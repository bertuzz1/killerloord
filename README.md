# killerloord

## prerequisites:

1. Lataa [git](https://git-scm.com/download/win).
2. Lataa [nodejs](https://nodejs.org/en/).

Testaa että CLI (Command Line Tool)  on molemmissa käytössä seuraavasti:

Paina Win + R ja kirjoita riville: 

```
node -v
```

ja 

```
git --version
```

Molemmista pitäisi tulla versionumerot komennon jälkeen.

## kloonataan repository githubista koneelle

1. Ensin paina vihreää Clone or download-nappia tällä sivulla ja kopioi sisällä oleva repository url.

<img src="https://screenshots.firefox.com/eZqW47wZwGxZIC9V/github.com" align="right">

2. Tämän jälkeen avaa CMD (Win + R ja kirjoita "cmd" ja paina enter).
Tee kansio sopivaan paikkaan. (esim. "mkdir harjoitus" komento tekee kansion nimeltä harjoitus)

3. Siirry kansioosi komennolla "cd harjoitus". 

4. Kansion sisällä aja komento

```
git clone "tähän url joka on leikepöydällä githubista"
```

Esimerkki:

```
git clone https://github.com/panukettu/killerloord.git
```

Tavarat latautuu koneellesi.

## tehdään oma branchi ettei häslätä master-branchia sekaisin

1. CMD:ssä siirrytään taas harjoitus-kansioon jos siellä ei olla jo.

2. Tee oma bränchi seuraavasti: 
```
git checkout -b killerloord-nimesi
```

Esimerkki: 

```
git checkout -b killerloord-merihaka187
```





