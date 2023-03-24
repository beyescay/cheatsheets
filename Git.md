# Git Cheatsheet

A concise cheatsheet of frequently used Git commands for seamless workflow experience.

## Table of Contents

- [New Repository](#new-repository)
- [Configuration](#configuration)
- [Alias](#alias)


### New Repository
- > **git init** - Intialize a git repository
- > **git clone <repository_url>** - Clone a repository
- > **git remote add <remote_name> <repository_url>** - Set a remote repository

### Configuration
- > **git config --global user.name <your_name>** - Set the name you want to appear in commits
- > **git config --global user.email <your_email>** - Set the email you want to appear in commits
- > **git config --list** - List all git configurations
- > **git config --global --unset <config_key>** - Unset a git configuration.

### Alias
- > **git config --global  alias.<your_alias_name> "<git_command>"** - Sets an alias for the <git_command>. See next command for an example.
- > **git config --global  alias.st "status"** - Now you can use **git st** to instead of **git status**. 
