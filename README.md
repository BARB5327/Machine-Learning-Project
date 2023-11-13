# Machine-Learning-Project
Machine Learning Project 2023
# GitHub Collaboration Guide

This guide assumes that the project is set up on GitHub and the team members are collaborators. The project is a Java project developed in NetBeans. We focus on direct collaboration in the `main` branch, which is not the standard approach for larger/more complex projects but is simpler for beginners or smaller teams.

## 1. Generate a Personal Access Token on GitHub

- On GitHub, click your profile photo, then click **Settings**.
- Click **Developer settings**.
- Click **Personal access tokens**, then **Generate new token**.
- Select the appropriate permissions, give your token a descriptive name, and click **Generate token**.
- **Copy your new personal access token immediately**; you won’t be able to see it again!

## 2. Setup

- Download and install Git from [https://git-scm.com/downloads](https://git-scm.com/downloads). Git is preinstalled on MacOS and Linux.
- Configure Git with your username and email using the terminal (or command prompt):

    ```shell
    git config --global user.name "Your Name"
    git config --global user.email "your-email@example.com"
    ```

## 3. Clone the Project

- Open your terminal or command prompt.
- Change the directory to where you want to place the project.

    ```shell
    cd [YOUR PROJECT LOCATION]
    ```

- Run the following command and enter your GitHub username and the personal access token when prompted:

    ```shell
    git clone https://github.com/BARB5327/Machine-Learning-Project.git
    ```

## 4. Regularly Pull the Latest Changes

To ensure you’re working on the latest version of the project, you should pull the latest changes from GitHub:

- Inside your project directory in your terminal, ensure you are on the main branch:

    ```shell
    git checkout main
    ```

- Pull the latest changes:

    ```shell
    git pull
    ```

## 5. Open and Edit the Project in NetBeans

- Launch NetBeans and open the project from the directory where you cloned it.
- Make your changes to the project files as needed.

## 6. Commit and Push Your Changes

After making your changes, push them to the remote repository:

- Go to your terminal.
- Inside the project directory, add the files that you've changed:

    ```shell
    git add .
    ```

- Commit your changes with a message:

    ```shell
    git commit -m "Your brief description of the changes"
    ```

- Push your changes back to the GitHub repository:

    ```shell
    git push
    ```

- If prompted, use your GitHub username and personal access token as the password.

**Note**: It’s essential to communicate with your team members when using this approach because everyone is working on the same branch. Regular updates and status checks can help prevent conflicts and confusion.

