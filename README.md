dfa.py este un program python care creeaza un dfa pentru jocul cu incaperile prezentat la laborator. Acesta citeste din fisierul dfa.txt datele despre joc si le stocheaza intr-un dicitonar. Apoi citeste din fisierul test.txt o serie de comenzi si afiseaza pe ecran in ce incapere se afla jucatorul dupa fiecare comanda, iar la final afiseaza 1 daca se afla intr-un final state si 0 in caz contrar.



turing_machine: Această mașină Turing determină dacă un șir de caractere este un palindrom — adică dacă se citește la fel de la stânga la dreapta și de la dreapta la stânga. Compararea este sensibilă la majuscule/minuscule ('a' ≠ 'A'), și funcționează pentru orice fel de caracter (litere, cifre, simboluri). Inputul este o bandă cu caractere urmate de un simbol de final _. Mașina parcurge banda, marcând primul și ultimul caracter necitit cu X, apoi le compară. Dacă sunt identice, continuă, iar dacă sunt diferite, se oprește și respinge șirul.
