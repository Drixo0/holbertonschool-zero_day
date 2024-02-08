Me first readme

# Pull changes from the main branch to update the local repository
git pull origin main

# Create the up_to_date file and write the git command used
echo "git pull origin main" > up_to_date

# Add the up_to_date file to git
git add up_to_date

# Commit changes with the specified message
git commit -m "How to be up to date in git"

# Push changes to the origin
git push origin main
