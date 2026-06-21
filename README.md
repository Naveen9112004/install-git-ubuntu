# Git Installation Guide for Ubuntu

A step-by-step guide to installing, configuring, and linking Git and GitHub on an Ubuntu system.


# Step 1: Install Git

Run the following command to download and install Git:

**Bash : sudo apt install git -y**

# Step 2: Verify Installation

Check if Git is successfully installed by checking its version:

**Bash : git --version**

# 👤 Step 3: Configure Your Git Identity

Git requires a username and email to track who makes changes to the code. Set your global configurations below (replace with your details):

**Bash**
**git config --global user.name "Your Name"**

**git config --global user.email "your-email@example.com"**

# Step 4: Set the Default Branch

Set the default initial branch name to main to ensure compatibility with GitHub:

**Bash : git config --global init.defaultBranch main**

# 🚀 Step 5: Link Your GitHub Account (GitHub CLI)

The easiest way to authorize your Ubuntu terminal with GitHub is by using the official GitHub CLI tool.

1. Install the GitHub CLI:

  **Bash : sudo apt install gh -y**
  
 2. Run the login wizard:
    
   **Bash : gh auth login**


# Follow the interactive prompts:

 1. Select **GitHub.com**
 2. Choose **HTTP**
 3. Authenticate Git with your GitHub credentials? **Yes**
 4. Choose Login with a web browser
 5. Copy the **8-digit code displayed** in the terminal.
 6. Press Enter to **open the browser**, paste the code, and click Authorize.

 # Verify the connection:
  
  **Bash : gh auth status**


  # Thank You
