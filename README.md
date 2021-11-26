# grabit
Copy files easily from a set of pre-defined directories

## How to install
Simply download the `grabit` file and place it in your PATH

## How to use
First, set the GRAB_PATH to directories that you wish to grab from.
For example, $HOME/templates, if you place your template files there.
Multiple directories are separated by `:`, just like how it's done in PATH.

Then, you can simply invoke:
```bash
grabit [filename]
```
to copy that file into the current working directory.
