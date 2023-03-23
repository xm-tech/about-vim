Editing C Programs
==================

:checkpath - show all recursively included files
`[i` - search for identifier under cusor in current and included files
`[ctrl-i` - jump to the match of `[i`
`[I` - list all lines in current and included files where identifier
    under the cusor matches
`[d` - search for #define under cusor in current and included files
`ctrl-]` - jump to tag under cusor (e.g., definition of a function or a variable)
`ctrl-t` - jump back to before a `ctrl-] command`
`gf` - go file name under the cusor
`gd` - go to declaration of local variable under the cusor
`gD` - go to declaration of global variable under the cusor
`%` - go to matching (), [], {}, `/* */`, #if, #else, #endif

moving throught a program
-------------------------

[# - when u are somewhere inside a "#if" - "#endif", will jump to the start of
    the #if
]# - to jump forward to the next "#else" or "#endif"

finding global identifies
-------------------------

[tab
[ctrl-i
]I
[I
[i
[D

finding local identifies
------------------------
