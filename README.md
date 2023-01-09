# Verziókezelés alapjai

## 1. git letöltése

- [git for windows](https://gitforwindows.org/)

## 2. Konfigurációs parancsok

- git config --global user.name pinterroniaron
- git config --global user.email pinte.roni.aron@students.jedlik.eu
  -git config --global credential.helper wincred

## 3. Repository létrehozása

- git init
- git status

## 4. Állomány hozzáadása

> A stagen lévő állományokról tudunk állapotfelvételt (commitot) készíteni  
> Üres mappa nem kerül a stage-re

- git add állomány_neve
- git add . (összes állomány és mappa)

## 5. Állapotfelvétel (commit) készítése

- git commit -m "commit message"
