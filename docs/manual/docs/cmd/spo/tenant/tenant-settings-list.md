# spo tenant settings list

Lists the global tenant settings

## Usage

```sh
spo tenant settings list [options]
```

## Options

Option|Description
------|-----------
`--help`|output usage information
`-o, --output [output]`|Output type. `json|text`. Default `text`
`--verbose`|Runs command with verbose logging
`--debug`|Runs command with debug logging

!!! important
    To use this command you have to have permissions to access the tenant admin site.

## Examples

Lists the settings of the tenant

```sh
spo tenant settings list
```