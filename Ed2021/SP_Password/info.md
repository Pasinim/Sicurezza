- Per cercare i formati supportati da JtR uno per riga, solamente i formati MD5:
```sudo john --list=formats | tr , '\n'  | grep -i 'md5'```
- È necessario rimuovere lo spazio nell'ultima riga di **crackme.txt** (steve) altrimenti l'hash non viene riconosciuto da JtR.
- Per inviare una soluzione devono essere inserite le vocali secondo l'alfabeto leet e gli underscore tra una parola e l'altra nel caso ci siano più parole. Alle volte bisogna convertire tutto in minuscole o tutto in maiuscole dentro le { }, ma SPFLG sempre maiuscolo 
- Per **me, myself and I** ho utilizzato [questo sito](hashes.com), che ha eseguito il decrypt e trovato come password >!whoami. *Quale e' il formato e come mai John non riesce a trovarlo*?
- Per safe4sure e' necessario utilizzare zip2john e successivamente utilizzare john sull'hash. La password per estrarre main e' <details> 
  <summary>Q1: What is the best Language in the World? </summary>
   A1: JavaScript 
</details>


