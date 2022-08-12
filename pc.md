## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a software made to help keep track of any code history and changes made and allows you to manage this as well. Git is maintained on the local copy, its a version control system.

2. What is the difference between Git and GitHub?
While Git helps to manage any history in code and is kept in the branch, GitHub is made to be a hosting system/service where you are able to share, edit, and merge different revisions or copies of a code with others, as GitHub as also cloud-based.


3. Why do we create a branch?
We create branches in order to be able to make changes, manipulations and edits to the main copy without placing any permenant or changes onto that copy, meaning that any added changes made in a branch would remain in that branch only, not touching anything on the main branch which can be useful when you want to make changes of your own without impacting the original copy. 

4. What is the purpose of a Pull Request?
The purpose of a pull request is in order for others to be able to see the changes you have made to the project by merging these new changes into the main branch for everyone to see.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
In order to switch between branches you can either use git checkout or git switch followed by the branch you wish to switch over to, for an example if you wanted to switch back to the main branch you would use the command git switch main.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The differences between git fetch, merge and pull is what each command does. In git fetch, this command 'fetches' and downloads content such as objects from a remote repo. In git merge, this command allows you to bring any new changes and merge it into the main branch to apply the new changes made. Lastly, git pull is a command that allows you to gather the content from the remote repo and upload it to update the local repo.

7. What is a merge conflict?
A merge conflict is when there are mutliple copies of code from different branches with changes made to each, followed by a merge conflict when being merged due to the error of two files containing the same code, making git unable to determine which change to push as there are two or more files with the same code. 

8. How do you resolve a merge conflict?
When it comes to resolving a merge conflict, the best way to go about this is by going directly to the file where the error is coming from and applying the changes needed to then add and commit with the new changes. 