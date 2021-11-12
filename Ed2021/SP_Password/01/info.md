- Per cercare i formati supportati da JtR uno per riga, solamente i formati MD5:
```sudo john --list=formats | tr , '\n'  | grep -i 'md5'```
- Il prof ha messo uno spazio nell'ultima riga (di steve), quindi se lo spazio non viene rimosso l' hash non viene riconosciuto correttamente
 
