# university_hub

### Windows:
Download and install Git from https://git-scm.com/download/win
Install GitHub Desktop from https://desktop.github.com/ for a GUI interface
Use Git Bash or PowerShell for command-line operations
Configure Git with your name and email:
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### macOS:
Install Git via Homebrew: brew install git
Or download from https://git-scm.com/download/mac
GitHub Desktop is available for macOS as well
Use Terminal for command-line operations
Configure Git as mentioned in the Windows section

### Linux:
Install Git using your distribution's package manager:
Ubuntu/Debian: sudo apt-get install git
Fedora: ``` sudo dnf install git ```
Arch Linux: ``` sudo pacman -S git ```
Use the terminal for all Git operations
Configure Git as mentioned in the Windows section

### Common GitHub workflow for all OS:

Create a repository on GitHub
Clone the repository: git clone https://github.com/username/repo.git
Make changes to your files
Stage changes: git add .
Commit changes: ``` git commit -m "Your commit message" ```
Push to GitHub: ``` git push origin main ```

### Additional GitHub features:

Create and manage issues
Review and merge pull requests
Use GitHub Actions for CI/CD
Collaborate with others using forks and branches
Remember to regularly pull changes from the remote repository using git pull to keep your local copy up-to-date.