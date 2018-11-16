# vscode-surround README

Surround selection with `if`, `try-catch`

## Purpose of this Repo

I like the surround plugin created by JuoCode but I discovered that it had several bugs that I chose to fix. I submitted a PR a long time ago but it was never merged. It appears that the plugin is no longer supported. To use my "fixed" version, follow the installation instructions below.

## Installing

The parent of this extension is available for free in the Visual Studio Code Marketplace

```
ext install vscode-surround
```

However, the pull request with the fix provided by this fork hasn't been accepted so you can install it by downloading the *.vsix file and running this command:

```
code --install-extension vscode-surround-1.0.1.vsix
```

## Usage

Surround with `if`
- Select what you want to surround
- Press `cmd+shift+p` open command panel
- Choose `Surround with if`

Surround with `try-catch`
- Select what you want to surround
- Press `cmd+shift+p` open command panel
- Choose `Surround with if`


## Release Notes

### 1.0.1

Fix selection issue after `try-catch` surrounded 

### 1.0.0

First release
