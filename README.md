# killerloord

## tehtävän tehneet:
- speedyrooster
- sinun nimesi? ;)

## Prerequisites:
1. Tee GitHub-tili.
2. Lataa [git](https://git-scm.com/download/win).

Testaa että CLI (Command Line Tool)  on molemmissa käytössä seuraavasti:

Paina Win + R ja kirjoita riville: 

```
git --version
```

Molemmista pitäisi tulla versionumerot komennon jälkeen.

## Kloonataan repository githubista koneelle

1. Ensin paina vihreää Clone or download-nappia tällä sivulla ja kopioi sisällä oleva repository url.

<img src="https://screenshots.firefox.com/eZqW47wZwGxZIC9V/github.com" align="right">

2. Tämän jälkeen avaa CMD (Win + R ja kirjoita "cmd" ja paina enter).
Tee kansio sopivaan paikkaan. (esim. "mkdir harjoitus" komento tekee kansion nimeltä harjoitus)

3. Siirry kansioosi esimerkiksi komennolla "cd harjoitus/killerloord". 

4. Kansion sisällä aja komento

```
git clone "tähän url joka on leikepöydällä githubista"
```

Esimerkki:

```
git clone https://github.com/panukettu/killerloord.git
```

Tavarat latautuu koneellesi.

## Tehdään oma branchi ettei häslätä master-branchia sekaisin

1. CMD:ssä siirrytään taas harjoitus-kansioon jos siellä ei olla jo.

2. Tee oma bränchi seuraavasti: 
```
git checkout -b killerloord-nimesi
```

Esimerkki: 

```
git checkout -b killerloord-merihaka187
```

## Tehdään muutoksia

1. Avaa kansiosi sisältä tiedosto README.md tekstieditorissa.

2. Editoi tiedostoon kohtaan "tehtävän tehneet" nimesi.

3. Mene CMD:llä taas kansioon ja aja komento 
```
git status
(näyttää mitä tiedostoja olet muokannut)
```

4. Seuraavaksi lisää muokatut tiedostot commit-listalle.
```
git add "tiedosto"
```

eli tässä tapauksessa:
```
git add readme.md
```

5. Committaa muutokset omaan repoosi GitHubissa seuraavalla komennolla:
```
git commit -m "Haluan mun nimeni README.md-tiedostoon herra kuningas."
```

## Muutokset githubiin

Seuraavalla komennolla pusketaan muutokset omaan githubiin:

```
git push origin reposi-nimi
```

eli tässä harjoituksessa repon nimi oli killerloord-merihaka187 joten:
```
git push origin killerloord-merihaka187
```

## Viedään muutokset omasta repositorystä yhteiseen repositoryyn hyväksyttäväksi

Muutokset ovat koskeneet vain omaa repositoryä tässä vaiheessa, tehdään siis "pull"-requesti yhteiseen repositoryyn jonka hallitsija hyväksyy tai hylkää muutoksesi:

1. Mene omaan GitHub-sivullesi (esim. http://github.com/panukettu)

2. Paina nappulaa "Compare & Pull request"

3. Seuraavassa ruudussa paina "Create pull request".

4. VALMIS ;)



