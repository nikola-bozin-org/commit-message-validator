# Getting Started
To use this script just create a commit-msg file in your .git/hooks directory and copy the script content into it.          

# Create the commit-msg Hook:           
 - Navigate to the .git/hooks directory in your Git repository.         
 - `cd [path-to-your-git-repository]/.git/hooks/`           

# Create and Edit the commit-msg File:              
- Create a new file named commit-msg in this directory and open it with a text editor.              
`touch commit-msg`          
`nano commit-msg`           

# Copy the Script Content:          
- Open the commit-msg script from this repository copy its content, and paste it into your newly created commit-msg file.           

# Make the Script Executable:               
- Change the permissions of the commit-msg file to make it executable.          
`chmod +x commit-msg`               

# Usage                 
Once installed, the commit-msg hook will automatically check the format of your commit messages each time you commit. If the commit message does not start with "fix: ", "docs: ", "chore: " or "feat: ", the commit will be aborted, and an error message will be displayed, guiding you to use the correct format.

# Customization         
Feel free to modify the script to include different or additional prefixes as per your project's requirements. Edit the VALID_PREFIXES array in the commit-msg script to make your changes.         

