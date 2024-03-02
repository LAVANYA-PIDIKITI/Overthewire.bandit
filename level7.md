# level7
Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size
Commands you may need to solve this level
ls , cd , cat , file , du , find , grep
# Solution
```bash
find / -user bandit7 -group bandit6 -size 33c
```
and we can see that <br>
![image](https://github.com/LAVANYA-PIDIKITI/Overthewire.bandit/assets/98797256/bb5c2b47-afb9-41de-b35d-89f58da6d118)<br>
![image](https://github.com/LAVANYA-PIDIKITI/Overthewire.bandit/assets/98797256/3bcefaf6-76e2-4702-b1cb-b7ae74b1be7e)

