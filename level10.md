# level10
Level Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

Commands you may need to solve this level
grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd
# Solution
```bash
strings data.txt | grep "="
```
<br>

![image](https://github.com/LAVANYA-PIDIKITI/Overthewire.bandit/assets/98797256/d1dc676c-0784-42e1-8c3e-a68d521e4f92)
