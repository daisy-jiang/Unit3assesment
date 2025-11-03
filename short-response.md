1) If you are collaborating with a classmate what is the first thing that each of the team members need to do? Why is it important to do this step?

Answer: Each team member must be in the same repo. This is so that everyones work will be connected into one thing and not multiple seperate parts.

2) Why do developers use branches?

Answer: So they won't disrupt the work flow of other members and accidentally cause changes to their parts

3) What is git? What is github? How does git and github work together?

Answer: Git is a command line tool that manages code while github is a cloud based service that allows developers to store, track, manage, and control changes to their code. They work together as github is the location where you can access git

4) What is wrong with the following command sequence? What should be the correct command sequence?

git commit-m "saving work"
git add .
git push

Answer: The order of the sequence is wrong and the location of git commit -m and git add . should be swapped. Also, there is supposed to be a space in between "commit" and "-". The correct command sequence is 

git add .
git commit -m "saving work"
git push