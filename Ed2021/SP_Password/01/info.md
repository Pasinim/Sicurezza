- Per cercare i formati supportati da JtR uno per riga, solamente i formati MD5:
```sudo john --list=formats | tr , '\n'  | grep -i 'md5'```
- È necessario rimuovere lo spazio nell'ultima riga di **crackme.txt** (steve) altrimenti l'hash non viene riconosciuto da JtR. Non sono in grado però di recuperare la psw
 
