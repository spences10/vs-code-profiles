# VSCode Profiles

To create specific sets of settings and VS Code extensions, this can
be stored in a repo or locally on your machine.

Originally taken from Andy Van Slaars GitHub [repo] you can use
profiles in VSCode.

I have set up a folder for [OBS Studio]

## Linux

```bash
code --extensions-dir ~/repos/vscode-profiles/obs/exts/ --user-data-dir ~/repos/vscode-profiles/obs/data/
```

Create an alias for it in fish:

```bash
alias obsCode 'code . --extensions-dir ~/repos/vscode-profiles/obs/exts/ --user-data-dir ~/repos/vscode-profiles/obs/data/'
```

## Windows Subsystem Linux [WSL]

If you're a WSL user your config is slightly different:

```bash
code --extensions-dir 'D:\repos\vs-code-profiles\obs\exts' --user-data-dir 'D:\repos\vs-code-profiles\obs\data'
```

Fish alias on WSL looks like this:

```bash
alias obs 'code --extensions-dir "D:\repos\vs-code-profiles\obs\exts" --user-data-dir "D:\repos\vs-code-profiles\obs\data"'
funcsave obs # to save the alias for next time
```

[repo]: https://github.com/avanslaars/code-profiles
[obs studio]: https://obsproject.com/
