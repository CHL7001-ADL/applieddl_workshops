# Quick-Start Guide

Welcome to the Applied Deep Learning software installation quick-start guide! The following instructions should help you get setup with all necessary softwares as quick as possible and ready to run your first job on your local machine. This workshop will include the installation instructions of following tools and best practices to build your project: 

* Anaconda Python Distribution
* PyCharm IDE
* Git
* Unix Shell


# Installing Anaconda on OSX/Linux/Windows

This tutorial will demonstrate how you can install Anaconda, a powerful package manager, on your Mac.

Anaconda is a package manager, an environment manager, and Python distribution that contains a collection of many open source packages. An installation of Anaconda comes with many packages such as numpy, scikit-learn, scipy, and pandas preinstalled.

1. Go to the [Anaconda Website](https://www.anaconda.com/distribution/#macos) and choose a Python 3.x (recommended version in this course) graphical installer. 
2. Download and start the installation.

## Test your installation
### OSX/Linux

Open a new terminal on your Mac. You can do this by clicking on the Spotlight magnifying glass at the top right of the screen, type “terminal” then click on the terminal icon. Now, type the following command into your terminal:
```python
python --version
```

Another good way to test your installation is to try and open a Jupyter Notebook (a user-friendly notebook, where you can create and share documents that contain live code, equations, visualizations and narrative text). You can type the command below in your terminal to open a Jupyter Notebook. If the command fails, chances are that Anaconda isn’t in your path. 
```python
jupyter notebook
```

### Windows
Verify the success of your installation by opening Anaconda Prompt, a teminal that is included with Anaconda: from your Windows Start menu, select the shortcut Anaconda Prompt. Type same command as shown in OSX/Linux section.


# PyCharm 

PyCharm is an IDE made by the folks at JetBrain, a team responsible for one of the most famous Java IDE, the IntelliJ IDEA. It provides support for JavaScript, HTML/CSS, Angular JS, Node.js, and so on, what makes it a good option for web development.

PyCharm has interesting features such as a code editor, errors highlighting, a powerful debugger with a graphical interface, besides of Git integration, SVN, and Mercurial. You can also customize your IDE, choosing between different themes, color schemes, and key-binding. Additionally, you can expand PyCharm’s features by adding plugins; You can take a look at the PyCharm Plugins Library [here](https://plugins.jetbrains.com/pycharm).

1. Download the community edition of PyCharm for your operating system: [link](https://www.jetbrains.com/pycharm/download/#section=mac).
2. Start and create a new project with PyCharm.
3. Select Interpreter. Since this is a Anaconda based tutorial, choose your anaconda path (you can do which conda in the terminal to see where anaconda is) and click "create".


# Git

Git is the most widely used version control system. A version control system is something that records changes to a file or set of files over time so that you can recall specific versions later. Git is an important technology as it really helps you work with others and it is something you will find in a lot of workplaces. Some of the benefits of learning Git include:

* Nothing version controlled using Git is ever lost, so you can always go back to see previous versions of your programs.

* Git notifies you when your work conflicts with someone else's, so it's harder (but not impossible) to accidentally overwrite work.

* Git can synchronize work done by different people on different machines, so it scales as your team does.

Knowing Git makes it easier to contribute to open source development of packages in Python and R.

You can check the simple guide for getting started with Git [here](http://rogerdudler.github.io/git-guide/).



# Unix Shell

Navigating directories, copying files, using virtual machines, and more are a regular part of a data scientist's job. You will often find the Unix Shell utilized to accomplish these tasks.

Unix Shell provides a number of useful commands such as: `wc` command counts the number of lines or words in a file, `cat` command concatenates/merges files, head and tail commands help you subset large files. You can learn more about this in [8 Useful Shell Commands for Data Science](https://www.datacamp.com/community/tutorials/shell-commands-data-scientist).

## Unix Shell on OSX/Linux

Mac comes with a Unix shell so you usually don't need to install anything! An important point is that there is a variety of Unix systems that have different commands. Sometimes you find that you don't have a Unix command (like wget) found on another Unix system. Similar to how you have package managers through RStudio and Anaconda, Mac can have a package manager called Homebrew if you install it. 

## Unix Shell on Windows

Windows does not come with a Unix Shell. Keep in mind that what Unix Shell does for you is give you useful commands for Data Science. There are many different ways to get these useful commands on Windows. You can install [Git](https://git-scm.com/download/win) on Windows with the optional Unix tools so that you can have Unix commands on your Command Prompt. 


















