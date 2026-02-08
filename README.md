# repo_B
test shared code

For beginning to work with shared folder do commands in terminal:
# add alias for remote repo to shared variable
git remote add shared git@github.com:irdy/shared.git
# add subtree to project (shared folder will be created)
git subtree add --prefix shared shared main --squash
