# IP
Evolution of our product

//

Tema: FantasyGrounds
 
Recomandare: impartirea echipei in 2, o parte pentru diagrame, o parte pentru forward/reverse engineering.
 
Echipe de 6
 
diagrame C4 - 4 tipuri de diagrame pe care le avem in vedere 
 
Context (cum interactioneaza aplcatia cu utilizatorii / alte aplicatii)
Ex: o diagrama de context ar fi - app noastra interactioneaza cu server de email, sau cu fluxuri de stiri pentru a transmite stiri
Ex de diagrama de context este in curs 4 
 
Container - care sunt acele dispozitive (fizice sau virtuale) pe care trebuie sa le folosesc pentru a functiona aplicatia
Ex: Va trebui sa ne gandim care sunt dispozitivele pe care va rula aplicatia (Ex: server, calculatorul utilizatorului care 
trebuie sa instaleze chestii, PC pentru baza de date samd)
Atunci cand ne referim la un container, e o masina pe care ruleaza bucati ale noastre de cod.
 
Componente - in esenta imi spune care sunt elementele mari de care are nev aplicatia pt a functiona
Ex: modul pentru gestiune login, gestiune comunicarii sincrone, pt gestiunea aplicatiilor derivate
Care sunt aspectele majore de care are nev de aplicatia noastra pt a functiona (putem sa ne gandim la pachete)
 
 
Forward engineering:
putem folosi diagrame de clase pentru a genera cod (in mare)
Dintr-o diagrama de clase si din aceste clase sa generam cod in java
pe care apoi sa-l corectam in cazul in care avem nevoie, si sa-l compilam.
Rezultatul compilarii vor fi niste fisiere .class, si asta e task-ul 2.
Foarte important in Java.
 
Reverse engineering:
din fisierele class, cu diferite utilitare, va trebui sa decompilam codul in asa fel incat sa obtinem fisiere jva
pe care sa le importam intr-un editor UML si sa obtinem diagrame de clase automat.
 
Bonus: unelte pentru viata mai usoara (GitHub, Trello - de asignat task-uri fiecarui utilizator +- prioritati, marcat ca finalizat 
samd)
