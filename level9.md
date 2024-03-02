# level9
Level Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

Commands you may need to solve this level
grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

Helpful Reading Material
Piping and Redirection
# Solution
Use the command
```bash
sort data.txt | uniq -u
```
<br>

![image](https://github.com/LAVANYA-PIDIKITI/Overthewire.bandit/assets/98797256/b38e52a2-5bf4-4c59-8a23-748cc385d5aa)


