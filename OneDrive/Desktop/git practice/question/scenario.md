# Scenario 1 Undo Unstaged Changes

● You modified a file main.py but have not staged it yet.
● After reviewing the changes, you realize they are incorrect and want to discard them completely.
● Questions:
●  How will you undo the changes?
●  Which command restores the file to the last committed state?

--> answers
● git checkout -- main.py
● git reset main.py