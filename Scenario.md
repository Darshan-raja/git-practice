# Scenario 1 Undo Unstaged Changes

● You modified a file main.py but have not staged it yet.
● After reviewing the changes, you realize they are incorrect and want to discard them completely.
● Questions:
●  How will you undo the changes?
●  Which command restores the file to the last committed state?

--> commands
● git checkout main.py # it used to undo the changes it should used before git push main.py
● git restore main.py

# Scenario 2 Undo Unstaged Changes
Scenario 2: Undo Staged Changes
You edited index.html and staged it using git add.
Before committing, you realize the changes should not be part of the next commit.
Questions:
• How do you unstage the file without losing the changes?
• Which Git command helps here?

commands :
git restore --staged index.html
git reset index.html

## Scenario 3: Modify Last Commit Message
You committed changes but made a mistake in the commit message.
The commit is not yet pushed to the remote repository.
Questions:
• How will you correct the commit message?
• Will this create a new commit? Explain.

commands:
git commit --amend -m "new commit message"

## git Scenario 4: Add Missed File to Last Commit

You committed your changes but forgot to include config.yaml.
The commit has not been pushed yet.
Questions:
• How will you add the missed file to te previous commit?
• Which command helps avoid creating a new commit
commnads :
git add filename
git commit --amend "--no-edit"

## Scenario 5: Undo Last Commit (Keep Changes)
You made a commit, but after testing, you realize the logic needs improvement.
You want to undo the commit but keep the code changes for further editing.
Questions:
• Which reset mode will you use?
• What happens to the working directory?

commndas:
