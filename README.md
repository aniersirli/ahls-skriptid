# Rakendusserverite halduse automatiseerimine
### Need skriptid sisaldavad: apache paigaldust, mysql-i paigaldamist, php paigaldamist ja phpmyadmin-i paigaldamist.
## Git
### Paigaldamine

Githubi paigaldamiseks tuleb teostada järgnevad käsud:
### Kuna tegu on haldusskriptidega, siis kõik tuleb kirjutada ja käivitada root kasutaja alt. Selleks kõige mõistlikum on ette valmistada root kasutaja kodukataloogis kataloog skriptide hoidmiseks, nimeks võib olla näiteks ahls.
```
su -
```

```
mkdir ahls
```

```
apt install git
```

### Seadistamine
### Githubi seadistamiseks on vaja konfigureerida nimi ja email ning seostada redaktor:

```
git config --global user.name "Eesnimi Perenimi"
git config --global.user email@domeen.com
git config --global core.editor nano

``` 
