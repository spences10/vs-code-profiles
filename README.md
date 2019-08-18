# VSCode Profiles

Taken from Andy Van Slaars GitHub [repo] you can use profiles in
VSCode.

He uses an alias in ZSH but I use Fish so will be doing so for that.

I will set up a folder for [OBS Studio]

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
