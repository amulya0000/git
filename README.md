Sure! Here are the Git interview questions along with their answers:

### Basic Questions

1. **What is a Git repository?**
   - A Git repository is a storage space where your project files and their revision history are stored. It can be local to a directory on your computer or a remote repository hosted on a server.

2. **What does the `git clone` command do?**
   - The `git clone` command creates a copy of an existing Git repository. It downloads the repository, including all files, branches, and commits, to your local machine.

3. **How do you initialize a new Git repository?**
   - You can initialize a new Git repository using the command `git init`. This command sets up the necessary files and directories for Git to start tracking changes in your project.

4. **What is the purpose of the `git config` command?**
   - The `git config` command is used to set configuration options for your Git installation. This includes setting your username, email, and other preferences like the default text editor.

5. **Explain the concept of branching in Git.**
   - Branching in Git allows you to create separate lines of development within a repository. Each branch can have its own commits and changes, enabling you to work on different features or fixes simultaneously without affecting the main codebase.

### Intermediate Questions

1. **What is a merge conflict, and how do you resolve it?**
   - A merge conflict occurs when Git cannot automatically merge changes from different branches due to conflicting changes in the same file. To resolve it, you need to manually edit the conflicting files to reconcile the differences and then commit the resolved changes.

2. **What does the `git stash` command do?**
   - The `git stash` command temporarily saves your uncommitted changes, allowing you to switch branches or perform other tasks without losing your work. You can later apply the stashed changes using `git stash apply`.

3. **How do you revert a commit that has already been pushed and made public?**
   - To revert a public commit, you can use the `git revert <commit>` command. This creates a new commit that undoes the changes made by the specified commit, preserving the history.

4. **What is the difference between `git pull` and `git fetch`?**
   - `git fetch` downloads updates from the remote repository but does not merge them into your local branch. `git pull` combines `git fetch` and `git merge`, fetching updates and then merging them into your current branch.

5. **Explain the difference between `git reset`, `git revert`, and `git checkout`.**
   - `git reset` moves the current branch to a specified commit and can modify the staging area and working directory.
   - `git revert` creates a new commit that undoes the changes of a specified commit.
   - `git checkout` switches branches or restores working directory files to a previous state.

### Advanced Questions

1. **What is a detached HEAD in Git, and how do you fix it?**
   - A detached HEAD occurs when you are not on a branch but directly on a commit. To fix it, you can create a new branch from the detached HEAD state using `git checkout -b <new-branch>`.

2. **How do you squash multiple commits into a single commit?**
   - You can squash commits using an interactive rebase. Run `git rebase -i <base-commit>`, mark the commits you want to squash with `s`, and then save and close the editor.

3. **What is the purpose of the `git rebase` command?**
   - The `git rebase` command is used to move or combine a sequence of commits to a new base commit. It helps in maintaining a clean and linear project history.

4. **How do you handle large binary files in a Git repository?**
   - Large binary files can be managed using Git Large File Storage (LFS). Git LFS replaces large files with text pointers inside Git, while storing the actual file content on a remote server.

5. **Explain the use of `git cherry-pick`.**
   - The `git cherry-pick` command allows you to apply changes from a specific commit to your current branch. This is useful for selectively integrating changes from different branches.

Feel free to ask if you need more details or examples for any of these questions!
