# harjoitus3
Raportoin [Tero Karvisen Palvelinten Hallinta kurssin harjoitus 3 kotitehtävää](http://terokarvinen.com/2020/configuration-management-systems-palvelinten-hallinta-ict4tn022-autumn-2020/) 

Raportin aloitus 17:01

Käytän harjoituksessa pöytätietokonetta jossa [VirtualBoxissa](https://www.virtualbox.org/) pyörii Xubuntu 20.04.1 LTS Desktop.


Aloitin tehtävän antamalla komennot

$ sudo apt-get update

$ sudo apt-get upgrade

Käytin tehtävässä [Teron ohjeita](http://terokarvinen.com/2016/publish-your-project-with-github/index.html)

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

![diff](https://user-images.githubusercontent.com/74610221/99414816-dcbbd180-28ff-11eb-9594-6172bab1d3ae.PNG)


## e) Tee tyhmä muutos gittiin, älä tee commit:tia. Tuhoa huonot muutokset ‘git reset –hard’. Huomaa, että tässä toiminnossa ei ole peruutusnappia.

Tein muutaman muutoksen README.md tiedostoon ja käytin komentoa

$ git reset --hard

![reset](https://user-images.githubusercontent.com/74610221/99415463-7c795f80-2900-11eb-99e7-6097f3a408ab.PNG)
