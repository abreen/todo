# todo - A tool to help you do
`todo` is a basic shell script for bash that manages a tiny file (by default, located at `~/todo`) with your important tasks. Todos are manipulated via the command line through simple, easy-to-remember arguments.

> `todo list` lists all of your todos
> `todo add <string>` adds a new todo
> `todo amend <#>` amends an existing todo
> `todo remove <#>` removes the specified todo

The file managed by `todo` is as simple as it gets. If you outgrow `todo`, it can be easily transported to other GTD applications. If you don't like `~/todo` as a location, you can change one variable in `todo`'s source code.

`todo` was inspired by and adheres to Douglas McIlroy's Unix philosophy:

*  Write programs that do one thing and do it well.
*  Write programs to work together.
*  Write programs to handle text streams, because that is a universal interface.

`todo` is my first foray into shell scripting. I hope you find it useful. It is released under the [GNU General Public License](http://www.gnu.org/copyleft/gpl.html).

## Installation
Probably the best way to install `todo` is to create a symbolic link to it from
some directory in your preferred shell's `PATH` variable, like this:

    ln -s todo /usr/local/bin/todo

Then you'll be able to use todo from anywhere.
