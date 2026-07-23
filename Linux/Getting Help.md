## 1. What is that?
$ ncal -w

2. man pages

The man pages, short for manual pages, are built-in form of documentation available on nearly all UNIX-like operating systems.

The specific contents vary from one operating system to another, but at a bare minimum the man man pages include information on commands and their usage.

3. How to read man pages?

To read the specific piece of documentation associated with a given command,

run: $ man command

Example: to learn more about the ncal command

we could run $ man ncal

This displays a bunch of information on ncal that we can scroll through.

Type q to exit.

4. man pages contents (general pattern)

The title/name of the command with a short explanation of its purpose.

Synopsis of the command's syntax.

Description of all the command's options.

5. man pages synopsis

ncal [-31bhJeoSM] [-A number] [-B number] [-d yyyy-mm] [year]

Anything inside [] is OPTIONAL.

The only required part is ncal.

* [-31bhJeoSM] We can use these options (-3, -1, -b, -h, -J, -e, -o, -S, -M) without any additional parameter.

[-A number] -A option expects a number.

[-B number] -B option expects a number.

[-d yyyy-mm]→ -d option expects a date in the format: yyyy -mm (e.g., 1980-04)

[year] We can pass a year as a parameter.
