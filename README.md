[![Sponsor](https://app.codesponsor.io/embed/MY7qFCdB7bDgiBqdjtV9ASYi/suzaku/shonenjump.svg)](https://app.codesponsor.io/link/MY7qFCdB7bDgiBqdjtV9ASYi/suzaku/shonenjump)

# Shonenjump [![Build Status](https://travis-ci.org/suzaku/shonenjump.svg?branch=master)](https://travis-ci.org/suzaku/shonenjump) [![Go Report Card](https://goreportcard.com/badge/github.com/suzaku/shonenjump)](https://goreportcard.com/report/github.com/suzaku/shonenjump)

shonenjump is a lightweight autojump clone written in Go.

# What does it do?

Quote from the description of [autojump](https://github.com/wting/autojump/):

> autojump is a faster way to navigate your filesystem. It works by maintaining a database of the directories you use the most from the command line.

> Directories must be visited first before they can be jumped to.

# Installation

1. [Download](https://github.com/suzaku/shonenjump/releases) the shonenjump binary for your platform, place it in a directory in your `$PATH`.
1. [Download](https://github.com/suzaku/shonenjump/blob/master/scripts/) the setup script for your shell and include it in your shell profile.

   For example, if you are using `zsh`, you can do the following:
    
   ```bash
   wget -O ~/.shonenjump.zsh https://raw.githubusercontent.com/suzaku/shonenjump/master/scripts/shonenjump.zsh
   echo 'source $HOME/.shonenjump.zsh' >> ~/.zshrc
```

1. If you are using `zsh`, you'll need an extra step to setup tab completion.

   You need to place a script into the `zsh/site-functions` directory:
   ```bash
   cd $(brew --prefix)/share/zsh/site-functions/
   wget https://raw.githubusercontent.com/suzaku/shonenjump/master/scripts/_j
   ```

# Usage

Usage is similar to [autojump](https://github.com/wting/autojump/#usage).

This section will be updated if different behaviors were to be added in the future.
