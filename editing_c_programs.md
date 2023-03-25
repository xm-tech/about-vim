Moving through a program
========================

`:checkpath` - show all recursively included files

`[i` - search for identifier under cusor in current and included files

`[ctrl-i` - jump to the match of `[i`

`[I` - list all lines in current and included files where identifier
    under the cusor matches

`[d` - search for #define under cusor in current and included files

`ctrl-]` - jump to tag under cusor (e.g., definition of a function or a variable)

`ctrl-t` - jump back to before a `ctrl-] command`

`gf`/`ctrl-w-f` - go file name under the cusor

`gd` - go to declaration of local variable under the cusor

`ctrl-w-d` - find the definition of the word under the cusor in a new window

`gD` - go to declaration of global variable under the cusor

`%` - go to matching (), [], {}, `/* */`, #if, #else, #endif

moving throught a program
-------------------------

`[#` - when u are somewhere inside a "#if" - "#endif", will jump to the start of
    the #if

`]#` - to jump forward to the next "#else" or "#endif"

`[{` - move to the last {

`]}` - move to the last }

`[(` - move to the last (

`])` - move to the last )

`[m` -to find the previous start of a method

`]m` - to find the next start of a method

`[/` - to move vack to the start of a comment

`]/` - tom move forward to the end of a comment

finding global identifies
-------------------------

> locating included files

`checkpath` - list the included fles that could be or could not be found

`checkpath!` - to see which included files are actually found

> jumping to a match

`[I` - listing the matching lines it can find, finding any identifier

`[tab` / `[ctrl-i]` - have a closer look at the first item matched by the `[I`
  ctrl-i is same as tab

`[i` - only list the first match

`]I` - only list the items below the curor

`]i` - only list the first items below the curor

`[D` - to find only macros, defined with `#define`

finding local identifies
------------------------

`gD` - go to the definition of a variable or function that was declared locally

`gd` - likely `gD`, but restrict the search only in the current function
