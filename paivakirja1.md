# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Helpointa oli Gitin perustoiminnot esim git status, add ja commit, ne olivat myös heti selkeitä, että mitä ne tekevät.
Mitään erityisen vaikeaa ei mielestäni tehtävissä ollut ehkä restore ja revert komentojen ero oli aluksi vähän epäselvä, mutta se selkeni vähän.
Haarojen käyttäminen tuntui ensin oudolta, mutta nopeasti ymmärsin miten ne toimivat. Oppimisess auttoi git status komennon käyttö aina välissä.
Siitä näki suoraan ns onko mitään tapahtunut. Suurimmat esteet johtuivat kirjotusvirheistä ja ne selvisivät kun katsoi ohjeita ja uudestaan sitä mitä oli kirjoittanut.


## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | luo git repon |
| git status | näyttää nykyisen tilanteen |
| git add | lisää tiedoston seuraavaan tallennukseen |
| git commit -m "" | tallentaa muutokset git versiohistoriaan, muutoksien viestin kanssa |
| git log | näyttää tehtyjen tallennusten historian |
| git restore --staged | poistaa tiedoston seuraavasto tallennuksesta |
| git restore | peruuttaa tallentamattomat muutokset |
| git revert | kumoaa aikaisemman tallennukset tekemällä uuden |
| git tag | luo tunnisteen tallennukselle |
| git branch | näyttää git haarat |
| git switch | vaihtaa aktiivista haaraa |
| git merge --no-ff | yhdistää haaran nykyiseen haaraan |
| git log --oneline --graph --decorate --all | näyttää git historian tiiviisti ja graafisesti, myös eri haarat |

