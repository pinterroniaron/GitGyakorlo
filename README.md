# Verziókezelés alapjai

## 1. git letöltése

- [git for windows](https://gitforwindows.org/)
- [git scm](https://git-scm.com/)

## 2. Konfigurációs parancsok

- git config --global user.name hmate06
- git config --global user.email horvath.mate3@students.jedlik.eu
- git config --global ceredential.helper wincred

## 3. Repository létrehozása

- git init

## 4. Állomány hozzáadása a stage-hez

> A stagen lévő állományokról tudunk állapotfelvételt (commit-ot) készíteni
> Üres mappa nem kerül a stagae-re

- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)

## 5. Állapot felvétel (commit készítése)

- git commit -m "commit message"

## 6. Git állapot és log lekérdezése

- git status
- git log

## 7. Lokális változások feltöltése a távoli repóba

- git push

## 8. Távoli repó másolása (klónozása) a lokális gépre

- git clone "távoli repó URL címe"

## 9. Ágak (branches) kezelése

> Lokális ágak listázása

- git branch
  > Lokális és távoli ágak listázása
- git branch -av
  > Ág létrehozása
- git nranch új_ág_neve
  > Váltás egy másik ágra
- git checkout másik_ág_neve
  > Ág törlése (aktuális ág nem törölhető)
- git branch -d törlendő_ág_neve
  > Változások átvezetése (merge)
- git checkout
