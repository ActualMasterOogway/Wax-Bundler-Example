# Title

Description

## Prerequisites

- `git clone` this repository (preferred) or fork this repository

To enhance your work environment, we recommend installing the [Luau LSP Extension](https://marketplace.visualstudio.com/items?itemName=JohnnyMorganz.luau-lsp). We suggest using Version 1.36.0, as it is the version we utilize.

## Bundling everything

> [!IMPORTANT]
> Bundling should only be used for testing.
> If you want to make a new Release, please head to the GitHub "Actions" tab and run the "Release" action.

To bundle all the scripts, you have to follow these steps:

1. Install [rokit](https://github.com/rojo-rbx/rokit) if you haven't already
2. Open Powershell or the command-line shell of your liking and [cd to this repository](https://www.quora.com/What-does-it-mean-to-CD-into-a-directory-and-how-can-I-do-that-Can-someone-explain-it-in-a-laymans-term)
3. Run `rokit install` and wait for it to install all the dependencies
4. Run `lune run Build bundle input='default.project.json' minify=true output='Distribution/Script.luau' env-name="Script" darklua-config-path="Build/DarkLua.json" temp-dir-base="Distribution" verbose=true`

You can find the bundled script in '/Distribution/Script.luau'. If any issues occur or you are having troubles with the steps [contact ActualMasterOogway on discord](https://discord.com/users/820039511236411463) or [open a Issue on this repository](https://github.com/user/repo/issues).
