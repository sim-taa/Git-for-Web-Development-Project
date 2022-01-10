# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [ ] [Download xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) - these are your developer tools for mac 
2. [ ] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [ ] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection.
4. [ ] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [ ] [Download Slack](https://slack.com/help/articles/207677868-Download-Slack-for-Mac) - make sure your slack display name is your `first name` `last name` 
6. [ ] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [ ] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [ ] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)
9. [ ] Sign up for a free account on [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign[…]tTwOoXp_lCeLTC97pikTFa5cE58FWHwjjpTSGsGPRqR2AAaAh-MEALw_wcB)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
----
Git is a version control system. GitHub is a specific vendor for this version control system.
2. Why do we create a branch? 
----
Branching allows you to keep features and secondary units of work discrete from the main code. If there are any problems or changes in preference relating to a branch, it can easily be detached from the main body of work.
3. What is the purpose of a pull request? 
----
Code review. One of your collegues or partners should review your work with fresh eyes to catch your mistakes and find opportunities for improvement.
4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main. 
----
git checkout main
5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 
----
'Git pull' is a command used to update the local version of a repo from a remote repo. This is the most common way to update your repo and it includes merging. 
'git merge' will update your current branch with any new commits on the remote tracking branch. 
If you expect conflicts, you may want to use 'git fetch' instead. git fetch updates the remote tracking branches.
6. What is a merge conflict? How do you resolve a merge conflict? 
----
If developers fail to work in separate, isolated branches, there can be overlapping changes, for example two different line 7's.
To resolve the conflicts, git will tell you where the conflicts are. You will have to pick through to edit and choose the code to keep. Then, you use 'git add' and 'git commit' to edit and save.