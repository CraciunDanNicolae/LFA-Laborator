dfa.py este un program python care creeaza un dfa pentru jocul cu incaperile prezentat la laborator. Acesta citeste din fisierul dfa.txt datele despre joc si le stocheaza intr-un dicitonar. Apoi citeste din fisierul test.txt o serie de comenzi si afiseaza pe ecran in ce incapere se afla jucatorul dupa fiecare comanda, iar la final afiseaza 1 daca se afla intr-un final state si 0 in caz contrar.



turing_machine: Această mașină Turing determină dacă un șir de caractere este un palindrom — adică dacă se citește la fel de la stânga la dreapta și de la dreapta la stânga. Compararea este sensibilă la majuscule/minuscule ('a' ≠ 'A'), și funcționează pentru orice fel de caracter (litere, cifre, simboluri). Inputul este o bandă cu caractere urmate de un simbol de final _. Mașina parcurge banda, marcând primul și ultimul caracter necitit cu X, apoi le compară. Dacă sunt identice, continuă, iar dacă sunt diferite, se oprește și respinge șirul.
START: caută primul caracter nemarcat și îl salvează.
MOVE_RIGHT: avansează până la capătul șirului pentru a găsi caracterul de la dreapta.
CHECK_MATCH: compară caracterul salvat cu ultimul caracter nemarcat.
MOVE_LEFT: se întoarce spre începutul benzii pentru a relua procesul.
Mașina se oprește cu accept (True) dacă toate caracterele au fost potrivite și marcate.




nfa:Acest program citește definiția unui NFA dintr-un fișier text nfa.txt și o listă de șiruri de test dintr-un alt fișier inputuri.txt. Apoi, simulează funcționarea NFA-ului pentru fiecare șir și afișează dacă acesta este acceptat sau respins. Conditia ca un sir sa fie acceptat este sa aiba un numar impar de 1.
