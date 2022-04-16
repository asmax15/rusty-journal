# Rusty journal
This repository contains the code for the CLI app, rusty journal. Rusty journal 
allows you to manage to do lists in your terminal. You can add tasks, remove tasks 
and you can list all available tasks.

You can also use more than one to do list at a time.

This little program is still in development.

## Usage
`$ rusty-journal [OPTIONS] <SUBCOMMAND>`

### Flags
* `-h, --help` - *Prints help information*
* `-v, --version` - *Prints version information*

### Options
* `-j, --journal-file <journal-file>` - *Use a different journal file*

### Subcommands
* `add` - *Write tasks to the journal file*
* `done` - *Remove an entry from the journal file by position*
* `list` - *List all tasks in the journal file*


## Planned Features
Feel free to submit your own ideas in the `issues` tab.

* Database integration
* Potentially a notion integration