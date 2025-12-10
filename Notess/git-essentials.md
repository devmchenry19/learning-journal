# Branching in git
# Create a dev Branch #git checkout -b dev
# 

# make a change and commit # example edith file and commit
# git add README.md
# git commit -m "Describe the change you made on dev"

# push branch to github 
# git push -u origin dev

# Open a Pull Request (two options):

# Web UI (recommended for beginners):
# Go to https://github.com/<your-username>/learning-journal
# You should see a prompt to compare & create a pull request for dev — click "Compare & pull request".
# Fill in a clear title and description of the change, then click Create pull request.
# Review the changes and click Merge pull request (choose "Create a merge commit" or "Squash and merge" as you prefer), then confirm.
# Optionally click Delete branch after merging.

# github CLI 
# gh pr create --base main --head dev --title "Short title" --body "More details"
# sgh pr merge --merge  # or --squash, --rebase depending on preference