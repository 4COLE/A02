## A02 IS117 @ NJIT SP24

## PART 0: Install Git

###### Install Git
- Download the installer from the official Git website (https://git-scm.com/) and follow the installation instructions appropriate for your operating system.
- After Git is installed you need to configure it with your name and email address. Open the terminal and run the following commands
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

###### Create a Github Account
- If you haven't already, sign up for a GitHub account at https://github.com/.

###### Create a new Repository
- Once logged in to GitHub, click on the "+" icon in the top-right corner and select "New repository." Give your repository a name, optionally add a description, choose whether it's public or private, and click on the "Create repository" button.

###### Clone the Repository
- If you want to work with a repository locally, you will need to clone it. Copy the repository URL from GitHub and run the following command
```
git clone <repository_url>
```

###### Make Changes and Commit
- Go to the directory where you cloned the rpository. Make changes to the files in your local copy by using your IDE, once done you need to stage them for commit using the '**git add .**' command
- This stages all changes in  the current direcotry for the next commit. You can also specify individual files instead of using '**.**' to stage all changes.
- After staging your changes, commit them to your local repository along with a message
```
git commit -m "Your commit message here"
```

###### Push Changes to GitHub
```
git push origin master
```

## PART 1: How to install and setup WebStorm

- Acquire a free educational license
  https://www.jetbrains.com/shop/eform/students
- Use the **"Offical document"** option when applying for a license
- After getting a License ID, download the WebStorm software
  https://account.jetbrains.com/licenses
- Follow the instructions to install WebStorm on your computer

###### Set up Git Integration in WebStore
- Open WebStorm
- Go to File > Settings (or WebStorm > Preferences on macOS).
- In the Settings/Preferences dialog, navigate to Version Control > Git.
- Check if Git is installed. If not, install it and specify the path to the Git executable.
- Click Apply and then OK to save the changes.

###### Clone a GitHub Repository
- Open WebStorm
- Go to VCS > Get from Version Control > Git.
- In the URL field, enter the URL of the GitHub repository you want to clone.
- Choose a directory for the local repository.
- Click Clone.

###### Make Changes and Commit
- Open the project in WebStorm.
- Make changes to the files in the project.
- Go to VCS > Git > Commit File....
- Enter a commit message describing the changes.
- Click Commit to commit the changes to your local repository.

###### Push Changes to Github
- After committing your changes, go to VCS > Git > Push....
- Make sure the correct branch is selected.
- Click Push to push your changes to the remote GitHub repository.

## PART 2: Glossary

- **Branch:** A parallel version of a repository, allowing you to work on different features or fixes simultaneously.
- **Clone:** Create a local copy of a repository from a remote source.
- **Commit:** Save changes to the local repository.
- **Fetch:** Retrieve changes from a remote repository.
- **Git:** A version control system used to track changes in files and coordinate work among multiple developers.
- **GitHub:** A web-based platform for hosting and sharing code repositories.
- **Merge:** Combine changes from one branch into another.
- **Merge Conflict:** Occurs when Git cannot automatically merge changes and requires manual intervention.
- **Push:** Upload local repository changes to a remote repository.
- **Pull:** Fetch changes from a remote repository and merge them into the local repository.
- **Remote:** A version of a repository hosted on a server, such as GitHub.
- **Repository:** A storage location for a project's files and revision history.

###### References
- JetBrains WebStorm Documentation: https://www.jetbrains.com/help/webstorm/
- GitHub Guides: https://guides.github.com/
- Pro Git Book: https://git-scm.com/book/en/v2
