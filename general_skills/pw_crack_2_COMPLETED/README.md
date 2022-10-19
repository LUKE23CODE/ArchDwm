# PW Crack 2
---

## Exercise

Can you crack the password to get the flag?
Download the password checker here and you'll need the encrypted flag in the same directory too.

when i opened the python file with my editor there was chr(0x64) + chr(0x65) + chr(0x37) + chr(0x36) to decrypt the passwd -> de76

then i ran the python file and enter the passwd and that's when i got the flag...

## Output

```bash
python level2.py
Please enter correct password for flag: de76
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_489dea9a}
```