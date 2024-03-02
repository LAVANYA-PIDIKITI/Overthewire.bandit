# level6
Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable
Commands you may need to solve this level
ls , cd , cat , file , du , find
# Solution
```bash
find . -readable -size 1033c -not -executable
```
![image](https://github.com/LAVANYA-PIDIKITI/Overthewire.bandit/assets/98797256/cd289c48-71f6-4efa-8b82-644e5f2b6cd2)
