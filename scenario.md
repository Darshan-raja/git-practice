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
