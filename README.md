# Proiect_X&0_AI

Enunțul proiectului:
-
Joc X&0 cu reguli modificate. Jocul se desfășoară pe un grid NxM cu 10>=N  și M>=5( utilizator este întrebat ce dimenisiuni va avea tabla ).

Mutările posibile sunt de 2 tipuri:

- punerea unui simbol într-un loc gol. Mutarea este permisă dacă în jurul locului gol( pe pozițiile vecine pe linie si coloana, dar nu pe diagonala ) nu avem mai multe simboluri ale jucatorului opus, decât ale jucatorului care vrea sa mute.

- deplasarea unui simbol existent într-un spațiu gol. Acesta este permisa oricând este rândul jucătorului și se face cu o pozitie ( pe linie, coloana, diagonala ) indiferent dacă in jurul locului în care se muta, sunt mai multe simboluri ale jucătorului opus.

Scopul jocului este să se creeze o configurație de 4 simboluri pe poziții vecine pe linie, coloana sau diagonală. Jucătorul care a creat o astfel de configurație, a câștigat, ca în imaginea de mai jos:

![Screenshot 2023-02-27 134902](https://user-images.githubusercontent.com/82332641/221561521-94be33a9-eb34-4389-bf29-6724acae5750.png)


Observații:
-

- Pentru a muta într-o căsuță goala se face click stânga( căsuța se va colora cu verde daca mutarea este valabilă, în caz contrar veti primi un mesaj de "mutare imposibila" )
- Pentru a muta o piesă deja existentă pe tablă, se selectează piesa pe care vrem sa o mutăm cu click dreapta ( după ce selectam piesa, se vor colora cu galben căsuțele valabile unde putem muta piesa ), iar cu scroll click o plasăm în căsuța dorită.
- Nu funcționează la o adâncime mai mare de 2( nu este optimizat )
- Colorarea configurației câștigătoare nu funcționează corespunzător
