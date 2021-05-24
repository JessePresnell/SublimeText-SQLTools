![SQLTools](https://github.com/mtxr/SQLTools/raw/images/icon.png?raw=true) SQLTools
===============

> Looking for maintainers! I'm currently using VSCode as my editor, so I'm not actively maintaining this project anymore.
>
> If you are interested in maintaining this project, contact me.
>
> If you are interested in checking VSCode version, see [https://github.com/mtxr/vscode-sqltools](https://github.com/mtxr/vscode-sqltools).


[![Join the chat at https://gitter.im/SQLTools/Lobby](https://badges.gitter.im/SQLTools/Lobby.svg)](https://gitter.im/SQLTools/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Your swiss knife SQL for Sublime Text.

Write your SQL with smart completions and handy table and function definitions, execute SQL and explain queries, format your queries and save them in history.

Project website: [https://code.mteixeira.dev/SublimeText-SQLTools/](https://code.mteixeira.dev/SublimeText-SQLTools/)

> If you are looking for VSCode version go to [https://github.com/mtxr/vscode-sqltools](https://github.com/mtxr/vscode-sqltools).

## Donate

SQLTools was developed with ♥ to save us time during our programming journey. But It also takes me time and efforts to develop SQLTools.

SQLTools will save you (for sure) a lot of time and help you to increase your productivity so, I hope you can donate and help SQLTools to become more awesome than ever.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RSMB6DGK238V8" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a>

## Features

* Works with PostgreSQL, MySQL, Oracle, MSSQL, SQLite, Vertica, Firebird and Snowflake
* Smart completions (except SQLite)
* Run SQL Queries &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+e</kbd>
![Auto complete and run SQL queries](https://github.com/mtxr/SQLTools/raw/images/execute_auto_complete.gif?raw=true)
* View table description &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+d</kbd>
![View table schemas](https://github.com/mtxr/SQLTools/raw/images/table_description.gif?raw=true)
* Show table records &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+s</kbd>
![Show table records](https://github.com/mtxr/SQLTools/raw/images/table_records.gif?raw=true)
* Show explain plan for queries &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+x</kbd>
* Formatting SQL Queries &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+b</kbd>
![Formatting SQL Queries](https://github.com/mtxr/SQLTools/raw/images/format_sql.gif?raw=true)
* View Queries history &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+h</kbd>
* Save queries &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+q</kbd>
* List and Run saved queries &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+l</kbd>
* Remove saved queries &nbsp; <kbd>CTRL+e</kbd>, <kbd>CTRL+r</kbd>
* Threading support to prevent lockups
* Query timeout (kill thread if query takes too long)


## Installation

### By Package Control

1. Download & Install **`Sublime Text 3`** (https://www.sublimetext.com/3)
1. Go to the menu **`Tools -> Install Package Control`**, then,
    wait few seconds until the installation finishes up
1. Now,
    Go to the menu **`Preferences -> Package Control`**
1. Type **`Add Channel`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
    input the following address and press <kbd>Enter</kbd>
    ```
    https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
    ```
1. Go to the menu **`Tools -> Command Palette...
    (Ctrl+Shift+P)`**
1. Type **`Preferences:
    Package Control Settings – User`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
    find the following setting on your **`Package Control.sublime-settings`** file:
    ```js
    "channels":
    [
        "https://packagecontrol.io/channel_v3.json",
        "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
    ],
    ```
1. And,
    change it to the following, i.e.,
    put the **`https://raw.githubusercontent...`** line as first:
    ```js
    "channels":
    [
        "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
        "https://packagecontrol.io/channel_v3.json",
    ],
    ```
    * The **`https://raw.githubusercontent...`** line must to be added before the **`https://packagecontrol.io...`** one, otherwise,
      you will not install this forked version of the package,
      but the original available on the Package Control default channel **`https://packagecontrol.io...`**
1. Now,
    go to the menu **`Preferences -> Package Control`**
1. Type **`Install Package`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
    search for **`SQLTools`** and press <kbd>Enter</kbd>

See also:

1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


### Using SQLTools with Mac OS X

Sublime Text has it's environment variable `PATH` set from launchctl, not by your shell. Binaries installed by packages such as homebrew, for instance `psql` DB CLI for `PostgreSQL`, cannot be found by Sublime Text and results in error in Sublime Text console by `SQLTools`. Installing the package `Fix Mac Path` or setting the full path to your DB CLI binary in `SQLTools.sublime-settings` resolves this issue. Package can be downloaded via [PackageControl](https://packagecontrol.io/packages/Fix%20Mac%20Path) or [github](https://github.com/int3h/SublimeFixMacPath).

## Contributors

This project exists thanks to all the people who [contribute](https://github.com/mtxr/SublimeText-SQLTools/graphs/contributors).


## Configuration

Documentation: [https://code.mteixeira.dev/SublimeText-SQLTools/](https://code.mteixeira.dev/SublimeText-SQLTools/)




