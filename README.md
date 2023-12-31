# Uploading Blender Files to GitHub Repository


## Overview
This README provides step-by-step instructions on how to upload Blender files to a GitHub repository. GitHub is a popular platform for version control and collaboration, making it an excellent choice for sharing and managing Blender projects.

## Prerequisites
GitHub Account: Ensure that you have a GitHub account. If you don't have one, you can sign up at GitHub.

Git Installed: Make sure Git is installed on your local machine. You can download and install Git from here.

Blender Installed: Have Blender installed on your computer. You can download the latest version of Blender from Blender's official website.

Steps to Upload Blender Files to GitHub

### Step 1: Name your blender files as your student id

### Step 2: Initialize a Git Repository Locally
Open a terminal or command prompt.

Navigate to the directory containing your Blender file using the cd command.

```
cd path/to/your/blender/project
```

Initialize a new Git repository:
```
git init
```

### Step 3: Create a .gitignore file

Create a .gitignore file in your project directory to specify which files should be ignored by Git. This is important to exclude unnecessary files generated by Blender.

Example .gitignore:
```
# Blender
*.blend1
*.blend2
*.blend3
*.bak
*.bphys
```

Adjust the patterns based on your project's needs.

### Step 4: Add and Commit Files
Add your Blender file and the .gitignore file:

```
git add .
```

Commit the changes:
```
git commit -m "Initial commit"
```

### Step 5: Connect Local Repository to GitHub

In the terminal, add this GitHub repository as a remote:

```
git remote add origin https://github.com/RGUCompSoc/blender-wars-submissions.git
```

### Step 6: Push to GitHub
Push your local repository to GitHub:

```
git push -u origin master
```

### Step 7: Verify on GitHub
Visit your GitHub repository on the web to confirm that your Blender files are now uploaded.

Conclusion
Congratulations! You have successfully uploaded your Blender files to a GitHub repository. You can now collaborate with others, track changes, and manage versions using Git and GitHub. If you encounter any issues, refer to GitHub's documentation or seek help from the GitHub community.
