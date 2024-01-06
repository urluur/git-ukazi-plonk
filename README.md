# Git ukazi

## Inicializacija

| Ukaz | Primer | Opis |
|-|-|-|
|init|`git init`| Trenutni repozitorij postane git repozitorij
|clone|`git clone [link]` | Kloniranje je le olepšana beseda za "download"

## Objavljanje

| Ukaz | Primer | Opis |
|-|-|-|
|status|`git status`| Najpomembnejše informacije o spremembah in repozitoriju
|add|`git add .` | Izbereš datoteke, ki jih boš želel commitati (dodaš v "stage")
|commit|`git commit -m "komentar"`|Vsebino datotek shranimo kot točko na časovnici prepoznavno po komentarju|
|push|`git push`|Vse commite pošlje na oddaljen repozitorij|
|fetch|`git fetch`|Osveži spremembe z oddaljenega repozitorija|
|pull|`git pull`|Prenese spremembe z oddaljenega repozitorija|

## Dodatno

| Ukaz | Primer | Opis |
|-|-|-|
|config color.ui|`git config --global color.ui auto`|Barve v terminalu so bolj izrazite|
|commit -a -m|`git commit -a -m "komentar"`|Ukaz add . združimo z ukazom commit|
|branch tree|`git log --oneline --graph --decorate --all`|Pokaže drevo vseh vej (izhod=q)|
