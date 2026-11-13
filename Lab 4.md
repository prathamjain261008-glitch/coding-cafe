# Lab 4 Answers

### Question 1
`--global` saves identity settings across all Git repositories on your machine. Leaving it out configures identity for the current repository only.

### Question 2
The `.git` directory appeared. It contains internal configuration files, object stores, and logs that track repository history.

### Question 3
It offers to track all project files, including thousands in `.venv/`. Yes, contents of `.venv/` and `__pycache__/` are auto-generated dependencies, not human-written code.

### Question 4
All entries under `.venv/` and `__pycache__/` disappeared from the untracked files section.

### Question 5
It should be committed. Saving `.gitignore` ensures collaborators and TAs ignore the exact same unnecessary files.

### Question 6
It moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved from the working directory into the staging area.

### Question 7
Git printed the commit short hash, branch, message, and statistics showing 1 file changed with insertions.

### Question 8
They are called the short commit hash, serving as a unique identifier for that specific commit.

### Question 9
The four steps are: edit files, check status (`git status`), stage changes (`git add`), and commit (`git commit`).

### Question 10
`README.md` serves as the primary landing page for a repository, which GitHub automatically renders on the main project overview.

### Question 11
It generated and stored an OAuth authentication token locally, allowing Git to push without requesting a password.

### Question 12
`README.md` is displayed because GitHub automatically renders it on the front page as the project description.

### Question 13
No, pushing only copied the local history to GitHub without altering local commits or hashes.

### Question 14
A private repository exists securely on GitHub with controlled access for authorized users. A non-existent repository has no cloud backup or remote presence anywhere.