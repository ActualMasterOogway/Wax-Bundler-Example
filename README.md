# Title

Description

## Prerequisites

To enhance your work environment, I recommend installing all the recommended [extensions](.vscode/extensions.json).

## Bundling everything

> [!IMPORTANT]
> Bundling should only be used for testing.
> If you want to make a new Release, please head to the GitHub "Actions" tab and run the "Release" action.

To bundle all the scripts, you have to follow these steps:

1. Install [rokit](https://github.com/rojo-rbx/rokit) if you haven't already
2. Open Powershell or the command-line shell of your liking and [cd to this repository](https://www.quora.com/What-does-it-mean-to-CD-into-a-directory-and-how-can-I-do-that-Can-someone-explain-it-in-a-laymans-term)
3. Run `rokit install` and wait for it to install all the dependencies
4. In VSCode, press CTRL + SHIFT + B to build or run this command `lune run Build bundle header=Build/Header.luau`

You can find the bundled script in '/Distribution/Script.luau'. If any issues occur or you are having troubles with the steps [contact ActualMasterOogway on discord](https://discord.com/users/820039511236411463) or [open a Issue on this repository](https://github.com/user/repo/issues).
