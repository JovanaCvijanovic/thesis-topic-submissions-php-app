# thesis-topic-submissions-php-app
Višeslojna veb aplikacija za upravljanje prijavama tema diplomskih radova, sa funkcionalnostima za studente i administratore, koja omogućava pregledne tabelarne prikaze, filtriranje i kontrolu statusa prijava.

## Opis projekta

Ovaj projekat predstavlja višeslojnu veb aplikaciju za upravljanje prijavom tema diplomskih radova. Aplikacija omogućava studentima da sami prijave svoju temu, dok administrator ima mogućnost potvrđivanja, ažuriranja i evidencije svih prijava.

Prilikom pokretanja aplikacije, korisnik se susreće sa stranicom `index.php` koja prikazuje informacije o autoru, tabelarni prikaz svih prijava sa opcijom filtriranja po broju indeksa, kao i link ka stranici za prijavu (`prijava.php`). Nakon prijave, korisnik vidi ime i prezime i odgovarajući meni u zavisnosti od tipa korisnika.

## Funkcionalnosti po tipu korisnika

**Student:**
- Može izvršiti prijavu svoje teme za diplomski rad

**Administrator:**
- Dodavanje novih prijava
- Korišćenje stored procedure za unos prijava
- Prikaz i ažuriranje postojećih prijava
- Filtriranje po broju indeksa
- Štampanje kompletne evidencije ili parametarska štampa po zadatom broju indeksa
- Provera obaveznih polja i poslovne logike prilikom unosa
- Kontrola statusa prijave: „prihvaćen“, „odbijen“ ili „u toku“

Ova aplikacija demonstrira razvoj višeslojne veb aplikacije sa različitim privilegijama korisnika i funkcionalnostima za jednostavno vođenje evidencije tema diplomskih radova.

## Tehnologije

Razvijena je korišćenjem **PHP**, **HTML**, **CSS**, **JavaScript** i **MariaDB** baze podataka unutar **XAMPP** platforme u **Visual Studio Code** okruženju.
