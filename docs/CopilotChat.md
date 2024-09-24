# COPILOT CHAT #

Copilot chat is the way we communicate with Copilot outside our files.

Now, we are going to talk about the different tags that are oriented to its usage in Copilot Chat

## Providing context ##

When we use '@' the tag will reference to the context of the code.

Context is essential in Copilot Chat prompts.

**@workspace**

Using @workspace will tell Copilot to use your workspace as source information.

¡¡¡DON'T ADD ANY OTHER COMMAND OR CONTEXT COMMAND IF YOU ARE TRYING TO GET GENERAL INFORMATION ABOUT THE WHOLE WORKSPACE!!!

If you try to do so, instead of taking every file in the workspace as a reference, it will take single documents or just two or three files.

1. *Command:* `@workspace Generate a readme markdown document that can be used as a repo description`
- *Description:* Generates documentation containing a general description of the project.

2. *Command:* `@workspace Generate a readme markdown document that can be used as a repo description, it must be very detailed`
- *Description:* Generates documentation containing a more detailed description of the project.

3. *Command:* `@workspace generate readme project documentation formatted using a raw markdown format`
- *Description:* Generates documentation formatted using a raw markdown format.

4. *Command:* `@workspace Generate a project summary that can be used at an executive briefing`
- *Description:* Generates documentation more useful in a business talk.

## Providing intention ##

We can use '/' to give details about the intention we have when we are writing a prompt, in other words, the result we want to get.

### Combining ###

We can use a combination of context, intention and source to get a desired and specific result

1. *Command:* Command alone (`@workspace /explain`)
- *Description:* Explains the selected code or the file in the editor if there is nothing selected.

2. *Command:* `@workspace /explain why is #selection causing an error`
- *Description:* Explains the error in the selected portion of the code.

3. *Command:* `@workspace /explain how this test works`
- *Description:* Explains the functionality of a test.

3. *Command:* `@workspace /fix propose a fix for the errors in #file:<filename>`
- *Description:* Proposes posible solutions to the errors in a file.

[<<](CommonFeatures.md)[>>](InlineChat.md)

[Overwiew](/docs/Overview.md)
[Common/ Features](/docs/CommonFeatures.md)
[Copilot/ Chat](/docs/CopilotChat.md)
[Inline/ Chat](/docs/InlineChat.md)