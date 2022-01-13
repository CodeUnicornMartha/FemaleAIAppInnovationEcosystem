# What is GitHub and Git?
## Git
Git is a form of tracking changes to your code.

Think of it like this:

You are working on a paper. You write five paragraphs. Then your friend comes along later, and writes another five paragraphs. Then you edit a few paragraphs, and your friend edits a few more paragraphs.

At the end of it, there are some issues, but its hard to coordinate who edited what and when.

With a system like Git, you would first create the file on the Git server, and add your changes. Then, you commit those changes to the repository, which will basically say 'Hey, this file exists and looks like this.'

Then, your friend checks out that repo, pulling the latest changes. He adds some stuff, then commits to the repo. The repo says 'Hey, this file exists and is different from the previous version, so we will save it as version 2.'

So on and so forth. The Git repo allows you and your friend to make edits and keep the changes sort of sequential, so if your friend messes up at #5, you can say 'Git, please check out #4' and you can get back to fixing things. Each commit has an owner, so you know who did what. And you can compare Version X to Version Y, and see what has changed, making it easier to spot what new changes have been made.

Git also allows you to branch. So you and your friend are on version 10 of the doc, but you want to try something new. Your friend wants to continue, so you create a branch called 'MyNewIdea' and start working on that. This is now a separate path of writing, while your friend continues on the original, which is usually considered the master or trunk. Get it? Branches and trunks.

So TL:DR Git basically lets multiple people access a central chunk of what is usually code, and make alterations to it without stepping on each others toes. Edit to add there's a bunch of other stuff Git lets you do, but simplified its a way of being able to track changes to a document with multiple users messing with the document, including making branches of the main document for individual development.

## GitHub
GitHub is just a website that works using Git that has a lot of code. Most of it is opensource, and the idea there is that if you wanted to add some paragraphs from someone on GitHub, you would just check out their Git repository and add it to your document, more or less.

[Source](https://www.reddit.com/r/explainlikeimfive/comments/2az038/eli5_what_is_a_git_and_github/)