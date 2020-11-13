This document is a simplified version of
<a href="https://github.com/jfiksel/github-classroom-for-students" class="uri">https://github.com/jfiksel/github-classroom-for-students</a>,
written by Jacob Fiksel. This document is also adapted from
<a href="https://happygitwithr.com" class="uri">https://happygitwithr.com</a>.
This video is helpful:
<a href="https://www.youtube.com/watch?v=pAcMgGbCtQw&amp;feature=youtu.be" class="uri">https://www.youtube.com/watch?v=pAcMgGbCtQw&amp;feature=youtu.be</a>.

Getting setup with GitHub
-------------------------

1.  Register for an account on GitHub
    (<a href="https://github.com/" class="uri">https://github.com/</a>).
    Please use a username that contains your identification information.
2.  Install Git. See
    (<a href="https://happygitwithr.com/install-git.html" class="uri">https://happygitwithr.com/install-git.html</a>).

-   Windows: Install Git for Windows
    (<a href="https://gitforwindows.org/" class="uri">https://gitforwindows.org/</a>).
-   Mac: install Xcode command line tools. Go to terminal (Applications
    -&gt; Utilities -&gt; Terminal), type:

        git --version
        git config

1.  Configure GitHub.  
    You can type in Shell:

        git config --global user.name 'Stat Student'
        git config --global user.email 'stat-student@uiowa.edu'

    You may also do this using an R package:

          ## install.packages("usethis")
          library(usethis)
          use_git_config(user.name = "Stat Student", user.email = "stat-student@uiowa.edu")

2.  Set up SSH keys. Here is a very detailed instruction.
    <a href="https://happygitwithr.com/ssh-keys.html" class="uri">https://happygitwithr.com/ssh-keys.html</a>.
    You may skip this step until you are familiar with GitHub.

Downloading and editing homework from GitHub
--------------------------------------------

1.  In your computer, make a directory like STAT5400 and make a
    subdirectory called HW.
2.  Accept your assignment. Try the test link:
    <a href="https://classroom.github.com/a/rfCWPoDp" class="uri">https://classroom.github.com/a/rfCWPoDp</a>.
3.  Enter the homework repository on GitHub and clich “Clone or
    Download”. You have copied
    <a href="https://github.com/STAT5400-Fall2019/HW-8.git" class="uri">https://github.com/STAT5400-Fall2019/HW-8.git</a>
    in your clipboard.
4.  In Rstudio, go to File -&gt; New Project, and then click Version
    Control, and then Git. Paste the link you just copied, and create
    this as a subdirectory of the folder HW. Now you should see a list
    of the files in Rstudio. You can click on the file you want to edit
    and make changes. Click the .Rproj file if you leave and go back to
    continue your project.
5.  Commit these changes to your local repository. CLick the Git tab and
    check the file you want to commit. Click commit and type a message
    in “Commit message” such as “Added a comment line”. Click “Commit”.
6.  Click the green “Push” botton to send your local changes to GitHub.

Besides Rstudio, you can also use Git through Shell, or use some other
clients, like GitHub Desktop, SmartGit, etc.
