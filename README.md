# productionOrder
application calculate components for production plan
(przyklad "z zycia" - producja kabli)

sa 3 producty w pliku baseProducts

produkcja w dwie zmiany

produkcja sklada zamówienie: typ produktu "FG" + ilosc dla produkcji (naprzyklad: 1714386-1 150 sztuk, 1714458-1 200 sztuk)

zamowienie skladaja dwie zmiany produkcyjne na pewna date (szyli: na 15-12-2017: piersza zmiana i druga zmiana wpisuja ilosci produktow dla tego zeby komponenty byli przygotowany na magazinie)

plik liczy ile komponentow dla koznej zmiany produkcji nalezy przygotowac i generuje sie lista tych componentow. (zmiana wpisala plan -> wygenerowala sie lista componentow dla magazynu na pewna data)

programa musi miac interface graficzny (Data wpisuje sie tekstowe pole, podaje sie numer zmiany, z listy wybiera sie "FG", wpisuje sie ilosc)
plik moze uzyc SQLite
