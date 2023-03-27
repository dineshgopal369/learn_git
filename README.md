# Git Learning Notes

This repository contains my notes on Git, including some basic commands and tips that I have found useful. Here are some commands to get started:

1. `git config --global user.name "<your name>"` - Sets your name globally for all repositories.
2. `git config --global user.email "<your email>"` - Sets your email globally for all repositories.
3. `git config --global --edit` - Opens the global Git configuration file where you can edit your username and email.

To add changes to the staging area:

4. `git add <file_name>` - Adds a specific file to the staging area.
5. `git commit -m "<commit message>"` - Commits changes to the repository with a commit message.

To create and switch to different branches:

6. `git branch` - Lists all the branches, including the default branch "master".
7. `git branch <branch_name>` - Creates a new branch with the given name.
8. `git checkout <branch_name>` - Switches to the specified branch.

To merge two branches:

9. `git checkout <target_branch>` - Switches to the target branch.
10. `git merge <source_branch>` - Merges the source branch into the target branch.

To push changes to the remote repository:

11. `git checkout main` - Switches to the main branch.
12. `git push` - Pushes the changes to the remote repository.

To ignore files from being tracked by Git:

13. Create a`.gitignore` file and add the files or directories you want to ignore.

Credits: [Anju Bhaiay](https://www.youtube.com/watch?v=uaeKhfhYE0U)

I have also included some screenshots to illustrate some of the commands.

#### Images

<p align="left">
<img src=assets/20230327_135323_ksnip_20230327-002622.png alt="your image" />
</p>

<p align="left">
<img src=assets/20230327_135632_ksnip_20230327-002905.png alt="your image" />
</p>
