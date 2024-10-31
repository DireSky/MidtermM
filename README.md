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
What is the difference between switch and checkout?
git switch и git checkout могут оба использоваться для переключения между ветками, но их назначение различается:

git switch был добавлен в более поздних версиях Git, чтобы упростить переключение между ветками и сделать команды Git более интуитивными. Он предназначен исключительно для переключения между ветками.

git checkout — более универсальная команда, которая не только переключает ветки, но также позволяет восстанавливать файлы или переключаться на конкретные коммиты. Однако она может быть более сложной, поскольку поддерживает множество функций.

What does git merge do?
git merge объединяет изменения из одной ветки в другую. Она берёт последние коммиты из целевой ветки (которую вы хотите слить) и интегрирует их в текущую ветку, создавая новый коммит слияния, если нет конфликтов. Если конфликты есть, Git попросит вас их разрешить перед завершением слияния.

What happens to the commit history after rebase and why?

После выполнения git rebase история коммитов переписывается. Rebase переносит коммиты из текущей ветки на другую базовую ветку и делает её линейной, перемещая каждый коммит на новую базу. Это изменяет хеши коммитов, так как они становятся "новыми" коммитами. Rebase полезен для поддержания линейной истории, упрощая её чтение, но его стоит использовать осторожно, особенно если коммиты уже были опубликованы в удалённом репозитории.

How to understand which branch is remote and which is local in the terminal?

Команду git branch для просмотра локальных веток. Она покажет только локальные ветки без префикса.
Команду git branch -r для отображения только удалённых веток. Удалённые ветки будут показаны с префиксом origin/ (или другим именем удалённого репозитория).
Команду git branch -a для отображения всех веток (локальных и удалённых).

Task 5️⃣: Create a new branch called “dev-feature” from the branch "main" and add at least one commit.

Task 6️⃣: Delete branches “two” and “three” after merging them with the main branch. Make a screenshot of the result.

Task 7️⃣: Resolve merge conflicts that will occur when merging “feature” back into “one”, and add a screenshot of the conflict resolution.

Task 8️⃣: Rename branches "two" and "three" to "backup-two" and "backup-three," respectively, and take a screenshot showing the renamed branches.

Task 9️⃣: Document the execution of each task in a README file and attach all screenshots and files.

Task 🔟: Create a pull request to merge the “feature” branch with the “main” branch and add a description of the changes. Take a screenshot of the created pull request.


