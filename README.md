GitHub Practical :- 1


# Configure Git (run once)
git config --global user.name "majidtamboli45"
git config --global user.email "majidtamboli45@gmail.com"

# Create project directory
mkdir P1
cd P1

# Initialize repository
git init

# Create initial files
echo "# First Practical Implementation" > README.md
touch .gitignore

# Add and commit files
git add .
git commit -m "Initial commit"

# Set branch name
git branch -M main

# Connect to GitHub (make sure repo is already created on GitHub)
git remote add origin https://github.com/majidtamboli45/P1.git

# Push to GitHub
git push -u origin main

# Create Python file
touch script.py

# Add, commit and push Python file
git add .
git commit -m "Added Python script file"
git push

# Verify remote
git remote -v
