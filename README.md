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

Task 2️⃣: Merge branch two to branch three and rebase three to one. Show the process in screenshots

Task 3️⃣: Answer the questions in commit questions

What is the difference between switch and checkout?
git checkout — это универсальная команда, которая используется как для переключения между ветками, так и для работы с файлами (например, чтобы отменить изменения в файле или восстановить его до определённого коммита). Ранее она была основной для переключения между ветками, но её функциональность может быть сложной для начинающих.
git switch — более новая команда, предназначенная исключительно для переключения между ветками. Она была введена, чтобы сделать процесс переключения проще и понятнее. В отличие от checkout, команда switch не работает с файлами, а предназначена только для работы с ветками.

What does git merge do?
git merge объединяет изменения из одной ветки в другую. Эта команда берёт изменения, внесённые в исходной ветке, и пытается интегрировать их в текущую ветку. Если файлы не конфликтуют, слияние произойдёт автоматически, но если изменения касаются одних и тех же строк, может возникнуть конфликт, который нужно будет разрешить вручную.

What happens to the commit history after rebase and why?

После rebase история коммитов изменяется. В отличие от merge, который добавляет новый коммит слияния, rebase перемещает коммиты одной ветки поверх другой, создавая «линейную» историю. Это делает историю чище, так как не создаются дополнительные коммиты слияния, но при этом старые коммиты переписываются.
Таким образом, rebase изменяет хэши коммитов, из-за чего создаётся новая история. Этот способ слияния особенно удобен для работы в локальных ветках, но может создать проблемы, если коммиты уже отправлены в удалённый репозиторий, так как он меняет историю.

How to understand which branch is remote and which is local in the terminal?
В терминале локальные ветки обычно отображаются просто по имени, например, main, feature, bugfix, и находятся только на вашей локальной машине.
Удалённые ветки обычно видны в формате origin/имя_ветки. origin — это имя удалённого репозитория по умолчанию. Удалённые ветки представляют собой их состояние на сервере.

Task 4️⃣: Create a new branch called “dev-feature” from the branch "main" and add at least one commit.


Task 5️⃣: Resolve merge conflicts that will occur when merging “feature” back into “one”, and add a screenshot of the conflict resolution.

Task 6️⃣: Delete branches “two” and “three” after merging them with the main branch. Make a screenshot of the result.

Task 7️⃣: Describe what tasks were completed, what screenshots correspond to them in the file readme.md and in general, the instructions for checking your work.

Создал ветку Student_name. Сделал merge two to three и сделал скриншот. Ответил на вопросы и добавил коммит. Создал ветку dev_feature и добавил 1 коммит. Обьединил ветку dev_feature for one и сделал скришот. Удалил two and three комит потом замерчил и сделал скришот. И описал что я сделал

Task 8️⃣: Make a pull request, write first name, last name and group in the request title.
 



