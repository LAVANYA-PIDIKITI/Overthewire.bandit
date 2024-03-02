# level11
Level Goal
The password for the next level is stored in the file data.txt, which contains base64 encoded data

Commands you may need to solve this level
grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

Helpful Reading Material
Base64 on Wikipedia
# Solution
```bash
echo contents_of_data.txt | base64 -d
```
![image](https://github.com/LAVANYA-PIDIKITI/Overthewire.bandit/assets/98797256/c55c974c-5621-418b-a882-559db77fb6f9)

