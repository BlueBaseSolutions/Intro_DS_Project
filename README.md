# Intro_DS_Project
This repository has been prepared for the TechLabs Data Science Project by [Blue Base](https://bluebasesolutions.com/). It is based on the [cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science) repository. We are confident that this repository will help you to get started with your project.

Before you get started make sure you have prepared the following:
- A GitHub account
- Git versioning on your local machine
- Installed Anaconda
- Read below about Git, conda virtual environments and cookiecutter

## Git
Git is a version control system that is commonly used by software developers to manage and track changes to their code. It allows developers to easily collaborate on projects, and to keep track of different versions of their code. This is useful for several reasons:

- It allows developers to work together on the same codebase, without conflicts or overwriting each other's changes. This makes it easier for developers to collaborate, and can also help to prevent errors or bugs caused by conflicting changes.
- It allows developers to easily switch between different versions of their code, and to experiment with new ideas or features without affecting the main codebase. This can be useful for testing, debugging, or trying out new ideas without risking the stability of the main code.
- It provides a history of changes to the code, so that developers can see who made what changes, when they were made, and why. This can be useful for tracking down bugs, understanding how the code has evolved over time, and for reviewing changes made by other developers.

Overall, Git is a powerful tool for managing and tracking changes to code, and is widely used by software developers. It allows developers to easily collaborate and work together on projects, and provides a robust system for tracking and managing different versions of their code.

The most important Git commands to know are:
- `git init` - Initialize a new Git repository
- `git add` - Add files to the staging area
- `git commit` - Commit changes to the local repository
- `git push` - Push changes to the remote repository
- `git pull` - Pull changes from the remote repository

Please review the following [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) if you need more information about these commands.

For a more thorough review of Git, check out the following [Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk).

## Conda virtual environment
In Python, a virtual environment is a way to create a separate, independent Python environment that has its own set of libraries and dependencies. This is useful for several reasons:

It allows you to have different versions of the same library or package installed on the same machine, without them conflicting with each other. For example, you could have one Python project that uses version 1.0 of a particular library, and another project that uses version 2.0, and both can be installed and used on the same machine without any issues.

It helps to keep your global Python environment clean and organized, by allowing you to install packages and libraries only for the specific project that needs them. This can prevent your global Python environment from becoming cluttered with unnecessary packages, and can also help to prevent conflicts between different packages.

It allows you to easily switch between different environments, which can be useful when working on multiple projects that have different requirements. For example, if you have one project that requires version 1.0 of a particular library, and another project that requires version 2.0, you can easily switch between the two environments as needed.

Overall, virtual environments are a useful tool for managing and organizing your Python projects and their dependencies. They can help you to avoid conflicts between different packages, keep your global Python environment clean and organized, and easily switch between different environments as needed.

If you need more help managing your virtual environments, check out the [Managing Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) section of the Conda documentation.

## Cookiecutter
In Python, a cookiecutter template is a way to create a template or boilerplate for a new project, which can be used as a starting point for a new project. This is useful for several reasons:

- It allows you to quickly and easily create a new project with a well-defined structure and set of default files and directories. This can save you a lot of time and effort, as you don't have to manually create all of these files and directories yourself.
- It helps to ensure that your new project is set up in a consistent and organized manner, following best practices and conventions. This can make your project easier to work with, and can also make it easier for others to contribute to your project.
- It allows you to customize and configure the template to meet the specific needs of your project. For example, you can specify the name of your project, the version of Python you want to use, and any other settings or options that are relevant to your project.

Overall, cookiecutter templates are a useful tool for creating new Python projects in a consistent and organized manner. They can save you time and effort, help to ensure that your projects are set up properly, and allow you to customize the template to meet your specific needs.

If you need more information about the cookiecutter-data-science template, check out the [Cookiecutter Data Science Docs](https://drivendata.github.io/cookiecutter-data-science/)

## Steps to get started
1. Clone and copy the contents of this repository into your own GitHub repository
2. `conda create --name techlabs cookiecutter`
3. `conda activate techlabs`
4. `cookiecutter -c v1 https://github.com/drivendata/cookiecutter-data-science`
5. `cd <project_name>`
6. `pip install -r requirements.txt`