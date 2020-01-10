Debugging:-

The two main techniques used to debug programs
are:

– Output messages (most commonly via a console or output window)
• As your program executes, write the value of variables or other messages to the console or other display

Or

– Debuggers
• Using the debugging feature of visual studio you can place breakpoints to pause your program as it executes and inspect & even alter the value of variables directly

What syntax errors exist?
-------------------------
A syntax error occurs when you write a statement that is not valid according to the grammar of the language.
This includes errors such as missing semicolons, using undeclared variables, mismatched parentheses or braces, etc… 
These will generally be reported in the Error List window of visual studio prior to compilation.

What linker errors exist?
-------------------------
You probably shouldn't see any linker errors in this project, however in other projects:-
If you include the correct header files for all of your functions, you still need to provide your linker with the
correct path to the library that has the actual implementation, not doing so can cause "undefined function" error
messages.  There are many other potential linker errors that crop up, but they generally require careful decrypting 
from the complex error reports generated.


What semantical errors exist?
-----------------------------
A semantic error occurs when a statement is syntactically valid, but does not do what the programmer intended.
Such as increasing the health of a character thats been attacked instead of decreasing it.


List & description of errors found:-
Please list all errors you have found during the debugging assessment mainly syntax & semantical.
Also provide a single line description of how you resolved it.
NB:- this should also be the same kind of description you are providing on your Github Commits.
