# todo - A tool to help you do
`todo` is a basic shell script for bash that manages a tiny file (by default, located at `~/todo`) with your important tasks. Todos are manipulated via the command line through simple, easy-to-remember arguments.

> `todo list` lists all your todos in a numbered list

> `todo add ...` adds a todo with a specified title

> `todo remove #` removes a specified todo by its number

The file managed by `todo` is as simple as it gets. If you outgrow `todo`, it can be easily transported to other GTD applications. If you don't like `~/todo` as a location, you can change one variable in `todo`'s source code.

`todo` is my first foray into shell scripting. I hope you can find it useful enough to contribute some time to the probject. It is released under the [GNU General Public License](http://www.gnu.org/copyleft/gpl.html).

## Installation
Probably the best way to install `todo` is to create a symbolic link to it from
some directory in your preferred shell's `PATH` variable, like this:

    ln -s todo /usr/local/bin/todo

Then you'll be able to use todo from anywhere.
