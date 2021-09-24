# A03
Tutorial How to use Git, GitHub, and WebStorm

GIT AND GITHUB SHARE SIMILAR INSTRUCTIONS ON HOW TO USE

1.	Create a repository:
    A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project
    needs. We recommend including a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It 
    also offers other common options such as a license file.
    
    Your repository can be a place where you store ideas, resources, or even share and discuss things with others.
    1.	In the upper right corner, next to your avatar or identicon, click and then select new repository.
    2.	Name your repository
    3.	Write a short description.
    4.	Select Initialize this repository with a README.
 
Click Create repository.
2.	Create a Branch:
    1.	Go to your new repository hello-world.
    2.	Click the drop down at the top of the file list that says branch: main.
    3.	Type a branch name, readme-edits, into the new branch text box.
    4.	Select the blue Create branch box or hit “Enter” on your keyboard.
 
Now you have two branches, main and readme-edits. They look exactly the same, but not for long! Next we’ll add our changes to the new branch

3.	Make and Commit Changes:
    On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit
    messages capture the history of your changes, so other contributors can understand what you’ve done and why.
        1.	Click the README.md file.
        2.	Click the  pencil icon in the upper right corner of the file view to edit.
        3.	In the editor, write a bit about yourself.
        4.	Write a commit message that describes your changes.
        5.	Click Commit changes button.
 
These changes will be made to just the README file on your readme-edits branch, so now this branch contains content that’s different from main.

4.	Open a Pull Request
    Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your
    contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are
    shown in green and red.
    
    As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.
    By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams, whether they’re down the hall or 10 time zones away.
    You can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub flow before working on larger projects.
    When you’re done with your message, click Create pull request!

5.	Merge your Pull Request:
    In this final step, it’s time to bring your changes together – merging your readme-edits branch into the main branch.
    1.	Click the green Merge pull request button to merge the changes into main.
    2.	Click Confirm merge.
    3.	Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.


**WebStorm: is an integrated development environment (DE) designed specifically for modern JavaScript.**

**Installation:**
There are two ways to install WebStorm
1.	You can install using TOOLBOX (https://www.jetbrains.com/toolbox-app/)
2.	Or Standalone installation (https://www.jetbrains.com/webstorm/download/#section=windows)

**Run WebStorm:**
To run WebStorm, find it in the Windows Start menu or use the desktop shortcut. You can also run the launcher batch script or executable in the installation directory under bin.

**Launch app:**
Once you launch WebStorm, you will see the Welcome screen, the starting point to your work with the IDE, and configuring its settings. This screen also appears when you close all opened projects. Use the tabs on the left side to switch to the specific welcome dialog.

**Customize environment:**
  1.	In the left-hand pane, click Customize.
  2.	In the Color theme area, specify the user interface theme. Choose the appropriate theme from the list or select the Sync with OS checkbox to use your system default theme.

  Gif
  You can change the theme at any time later in the Switch popup (Ctrl+`). For more information, see User interface themes.
    3.	Specify the keymap to use. Select the appropriate one from the list or click Configure and adjust the keymap as described in Configure keyboard shortcuts.
    4.	In the Accessibility area, specify the font size to use and adjust colors if necessary. Learn more from Accessibility.

Note: You can download and install additional plugins via the Marketplace

Open a new project:
  • On the Welcome Screen, click Open and then select the folder with your application in the dialog that opens.

**Create a new project:**
  1.	Click Create New Project on the Welcome screen or select File | New | Project from the main menu. The Create New Project Dialog opens.
  2.	In the left-hand pane, choose Empty Project. In the right-hand pane, specify the application folder and click Create.


**Create a new file in a project:**
  •	In the Project tool window, select the folder where you want to create a new file and press Alt+Insert.
  •	Alternatively, choose New from the context menu of the selection and then choose the file type from the list:
 
See Creating files and directories for more details.

For more details on WebStorm FAQs see https://www.jetbrains.com/help/webstorm/meet-webstorm.html

**TERMINOLOGY**

GIT: Is a command line version control system for tracking changes in computer files and coordinating work on those files among multiple people. Version control systems helps software developers track changes to a source code over time. It is mostly used for source code management in software development but can be used to track changes to documents shared by a team.
https://codeburst.io/so-wtf-is-git-fa7daa0e0271

GITHUB: Is a web-based graphical interface repository just like Git. It has other features, ‘such as wikis and basic task management tools for every project.’ You can see other features via the link.
https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/

Repository: is a location where you can store things. In this case you are storing data and managing it in a location such as Git or GitHub

Clone: It’s a command used to download an existing Git repository to your local computer. On GitHub you can store your repository locally and sync between the two locations.

Commit: it’s one of the core primary functions. It is used to save your changes to the local repository. Every time you save it assigns a unique ID (a.k.a. the ‘SHA’ or ‘hash’) that allows you to keep record of what changes were made and by who.
https://help.github.com/en/github/getting-started-with-github/github-glossary

Push: means to send your committed changes to a remote repository on GitHub.com.

Pull: refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you’re both working on, you’ll want to pull in those changes to your local copy so that it’s up to date.

Branch: is a parallel version of repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the ‘live’ version. When you’ve made the changes you want to make, you can merge your branch back into the master branch to publish your changes.

Merge: takes the changes from on branch (in the same repository or from a fork), and applies them into another. This often happens as a ‘pull request’ (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.

Merge Conflict: difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

Fetch: When you use git fetch, you’re adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.

Remote: This is the version of a repository or branch that is hosted on a server, most likely GitHub.com Remote version can be connected to local clones so that changes can be synced.

References:
How Git Works - https://www.atlassian.com/git
Create with GITHUB - https://guides.github.com/activities/hello-world/
How to use WebStorm - https://www.jetbrains.com/help/webstorm/meet-webstorm.html



