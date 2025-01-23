# Discord All-Questions Channel Question Template

Asking a software/environment question professionally involves following these steps:

1. Use a Clear and Descriptive Post Title
2. Confirming the Environment You Are Using
3. Basic Validation and Debugging Checks
4. Structure Your Question
5. Show us the error/output screenshot(~s)

We’ve crafted a simple template and questionnaire just for you! Copy and paste it into your Discord post, follow the TEMPLATE steps, and watch how it helps you tackle problems more efficiently!

## TEMPLATE to copy

1. Use a Clear and Descriptive Post Title

   Start with the terminal command name or software item name that you have issues with.

   `Your answer goes here…`

2. Confirming the Development Environment You Are Using

   Which environment did you use when the issue happened?

   `Remove those that don't apply...`

   - MacOS/terminal
   - Windows/Terminal/Powershell
   - Windows/WSL/Ubuntu
   - Other environment (Please, describe the environment you used)

3. Basic Validation and Debugging Checks

   Answer YES or NO to the following:

- Did you make a search through older posts (Y/N)?
  - Please make sure to provide a link to the post you found.
- Did you execute commands or used the installation way following the Orientation instructions to a word? (Y/N):
  - Please make sure to follow the instructions if the answer is "N"
- Did you get any errors on any previous steps? (Y/N):
  - Move to the next step if the next question if the answer is N
  - Please, provide screenshots if the answer is "Y"
- Did you try to execute the commands that displayed errors one more time? (Y/N):
  - Please try to execute those commands one more time if the answer is "N"
  - Please, provide screenshots if the answer is "Y":
- If the problem is about failing the github connection:
  - Have you generated the ssh key? (Y/N):
  - Did you add the PUBLIC key to your github account ssh keys list? (Y/N):
  - Did you try to restart the ssh agent and add the PRIVATE key to the list of entities? (Y/N):
  - Did you try to generate another ssh key and add it to your github account? (Y/N):

4. Structure Your Question

- Identify the Goal/What You Want to Happen

  Briefly explain the desired behavior and outcome you expect to happen.

  `Your answer here…`

- Identify the Problem or Obstacle You are Facing

  Briefly explain what is happening instead of what you want to happen.

  `Your answer here…`

- What Do You Think the Root Cause of the Blocker/Problem Is?

  Share an educated guess as to why you think the problem is occurring.

  `Your answer here…`

5. Show us the error/output screenshot(~s)

Share the screenshot of the problem/issue.

`Your answer here…`

### TEMPLATE Requirements and examples

!!! HINT: Even if the question is a Yes/No one, always try to add relative context (screenshots) to help others help you better.

#### Use a Clear and Descriptive Post Title

> [ Start with the terminal command name or software item name that you have issues with and the brief environment description. ]

Examples:

- ❌ Bad: "My terminal doesn't work"
- ❌ Bad: "I cant open a folder! Need help!"
- ❌ Bad: "My terminal was not installed correctly and I can't follow the instructor's video!"
- ✅ Great: "The open command shows an error in WSL Ubuntu terminal"

#### Confirming the Development Environment You Are Using

> [ Which environment did you use when the issue happened? ]

`Remove those that don't apply...`

- MacOS/terminal
- Windows/WSL/Ubuntu
- Other environment (Please, describe the environment you used)

Remove the items that you DID NOT use. If your choice is "Other" please make sure to share which environment you used.

Examples:

- ❌ Bad: Empty (no answer)
- ✅ Great: Windows/WSL/Ubuntu

#### Basic Validation and Debugging Checks

Answer YES or NO to the following:

> Did you make a search through older posts (Y/N)

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: No
- ✅ Not Bad: Yes but I didn't find any relative to my issue
- ✅ Great: Yes. I found a thread with a similar issue, and followed all the step suggested in the answer but it didn't help.

[Link](https://discord.com/channels/747547219586056295/1058058486791016498)

> Did you execute commands or used the installation way following the Orientation instructions to a word? (Y/N):

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: No
- ✅ Not Bad: Yes (single word with no context)
- ✅ Great: Yes. I used the `open PROJECTS` command and it failed.

> Did you get any errors on any previous steps? (Y/N):

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: Y (a single word answer)
- ✅ Great: Y, here is a screenshot of the terminal.
- ✅ Great: N.

> Did you try to execute the commands that displayed errors one more time? (Y/N):

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: N
- ✅ Great: Y, but it didn't help and gave me the same result

> If the problem is about failing the github connection:
> Have you generated the ssh key? (Y/N):

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: N
- ✅ Great: Y

> Did you add the PUBLIC key to your github account ssh keys list? (Y/N):

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: N
- ✅ Great: Y

> Did you try to restart the ssh agent and add the PRIVATE key to the list of entities? (Y/N):

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: N
- ✅ Great: Yes I did, but still no luck.

> Did you try to generate another ssh key and add it to your github account? (Y/N):

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: N
- ✅ Not Bad:
- ✅ Great: Y

#### Structure Your Question

##### Identify the Goal/What You Want to Happen

> [ Briefly explain the desired behavior and outcome you expect to happen. ]

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: Screenshot attached.
- ✅ Good: In the instructor's video a folder is opened on command execution

##### Identify the Problem or Obstacle You are Facing

> [ Briefly explain what is happening instead of what you want to happen. ]

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: Screenshot attached.
- ✅ Good: My terminal says "open" not found instead

##### What Do You Think the Root Cause of the Blocker/Problem Is?

> [ Share an educated guess as to why you think the problem is occurring. ]

Examples:

- ❌ Bad: Empty (no answer)
- ❌ Bad: No idea.
- ❌ Bad: I don't know.
- ✅ Good: I have a hunch the open command is not built into Linux shell.

#### Show us the error/output screenshot(~s)

Please share your code professionally. Screenshots of the code, codeblocks without syntax highlighting and codepen links are not acceptable. Make sure to use one of the suggested methods.

- ❌ Bad: Empty (no answer)
- ❌ Bad: No
- ✅ Good: Screenshots attached