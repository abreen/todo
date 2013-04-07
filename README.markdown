# todo - A tool to help you do
`todo` is a basic shell script for `bash` (and probably other shells)
that manages a tiny file (by default, located at `~/todo`) with your
important tasks. Todos are manipulated via the command line through
simple, easy-to-remember commands.

1. `todo` or `todo list` lists all of your todos,
2. `todo add` adds a new todo,
3. `todo amend` amends an existing todo, and
4. `todo remove` removes the specified todo.

The file managed by `todo` is as simple as it gets. Each todo is written 
to a new line. `todo` merely adds and removes lines to this file. If you
outgrow `todo`, it can be easily transported to other GTD applications, as long
as you're comfortable with a little file manipulation from the command
line. `todo` tries to save to the file `~/todo` by default, but you can
change a simple variable in the source code to change this.

`todo` was inspired by and adheres to Douglas McIlroy's Unix philosophy:

*  Write programs that do one thing and do it well.
*  Write programs to work together.
*  Write programs to handle text streams, because that is a universal interface.

`todo` is my first foray into shell scripting. I hope you find it useful.
I tinker around with it sometimes. If you have something to contribute or
a bug to fix, don't hesitate to send a merge request!

`todo` is released under the
[GNU General Public License](http://www.gnu.org/copyleft/gpl.html).

## Installation
Before installing, verify you have a Linux Standard Base-compliant operating
system, or at the very least: `bash`, `awk`, and `sed`.

Probably the best way to install `todo` is to create a symbolic link to it from
some directory in your preferred shell's `PATH` variable, like this:

    ln -s todo /usr/local/bin/todo

Then you'll be able to use `todo` from anywhere.
