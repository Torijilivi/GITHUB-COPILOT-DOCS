## COMMON FEATURES ##

In this point you can find information about elements useful in both chats.

If there are details that change between them it will be in brackets.

# Providing sources #

When we are asking something to Copilot, we must provide the information we are asking about, if we want to know how a block of code works we must provide the block of code itself.

In order to do this, we use tags with the '#' symbol.

***file***

This tag will be useful to refer to a file or a group of files if used more than once.

(COPILOT CHAT)
1. *Command:* `Explain how #file:<filename> works`
- *Description:* Explains the content of a file.

(INLINE CHAT)
1. *Command:* `Modify my code to use procedures from #file:<filename>`
- *Description:* Modifies the code of the file to use procedures declared in <filename> .

# Providing intention #

We can use '/' to give details about the intention we have when we are writing a prompt, in other words, the result we want to get.

***/explain***

Explains code and everything you ask him to explain.

(COPILOT CHAT)
¡¡¡THIS COMMAND WILL TAKE YOUR SELECTION AS INPUT. IF YOU DON'T HAVE ANYTHING SELECTED, IT WILL TAKE THE FILE IN YOUR EDITOR!!!
1. *Command:* `@workspace /explain Explain the code`
- *Description:* Explains the code in the file you have opened in the editor.

(INLINE CHAT)
1. *Command:* `/explain Explain the selection of code`
- *Description:* Explains the code you have selected.

***/fix***

Analyses errors or bad practices in code.

(COPILOT CHAT)
¡¡¡THIS COMMAND WILL TAKE YOUR SELECTION AS INPUT. IF YOU DON'T HAVE ANYTHING SELECTED, IT WILL TAKE THE FILE IN YOUR EDITOR!!!
1. *Command:* `@workspace /fix Fix the errors in the code`
- *Description:* Proposes working code with error fixes, explaining them, or proposes code with good practices.

(INLINE CHAT)
1. *Command:* `/fix Fix the errors`
- *Description:* Generates a working alternative for the code you have selected.

***/tests***

Gets to possible tests for the code you are working with.

(COPILOT CHAT)
¡¡¡THIS COMMAND WILL TAKE YOUR SELECTION AS INPUT. IF YOU DON'T HAVE ANYTHING SELECTED, IT WILL TAKE THE FILE IN YOUR EDITOR!!!
1. *Command:* `@workspace /tests Tests for the code`
- *Description:* Proposes tests to check if the code is working correctly.

(INLINE CHAT)
1. *Command:* `/tests Generate tests`
- *Description:* Generates tests for the procedures in your file or selected code.