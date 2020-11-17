# harjoitus3
Raportoin Tero Karvisen Palvelinten Hallinta kurssin harjoitus 3 kotitehtävää

Raportin aloitus 17:01

Käytän harjoituksessa pöytätietokonetta jossa VirtualBoxissa pyörii Xubuntu 20.04.1 LTS Desktop.


Aloitin tehtävän antamalla komennot

$ sudo apt-get update

$ sudo apt-get upgrade


## a) MarkDown. Tee tämän tehtävän raportti MarkDownina. Helpointa on tehdä raportti GitHub-varastoon, jolloin md-päätteiset tiedostot muotoillaan automaattisesti. Tyhjä rivi tekee kappalejaon, risuaita ‘#’ tekee otsikon, sisennys merkitsee koodinpätkän. Vinkkinä artikkelini Publish Your Project with GitHub.

Aloitin tekemällä github tunnukset ja luomalla uuden repositoryn

![create_repo](https://user-images.githubusercontent.com/74610221/99412087-04f60100-28fd-11eb-80f0-3148ce6c4143.PNG)

Tämän jälkeen kopioin tiedoston virtuaalikoneeni Xubuntuun komennolla

$ git clone https://github.com/frodhu23/harjoitukset3.git


Määrittelin käyttäjätiedot

$ git config --global user.email "sposti"

$ git config --global user.name "frodhu23"


![first_commit](https://user-images.githubusercontent.com/74610221/99412698-b1d07e00-28fd-11eb-8873-1bb447649fb4.PNG)

![git_push](https://user-images.githubusercontent.com/74610221/99412782-c6147b00-28fd-11eb-92d1-dc356df0b0e3.PNG)

## d) Näytä omalla git-varastollasi esimerkit komennoista ‘git log’, ‘git diff’ ja ‘git blame’. Selitä tulokset.

Git log komento kertoo kaikki repositoryyn tehdyt muutokset ja commitit, committien ajajan ja päivämäärän.

Git diff komennolla näet paikallisen kansion ja github repositoryn eron 
