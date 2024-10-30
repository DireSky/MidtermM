Exam on Introduction to engineering and computer science
Make a fork of this repository on your GitHab. Read the tasks carefully and complete them according to the instructions.
✔️ All tasks must be done on the git and uploaded to the GitHub.

✔️ Send me a link to your GitHub repository with completed tasks as a pull request.

✔️ In the next message after the link send me information about who you are: name, surname and group.

⚠️ Your push operation may not work. If so you can use FORCE PUSH. How to do force push you can find in internet, or use https url.

⚠️ The end of the exam is at 14:10.

❌ I will not accept links that are sent later than end of the exam

❌ I will not accept a links if you send me your GitHub instead of a repository with answers.

❌ I will not accept links unless you post information about who you are.

Tasks:
Task 1️⃣: Create new branch Student_name and add 3 commits.

Task 2️⃣: Recreate the graph as in the picture. Leave a link to the repository in the text file "task 2".

Task 3️⃣: Merge branch two to branch three and rebase three to one. Show the process in screenshots

Task 4️⃣: Answer the questions in commit questions

Task 5️⃣: Create a new branch called “dev-feature” from the branch "main" and add at least one commit.

Task 6️⃣: Delete branches “two” and “three” after merging them with the main branch. Make a screenshot of the result.
![alt text](Снимок-1.PNG)
Task 7️⃣: Resolve merge conflicts that will occur when merging “feature” back into “one”, and add a screenshot of the conflict resolution.
[text](<../../Новая папка>)
Task 8️⃣: Rename branches "two" and "three" to "backup-two" and "backup-three," respectively, and take a screenshot showing the renamed branches.
![alt text](Снимок.PNG)
Task 9️⃣: Document the execution of each task in a README file and attach all screenshots and files.

Task 🔟: Create a pull request to merge the “feature” branch with the “main” branch and add a description of the changes. Take a screenshot of the created pull request.


Task 4️⃣: Answer the question in commit question.


Difference between switch and checkout
git checkout: Used for switching branches and restoring files. Versatile but can be confusing.
git switch: Specifically for switching branches, introduced for clarity.
2. What does git merge do?
git merge: Combines changes from one branch into another, creating a merge commit if branches have diverged. Conflicts must be resolved manually if they exist.
3. What happens to the commit history after rebase?
Rebase: Moves a branch to a new base, rewriting commit history to create new commits. Results in a linear history, but alters commit hashes, so use cautiously on shared branches.
4. How to identify local vs. remote branches?
Local branches: List with git branch.
Remote branches: List with git branch -r.
Both: List with git branch -a. Remote branches typically start with origin/.
