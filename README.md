2. Configuration

Before using Git, configure your identity and preferences.

bash
# Set your name and email (used in every commit)
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Enable colored output
git config --global color.ui auto

# View all configuration settings
git config --list
# Set default branch name for new repos
git config --global init.defaultBranch main

# Set default editor
git config --global core.editor "code --wait"
