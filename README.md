1.) $ mvn archetype:generate

version: 1.4 groudId: com.adriano artifactId: BankingMicroservice

$ cat /home/ubuntu/BankingMicroservice/src/main/java/com/adriano/App.java

2.) $ cat /home/ubuntu/src/test/java/com/adriano/AppTest.java

3.)

4.) https://github.com/lovi02/CapstoneMicroservice

5.) $ git branch dev1 $ git branch dev2 $ git branch

$ git checkout dev1 $ echo "dev1 has added a file" >> dev1.txt $ git add dev1.txt $ git commit -m "dev1 first commit" $ git push -u origin dev1

$ git checkout dev2 $ echo "dev2 has added a file" >> dev2.txt $ git add dev2.txt $ git commit -m "dev2 first commit" $ git push -u origin dev2

$ git checkout main $ git merge dev1 $ git merge dev2 $ git push -u origin master

6.) no action needed

7.) $ echo "BankingMicroservice" >> README.md $ git add README.md $ git commit -m "first commit" $ git push -u origin main

$ git add . $ git status $ git commit -m "second commit" $ git push -u origin main

8.) https://github.com/lovi02/CapstoneMicroservice/blob/main/README.md

$ vi README.md $ git status $ git add README.md $ git commit -m "documentation" $ git push -u origin main
