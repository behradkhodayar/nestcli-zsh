# NestJS CLI Zsh Plugin

This plugin provides Zsh command-line completion for the [Nest.js CLI](https://github.com/nestjs/nest-cli).

## Installation

### Using a Plugin Manager (e.g., Oh My Zsh)

Clone the repository into your Oh My Zsh custom plugins directory:

`git clone https://github.com/behradkhodayar/nestcli-zsh.git ${path_to_.oh-my-zsh_dir}/custom/plugins/nest`

Add the plugin to your .zshrc file:

`plugins=(... nest`)

Restart your shell or source your .zshrc file:

`source ~/.zshrc`

### Manual Installation

Clone the repository:

`git clone https://github.com/behradkhodayar/nestcli-zsh.git`

Source the plugin in your `.zshrc` file:

`source /path/to/nestjs-zsh/_nest`

Restart your shell or source your `.zshrc` file:

`source ~/.zshrc`

## Usage

Once installed, the plugin will automatically provide completions for nest commands. Simply type nest and press Tab to see the available commands.

`nest <Tab>`

You'll see a list of available commands, such as new, add, generate, build, etc.

The plugin also provides completions for the `add`, `generate`, `start` & `build` command's options & subcommands:

```shell
nest add <Tab>
nest generate <Tab>
nest start <Tab>
nest build <Tab>
```

So for example, hitting <kbd>Tab</kbd> on `nest generate` will show a list of available elements to generate, such as module, controller, service, etc.
