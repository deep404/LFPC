# LFPC
###### Code-ul pentru laboratorul Nr.1 am fost scris in python. Tot programul a fost impartit in mai multe blocuri, dupa semnificatie si rol. De asemenea, code-ul este scris, astfel incat cu acesta rezolva toate variantele din lucrare de laborator, nu daor a mea personala, varianta Nr.20.
###### In blocul Nr.1 se importeaza librariile necesare pentru ilustrarea grafului din ultimul bloc.
###### In blocul Nr.2 afiseaza legenda pentru gramatica care va fi utilizata pe parcursul programului.
###### In blocul Nr.3 se afla si se salveaza simbolurile terminale, marcate cu litere mici a alfabetului englez
###### In blocul Nr.4 se afla si se salveaza simbolurile neterminale, marcate cu litere mari a alfabetului englez
###### In blocul Nr.5 se afla si se salveaza care simbol este de start
###### In blocul Nr.6 se afla si se salveaza reguile gramaticii, la moment ele sunt salvate intr-o lista de string-uri, astfel cum sunt specificate de utilizator, fara modificari
###### In blocul Nr.7 se afiseaza gramatica totala a limbajului specificat de utilizator prin intermediul la code-ul din blocurile 2 - 6. Acest bloc duce in caracter informativ
###### In blocul Nr.8 se citeste string-ul care va fi controlat daca face parte din gramatica de mai sus
###### In blocul Nr.9 se contruieste Finite Automaton prin intermediul structuri de date din python. Pentru reprezentarea s-a utilizat dictionar, lista si tuple. Cheia este numarul de ordine a simbolului neterminal in alfabet, de exemplu pentru A -> 1. Pentru fiecare cheie ii convine tuple de perechi. Fiecare pereche reprezinta o muchie din graf. Primul e simbolul terminal, al doilea e simbolul neterminal, daca acesta nu exista, atunci e inlocuit de '$'. Dupa procesare se ilustreaza acest dictionar.
###### In blocul Nr.10 se controleaza daca string-ul specficiat in blocul Nr.8 apartine gramaticii. Se contruiesc string-urile prin intermediul la FA, pana nu se obtine varianta dorita, altfel acesta nu apartine limbajului.
###### In blocul Nr.11 se ilusteaza FA prin intermediul la un graf orientat poderat. Nodurile sunt simbolurile neterminale, ponderea o constituie simbolurile terminale. Simbolul de start si sfarsitul '$' sunt ilustrate prin culori diferite fata de celelalte noduri.

