
# Introduction to GitHub
![github home page](https://user-images.githubusercontent.com/95081227/205900828-f930e396-6e53-4397-87ba-0d0f0f081a11.JPG)

Launched in 2008, GitHub has become one of the most popular version control systems used by software developers, with over 40 million users and over 100 million repositories. It allows users to store their code in a central repository and collaborate with other users on that code. With GitHub, users can collaborate on code, review changes, and track changes to their code. GitHub also allows users to access their code from anywhere in the world, making it easier for them to work with colleagues on different continents. GitHub is an essential tool for software developers, and its popularity continues to grow each year.

# What is GitHub?
GitHub is a web-based hosting service for version control using Git. It is a platform for developers to store, collaborate, and share code. Developers use GitHub to host their code, work together on projects, and showcase their work to the world. It has functions like code reviews, codespaces, Copilot, actions, and more. Leading global businesses like Stripe, Spotify, Uber, Slack, and others use it.

# Prerequisites
* Have Git installed on your local machine.
* Have GitHub Account.
 
# Why GitHub?
Although there are so many other competitors. However, GitHub stands out in several ways which includes

* **Version Control**: Github offers version control, which allows developers to track changes made to code and to easily roll back to a previous version if needed.
* **Collaboration**: Github enables developers and teams to collaborate on projects through pull requests, code reviews, and more.
* **Open Source Development**: Github is an open source platform, which means developers can take advantage of the many existing projects and contributions.
* **Documentation**: Github is a great place to host documentation for both public and private projects.
* **Hiring & Recruiting**: Github makes it easy for hiring managers and recruiters to view potential candidates’ work and contributions.
* **Project Management**: Github offers project management tools, such as issue tracking and milestone tracking, which help teams stay organized and on track.

# Git VS. GitHub

Git is a version control system, a tool to manage your source code history. It's a command-line tool, but there are also some other tools that provide a graphical user interface to Git such as GitHub and GitLab.

GitHub is a cloud-based hosting service that lets you manage Git repositories. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project. GitHub provides a web-based graphical interface and desktop as well as mobile integration. It also provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project. GitHub is mostly used for code.

| Git  | GitHub |
| ------------- | ------------- |
| Git is a version-control system used to track changes in files  | GitHub is a web-based platform that hosts Git repositories.  |
| Git is a command-line tool  | GitHub provides a web-based graphical interface  |
| Git is a local repository for tracking changes | GitHub is a remote repository that can be accessed from anywhere. |
| In Git, the user can commit changes to the local repository | GitHub the user can commit changes to the remote repository. |
| Git is used for source code management | GitHub is used for project management. |

# GitHub Desktop vs. Github CLI

Both GitHub Desktop and GitHub CLI are tools used to interact with GitHub repositories. Both tools allow users to manage their local and remote repositories, clone repositories from GitHub, create and manage branches, commit changes, and push and pull changes from GitHub. The main difference between the two are highlighted in the table below
| GitHub Desktop  | Github CLI |
| ------------- | ------------- |
| GitHub Desktop is a graphical user interface (GUI)l  | GitHub CLI is a command line interface (CLI).   |
| GitHub Desktop is more user-friendly and provides a graphical representation of the repository  | GitHub CLI requires users to use commands to make changes.  |
| GitHub Desktop provides a visual feedback of changes made | GitHub CLI requires users to type in commands to view the changes. |
| GitHub Desktop can be used to commit, add files, and sync changes with the server | GitHub CLI requires users to use commands for all these actions. |
| GitHub Desktop allows users to create branches easily  | GitHub CLI requires users to use commands to create branches. |

The preference for GitHub Desktop or Github CLI depends on the user's needs and preferences. For instance, GitHub Desktop is a more user-friendly option for those who are not familiar with command-line interfaces, while Github CLI is a better choice for users who prefer to use command-line interfaces and automate tasks.

# What to do and How to Do It on GitHub

# 1. Cloning on GitHub

Cloning on GitHub means to download a copy of a repository from a remote server to your local computer. It allows you to make a local copy of an entire project from a remote repository. This is helpful for creating your own local version of a repository to work with and make changes to.

# How to clone on GitHub
## Steps

1. Go to the GitHub page and login to your profile

![login](https://user-images.githubusercontent.com/95081227/205902306-2f4a8ce8-00ca-418b-b246-1aea6da01208.JPG)

2. Navigate to the repositories
![annotely_image](https://user-images.githubusercontent.com/95081227/205904904-4634b68f-2194-48aa-94eb-951b655d7822.jpeg)

3. Select the GitHub repository you wish to clone by clicking on it (in this project I will clone the [Git Demo Github repository](https://github.com/Christianaojo/Demo-Repository.git).)
![annotely_image (1)](https://user-images.githubusercontent.com/95081227/205905096-88fdd7a2-c9c1-44b3-b9fa-cd9a6d1f59fe.jpeg)

4. Once the repository opens, Click `Code` button and Copy the url for the repository by clicking on the copy icon using the HTTPS option.
![annotely_image (2)](https://user-images.githubusercontent.com/95081227/205905212-284aa33a-1d55-412c-99bf-218775db2a2a.jpeg)

5. Return to your Computer's home screen and Open `Terminal`

6. Type git clone and paste the link you copied in 3, press enter to start cloning. Depending on the dependencies in the repository it might take some time to clone.

For instance:

`git clone https://github.com/Christianaojo/Demo-Repository.git`
The GitHub repository will be downloaded (cloned) immediately to your PC.

![5](https://user-images.githubusercontent.com/95081227/205906811-848e8d65-3fdd-4f0b-8b90-77ea30f61e99.JPG)

## Congratulations! You have successfully cloned a repository.
