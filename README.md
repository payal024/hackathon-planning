# hackathon-planning

# How to clone github repo
  Cloning a repository syncs it to your local machine. After you clone, you can add and edit files and then push and pull updates. 
Steps
  1. Open GitHub and navigate to the main page of the repository.
  2. Under the repository name, click on Clone or download.
  3. Select the Clone with HTTPs section and copy the clone URL for the repository.
  4. Open Git Bash and change the current working directory to your desired location where you want to create the local copy of the repository.
  5. Use the git clone command with repository URL to make a copy of the remote repository. 
  


# How to push local repo to github repo
Steps
  1. Create a new repository on github and click on the plus sign.
  2. Open your Git Bash and create your local project in your desktop directed towards a current working directory.
  3.  Initialize the git repository using command  ' git init ' . It is used to create a new empty repository or directory consisting of files' with the hidden directory. '.git' is created at the top level of your project, which places all of the revision information in one place.
  4.   Add the file to the new local repository using the command  ' git add . ' . Also use the command ' git status '  to check for the all the files which are going to be staged.
  5.   Commit the files staged in your local repository by writing a commit message using the command '  git commit -m "message" ' . 
  6.   Copy your remote repository's URL from GitHub and add the URL copied, which is your remote repository to where your local content from your repository is pushed using command  ' git remote add origin 'your_url_name'   '  .
  7.   Push the code in your local repository to GitHub using the command  ' git push -u origin master '.
  8.   View your files in your repository hosted on GitHub.
  9.   Every time when any changes are made to any file in local repo, use the command git add . to add the new changes to staging directory and  use the command git commit -m for commiting the changes. Now to push the commited changes to the remote repo use the command ' git push '.



# How to pull changes 
Steps
  1. To pull the changes from source branch to your destination branch use the command git pull 'remote_name' 'branch_name'. Here the remote_name is the name of the source branch and the branch_name is destination branch where you want the changes to be merged.
