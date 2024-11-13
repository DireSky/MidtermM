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

Task 4️⃣: Create a new branch called “dev-feature” from the branch "main" and add at least one commit.

Task 5️⃣: Resolve merge conflicts that will occur when merging “feature” back into “one”, and add a screenshot of the conflict resolution.

Task 6️⃣: Delete branches “two” and “three” after merging them with the main branch. Make a screenshot of the result.

Task 7️⃣: Describe what tasks were completed, what screenshots correspond to them in the file readme.md and in general, the instructions for checking your work.


Задание 1️⃣: Создать новую ветку Student_name и добавить 3 коммита.
Создать ветку Student_name:
bash
git checkout -b Student_name
Добавить 3 коммита, изменив файлы или создав новые. Используйте:
bash
git add <file>
git commit -m "Коммит 1"
git commit -m "Коммит 2"
git commit -m "Коммит 3"


Задание 2️⃣: Объединить ветку two с веткой three и сделать ребейз three на one.
Перейти на ветку three:
bash
git checkout three
Объединить ветку two:
bash
git merge two
Затем сделать ребейз:
bash
git rebase one

Задание 3️⃣: Ответить на вопросы о коммитах.
Я ответил на все вопросы и закоммитил в другом месте до этого



Задание 4️⃣: Создать новую ветку dev-feature от ветки main и добавить хотя бы один коммит.
Перейти на ветку main:
bash
git checkout main
Создать ветку dev-feature:
bash
git checkout -b dev-feature
Добавить коммит:
bash
git add <file>
git commit -m "Коммит в dev-feature"

Задание 5️⃣: Решить конфликты при слиянии feature обратно в one и сделать скриншот решения конфликта.
Перейти на ветку one:
bash
git checkout one
Объединить ветку feature:
bash
git merge feature
Если возникли конфликты, решить их и сделать скриншот.


Задание 6️⃣: Удалить ветки two и three после их слияния с основной веткой.
Перейти на основную ветку one:
bash
git checkout one
Удалить ветки two и three:
bash
git branch -d two
git branch -d three
Сделать скриншот результата, используя команду:
bash
git branch


Task 8️⃣: Make a pull request, write first name, last name and group in the request title.
 



