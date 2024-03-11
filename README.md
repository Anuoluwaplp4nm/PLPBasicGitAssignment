# DOCUMENTATION OF PROCEDURE AND GIT COMMANDS USED.
## I have a GitHub account created already and also the neccesary tools(Git and VsCode installed on my local machine).

## Task 1: Repository Setup
  1. GitHub Repository Creation:
    -I Logged into my GitHub account and created a new repository called it "PLPBasicGitAssignment".
    -I Initialized it with a README file.

## Task 2: Local Setup
  1. Local Folder Setup:
    - I Create a new folder on your local machine called "PLPBasicGitAssignment".
    - Using VsCode to navigate to the created folder.

  2. Git Initialization:
  - Inside the folder I Initialized the new empty Git repository using the git command;
   ## git init.

  3. Connecting to GitHub:
  - I Linked the local repository to the GitHub repository using the following commands.
    ## git remote add origin https://github.com/Anuoluwaplp4nm/PLPBasicGitAssignment.git

## Task 3: Making Changes
  1. Created a File:
    - Via the VsCode, Inside your local folder, I created a new text file called "hello.txt".
    - I Added a simple text message  "Hello, Git!."
     
  2. Committing Changes:
    - After saving the file, it was Stagged and committed using the following command respectively;
      ## git add hello.txt (adding to the index).
      ## git commit -m "Add hello.txt with a greeting"  (Commit the changes.)

## Task 4: Pushing to GitHub
  1. Pushing to GitHub:
    - Push the committed changes to your GitHub repository.
      ## git push -u origin main

## Task 5: Verifying uploded file to GitHub.
  1. Verify on GitHub:
    - Visited GitHub repository to confirm that the `hello.txt` file and committed message are visible.
