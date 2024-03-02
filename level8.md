# level8
Level Goal
The password for the next level is stored in the file data.txt next to the word millionth

Commands you may need to solve this level
man, grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd
# Solution
```bash
strings filename | grep "millionth"
```
![image](https://github.com/LAVANYA-PIDIKITI/Overthewire.bandit/assets/98797256/2b3bef23-7191-47ab-8a5b-7df23b9b4561)
