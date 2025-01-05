
## **Git and GitHub 101**


### **1. Theoretical Part (20-25 minutes)**

#### **1.1. Introduction to Git (5 minutes)**

-   What is a version control system?
-   Key benefits of using Git.
-   Difference between local and remote repositories.

#### **1.2. Git Basics (10 minutes)**

-   Essential commands:
    -   `git init` — initializing a repository.
    -   `git add` and `git commit` — staging and committing changes.
    -   `git status` — checking repository status.
    -   `git log` — viewing the commit history.

#### **1.3. Introduction to GitHub (10 minutes)**

-   What is GitHub and why use it?
-   Creating a remote repository.
-   Connecting a local repository to a remote one (`git remote`, `git push`).

----------

### **2. Practical Part (50-55 minutes)**

#### **2.1. Setting Up the Environment (5 minutes)**

1.  Configure user name and email:
    
    ```bash
    git config --global user.name "Your Name"  
    git config --global user.email "Your Email"  
    ```
    
2.  Create a GitHub account (if not already done).

#### **2.2. Creating and Managing a Repository (30 minutes)**

1.  Create a local project:
    
    ```bash
    mkdir my-first-repo  
    cd my-first-repo  
    git init  
    ```
    
2.  Create a `README.md` file with the following content:
    
    ```
    # My First Repository  
    This is my first repository!  
    
    ```
    
3.  Stage and commit the file:
    
    ```bash
    git add README.md  
    git commit -m "Initial commit: add README.md"  
    ```
    
4.  Create a remote repository on GitHub.
5.  Connect the local repository to the remote one and push the changes:
    
    ```bash
    git remote add origin <URL_of_your_repository>  
    git branch -M main  
    git push -u origin main  
    ```
    

#### **2.3. Team Collaboration Practice (20 minutes)**

1.  One participant edits `README.md` (e.g., adds a new line), commits the changes, and pushes them.
2.  Another participant clones the repository:
    
    ```bash
    git clone <URL>  
    ```
    
3.  The second participant makes changes and sends them back (or creates a pull request).
4.  Demonstrate a basic conflict and how to resolve it.

----------

### **3. Q&A (10 minutes)**

----------
