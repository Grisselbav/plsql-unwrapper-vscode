# PL/SQL Unwrapper for VS Code

PL/SQL code that has been wrapped with the wrap utility of Oracle Database version 10g or newer can be unwrapped with this extension.

Runs locally without an internet connection.

## Example

Open a wrapped PL/SQL unit (procedure, function, package specification, package body, type specification, or type body) in an SQL editor. Right-click inside the editor to display the context menu and select `Unwrap PL/SQL`.

![Wrapped](https://github.com/Grisselbav/plsql-unwrapper-vscode/blob/main/images/wrapped.png?raw=true)

The unwrapped code replaces the editor's contents.

![Unwrapped](https://github.com/Grisselbav/plsql-unwrapper-vscode/blob/main/images/unwrapped.png?raw=true)

## Requirements

- The `Unwrap PL/SQL` command requires an editor that uses the SQL (`sql`) or PL/SQL (`oracle-sql`) language.

- The editor must contain wrapped code for the context menu to show the `Unwrap PL/SQL` command.

## Limitations

- The extension cannot unwrap code wrapped with the wrap utility before Oracle Database 10g.

## Installation

The extension is available in the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=Grisselbav.plsql-unwrapper).
