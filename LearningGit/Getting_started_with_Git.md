# Getting started with Git

## Tools

You'll need to install Git, and I recommend also installing your choice of GUI which will save you from needing to write code. Personally I (_author_) recommend Visual Studio Code (_VSCode_), but there are lots of options. 

Some of these are full Integrated Development Environments (_IDE_), which do ALL your programming needs, others just do the Git stuff.

- [Git - Git SCM](https://git-scm.com/)
- [Visual Studio Code - Microsoft](https://code.visualstudio.com/)
- [SourceTree - Atlassian](https://www.sourcetreeapp.com/)
- [TortoiseGit, Windows Shell - TortoiseGit](https://tortoisegit.org/)


## Tutorials

Git is **HUGE** in the software world, so there are an enormous wealth of tutorials for it. Check out these guys. 

- [Using Git with Visual Studio Code (Official Beginner Tutorial) - Visual Studio Code](https://youtu.be/i_23KUAEtUM?si=g4FdPGolwPDqiWYK)
- [Intro to VS Code & Git - PowerBI Tips](https://www.youtube.com/live/-v4nJoR8bJg?si=0Bvh8Kv-cx1WdvZ6)
- [Using source control - Guy in a Cube](https://youtu.be/zvyr2qYCQNo?si=jBYtwhcqlLIUZrmE)
- [Set your username - GitHub docs](https://docs.github.com/en/get-started/git-basics/setting-your-username-in-git)
- [Git guide - Roger Dudler](https://rogerdudler.github.io/git-guide/)
- [Git branches - Noble desktop](https://www.nobledesktop.com/learn/git/git-branches)
- [Git, the book - Git SCM](https://git-scm.com/book/en/v2)
- [How to Git Merge - Atlassian](https://www.atlassian.com/git/tutorials/using-branches/git-merge)
- [pull remote branch in source tree - StackOverflow](https://stackoverflow.com/questions/42073591/how-to-pull-remote-branch-in-source-tree)
- [SourceTree will not start - Atlassian Community](https://community.atlassian.com/forums/Sourcetree-questions/SourceTree-Splash-screen-only/qaq-p/2389527)
- [SourceTree token issues - StackOverflow](https://stackoverflow.com/questions/68191968/source-tree-fix-for-git-password-authentication-is-temporarily-disabled-as-part#:~:text=In%20Windows%2C%20go%20to%20C,you%20for%20your%20credentials%20again)

## Steps
0. Install Git
0. Set up your profile - **this will be public**
    ```powershell
    $ git config --global user.name "John Doe"
    $ git config --global user.email johndoe@example.com
    ```
0. Install VS Code (_or other IDE / Git GUI_)
0. Create a folder on your computer, relatively high in your files: 
    *i.e. a new folder within `C:` or `C:\Users\YOUR_NAME_HERE\Documents`*

    !!! tip "Long filepaths"
    
        Most computers have a maximum filename length and trying to clone this repo into a long filepath like `C:\Users\YOUR_NAME\Documents\Warhammer\FunProjects\PublicStuff\HeresySilhouettes\...` will throw a wobbly once it hits 256 characters
0. Open the project in GitHub *(where you're reading this)*, select `Code` and then the copy icon near "Clone using this web URL"
0. Open VS Code *(or equivalent)* and using the *Source Control* tab
0. Select "Clone Repository" and then paste the URL you copied earlier
0. Select the folder you made earlier as your "target directory"
0. Create a new branch
0. Make your changes
0. Save your changes
0. Stage & Commit your changes - this is where you put them on the Git record
0. Push your branch when you're done or the work has reached a stable milestone - this is what makes it accessible to others
0. Once it's ready for review, create a Pull Request on GitHub, outlining your changes!!
0. Someone will review & approve your changes, or give you suggestions to go back and fix
0. Done! 🎉🎉

!!! warning "Commit a file"
    Git doesn't upload empty folders, you have to create a file in the folder for it to be detected. 
    
    If someone hasn't created a file, there *should* be a placeholder in there.
