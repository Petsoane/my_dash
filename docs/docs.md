# my_dash

## Usage
> This cli template shows the date and time in the terminal

my_dash

## Description

```
This is a template CLI application, which can be used as a boilerplate for awesome CLI tools written in Go.
This template prints the date or time to the terminal.
```
## Examples

```bash
cli-template date
cli-template date --format 20060102
cli-template time
cli-template time --live
```

## Flags
|Flag|Usage|
|----|-----|
|`--debug`|enable debug messages|
|`--disable-update-checks`|disables update checks|
|`--raw`|print unstyled raw output (set it if output is written to a file)|

## Commands
|Command|Usage|
|-------|-----|
|`my_dash completion`|generate the autocompletion script for the specified shell|
|`my_dash help`|Help about any command|
|`my_dash time`|Prints the current time|
# ... completion
`my_dash completion`

## Usage
> generate the autocompletion script for the specified shell

my_dash completion

## Description

```

Generate the autocompletion script for my_dash for the specified shell.
See each sub-command's help for details on how to use the generated script.

```

## Commands
|Command|Usage|
|-------|-----|
|`my_dash completion bash`|generate the autocompletion script for bash|
|`my_dash completion fish`|generate the autocompletion script for fish|
|`my_dash completion powershell`|generate the autocompletion script for powershell|
|`my_dash completion zsh`|generate the autocompletion script for zsh|
# ... completion bash
`my_dash completion bash`

## Usage
> generate the autocompletion script for bash

my_dash completion bash

## Description

```

Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:
$ source <(my_dash completion bash)

To load completions for every new session, execute once:
Linux:
  $ my_dash completion bash > /etc/bash_completion.d/my_dash
MacOS:
  $ my_dash completion bash > /usr/local/etc/bash_completion.d/my_dash

You will need to start a new shell for this setup to take effect.
  
```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion fish
`my_dash completion fish`

## Usage
> generate the autocompletion script for fish

my_dash completion fish

## Description

```

Generate the autocompletion script for the fish shell.

To load completions in your current shell session:
$ my_dash completion fish | source

To load completions for every new session, execute once:
$ my_dash completion fish > ~/.config/fish/completions/my_dash.fish

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion powershell
`my_dash completion powershell`

## Usage
> generate the autocompletion script for powershell

my_dash completion powershell

## Description

```

Generate the autocompletion script for powershell.

To load completions in your current shell session:
PS C:\> my_dash completion powershell | Out-String | Invoke-Expression

To load completions for every new session, add the output of the above command
to your powershell profile.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion zsh
`my_dash completion zsh`

## Usage
> generate the autocompletion script for zsh

my_dash completion zsh

## Description

```

Generate the autocompletion script for the zsh shell.

If shell completion is not already enabled in your environment you will need
to enable it.  You can execute the following once:

$ echo "autoload -U compinit; compinit" >> ~/.zshrc

To load completions for every new session, execute once:
# Linux:
$ my_dash completion zsh > "${fpath[1]}/_my_dash"
# macOS:
$ my_dash completion zsh > /usr/local/share/zsh/site-functions/_my_dash

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... help
`my_dash help`

## Usage
> Help about any command

my_dash help [command]

## Description

```
Help provides help for any command in the application.
Simply type my_dash help [path to command] for full details.
```
# ... time
`my_dash time`

## Usage
> Prints the current time

my_dash time

## Description

```
You can print a live clock with the '--live' flag!
```

## Flags
|Flag|Usage|
|----|-----|
|`-l, --live`|live output|


---
> **Documentation automatically generated with [PTerm](https://github.com/pterm/cli-template) on 04 February 2022**
