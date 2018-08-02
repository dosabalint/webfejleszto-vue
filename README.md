# Webfejlesztő leszek! VueJS Edition - VueJS repositoryk

## Tartalomjegyzék

- Vue intro
  - [1. alkalom - 2018 június 5.](#1-alkalom---2018-június-5)
  - [2. alkalom - 2018 június 7.](#2-alkalom---2018-június-7)
  - [3. alkalom - 2018 június 12.](#3-alkalom---2018-június-12)
  - [4. alkalom - 2018 június 14.](#4-alkalom---2018-június-14)
  - [5. alkalom - 2018 június 19.](#5-alkalom---2018-június-19)
  - [6. alkalom - 2018 június 21.](#6-alkalom---2018-június-21)
  - [7. alkalom - 2018 június 26.](#7-alkalom---2018-június-26)
  - [8. alkalom - 2018 június 28.](#8-alkalom---2018-június-28)
  - [Gyakorláshoz](#gyakorláshoz)
- Vue advanced
  - [1. alkalom - 2018 július 10.](#1-alkalom---20180710)
  - [2. alkalom - 2018 július 17.](#2-alkalom---20180717)
  - [3. alkalom - 2018 július 18.](#3-alkalom---20180718)
  - [4. alkalom - 2018 július 24.](#4-alkalom---20180724)
  - [5. alkalom - 2018 július 26.](#5-alkalom---20180726)
  - [6. alkalom - 2018 július 31.](#6-alkalom---20180731)
  - [7. alkalom - 2018 augusztus 02.](#7-alkalom---20180802)

## Elérhetőségek

**NetAcademia Frontend csoport facebookon**

https://www.facebook.com/groups/364060044017273/

**Email**

- dosa.balint@netacademia.hu
- oktatok@netacademia.hu
- nagy.gergo@netacademia.hu

## Vue Advanced

### 7. alkalom - 2018.08.02.

**Feladat**

- route guard fix
- blog categories fix
- navigation refactor (profile link és logout)
- open source sw tanulási minta vue-routeren keresztül
- vue-router examples checkout, indítás és megértés

![Áttekintő az óráról](https://raw.githubusercontent.com/dosabalint/webfejleszto-vue/master/assets/mm-vue-advanced07.png)

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/releases/tag/adv07_0802_navigation-oss

### 6. alkalom - 2018.07.31.

**Feladat**

- vscode setup, hogy a html részt is formázza
- vue-app babel preset
- dataservice refactor + vuex + promisok
- firebase database app levedes
- firebase hosting
- házik

![Áttekintő az óráról](https://raw.githubusercontent.com/dosabalint/webfejleszto-vue/master/assets/mm-vue-advanced06.png)

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/releases/tag/adv06_0731_dataservice_es_firebase

### 5. alkalom - 2018.07.26.

**Feladat**

- átvesszük és kijavítjük a babel configunkat, hogy jobban vigyázzon ránk
- vuex-et ismétlünk
- types refactor elgépelés ellen
- user teljes refactor
- blog olvasás bejelenktkezéshez kötése
- localStorage használat login perszisztenciára

![Áttekintő az óráról](https://raw.githubusercontent.com/dosabalint/webfejleszto-vue/master/assets/mm-vue-advanced05.png)

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/releases/tag/adv05_0726_blog-levedes

### 4. alkalom - 2018.07.24.

**Feladat**

- megértjük a javascript fejlődését, verzióit
- átismétlünk pár új nyelvi elemet: rest, spred és destructoring
- megnézzük, hogy mit csinál nekünk pontosan a babel és hogyan működik együtt a webpack-el
- refactore-oljuk a store-unkat külön fileba, hogy függetlenedni tudjunk a Vue-s környezettől
  - megértjük hogyan is működnek pontosan az import exportok es2015-ben
- megismerjük a vuex-et
  - a frissen előállt független storeunkat refactoroljuk vuex-es verzióra, mert szeretjük ha okos emberek dolgoznak sokat helyettünk!
- megértjük, hogy miért is kellett ezt a részt az authentikáció kellős közepén megtanulnunk

![Áttekintő az óráról](https://raw.githubusercontent.com/dosabalint/webfejleszto-vue/master/assets/mm-vue-advanced04.png)

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/releases/tag/adv04_0724_vuex

### 3. alkalom - 2018.07.18.

**Feladat**

- Ismételjük az eddigieket azon keresztül, hogy megvalósítjuk a registration-t is
- refaktorolunk a kódunkon sokat, hogy minimalizáljuk önmagunk ismétlését
- logikailag elkezdjük elszeparálni az action-öket és a mutation-öket
  - egyelőre még a root instance eszközein keresztül

![Áttekintő az óráról](https://raw.githubusercontent.com/dosabalint/webfejleszto-vue/master/assets/mm-vue-advanced03.png)

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/releases/tag/adv03_0718_reigistration

### 2. alkalom - 2018.07.17.

**Feladat**

- Elkezdjük átemelni a login és a registrációs felületeket
- Implementáljuk a valós login-t az eddigi firebase-s ismereteink alapján
- Megismerkedünk a globál állapotkezelés problémájával, mivel service végzi a műveletet, de componentben szeretnénk használni ennek az eredményét
  - amit kipróbálunk:
    - global namespace (window)
    - root component data-ban adat tárolás
  - amit nem próbálunk ki, de érdekes és megoldás lehet hasonló problémára
    - [vue component mint message bus](https://alligator.io/vuejs/global-event-bus/)
    - [saját store megvalósítása](https://vuejs.org/v2/guide/state-management.html)
      - ezt még azért lehet elővesszük majd :smile:

![Áttekintő az óráról](https://raw.githubusercontent.com/dosabalint/webfejleszto-vue/master/assets/mm-vue-advanced02.png)

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/releases/tag/adv02_0717_login

### 1. alkalom - 2018.07.10.

**Feladat**

- átnézzük, hogy milyen eszközöket használunk majd a kurzus során
- átismételjük, hogy hogyan is épül fel a projekt és kicsit végig nézzük a kódunkat
- firebase ismétlés és használat
  - megcsináljuk az adatbázisunkat
  - megismerjük hogyan működik a firebase rest apin keresztül és megrángatjuk vs code extension segítségével
  - átemeljük a blogpostokat a lokális back-endünkről firebase-re
  - megnézzük hogyan működik a firebase authentikáció
  - beregisztráljuk az első userünket
  - levédjük az adatbázisunkat az idegenektől

![Áttekintő az óráról](https://raw.githubusercontent.com/dosabalint/webfejleszto-vue/master/assets/mm-vue-advanced01.png)

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/releases/tag/adv01_0710_firebase-auth-es-jogosultsagok

## Vue Intro

### 1. alkalom - 2018 június 5.

[Tematika](assets/mm-vue01.png)

#### 1/1. feladat - Ezt csak így ide be, és működik is

**Feladat**

Belekóstolunk a VueJS adta lehetőségekbe.

**Repository**

https://github.com/dosabalint/webfejleszto-vue-01-01

#### 1/2. feladat - Kereső refactor

**Feladat**

A JS-ben írt keresőnket átnézzük, hogy is nézne ki VueJS-re építve.

**Repository**

https://github.com/dosabalint/webfejleszto-vue-01-02

#### 1/3. feladat - Kosár refactor

**Feladat**

A korábban JS-ben írt kosarunkat is górcső alá vesszük, hátha tudunk rajta egyszerűsíteni.

**Repository**

https://github.com/dosabalint/webfejleszto-vue-01-03

### 2. alkalom - 2018 június 7.

[Tematika](assets/mm-vue02.png)

#### 2/1. feladat - NPM

**Feladat**

CDN helyett átállunk a package.json használatára

**Repository**

https://github.com/dosabalint/webfejleszto-vue-02-01

**Egyéb linkek**

- https://stackoverflow.com/a/31733623/4920059

#### 2/2. feladat - HTTP server és opener

**Feladat**

Belekóstolunk, hogy mit is lehet összerakni NPM és package.json segítségével.

**Repository**

https://github.com/dosabalint/webfejleszto-vue-02-02

#### 2/3. feladat - SASS

**Feladat**

Kiegészítjük CSS körüli ismereteinket a SASS-sal.

**Repository**

https://github.com/dosabalint/webfejleszto-vue-02-03

### 3. alkalom - 2018 június 12.

[Tematika](assets/mm-vue03.png)

#### 3/1. feladat - Komponensek

**Feladat**

Kipróbáljuk, hogy milyen VueJS komponensekkel dolgozni.

**Repository**

https://github.com/dosabalint/webfejleszto-vue-03-01

#### 3/2. feladat - Webpack

**Feladat**

A workflownkon csavarunk még egy kicsit a Webpackkel és .vue komponensekkel

**Repository**

https://github.com/dosabalint/webfejleszto-vue-03-02

#### 3/3. feladat - .vue komponensek

**Feladat**

Írunk egy saját .vue komponenst

**Repository**

https://github.com/dosabalint/webfejleszto-vue-03-03

### 4. alkalom - 2018 június 14.

[Tematika](assets/mm-vue04.png)

#### 4/1. feladat - Szerkezet átnézése

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/04-01_project-init

#### 4/2. feladat - index.html feldarabolása

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/04-02_index-darabolas

#### 4/3. feladat - blog oldal feldarabolása

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/04-03_blog-darabolas

#### 4/4. feladat - Navigation átdolgozása

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/04-04_navigation-atdolgozasa

### 5. alkalom - 2018 június 19.

[Tematika](assets/mm-vue05.png)

#### 5/1. feladat - Általános komponensek

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/05-01_altalanos-komponensek

#### 5/2. feladat - JSON server

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/05-02_json-server

**Egyéb linkek**

- https://spring.io/understanding/REST

#### 5/3. feladat - Blog - megjelenítés

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/05-03_blog-megjelenites

#### 5/4. feladat - Blog - szűrés

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/05-04_blog-szures

### 6. alkalom - 2018 június 21.

[Tematika](assets/mm-vue06.png)

#### 6/1. feladat - Vue Router

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/06-01_vue-router

#### 6/2. feladat - Blog category szűrés refactor

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/06-02_blog-category-szures-refactor

#### 6/3. feladat - Post oldal

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/06-03_post-oldal

#### Gyakorló / Házi feladat ötletek

- lapozó bevezetése
  - elsőre kategória szűréstől külön, utána akár egyben a kettőt
  - új route
  - $route.params alól oldalszám alapján tördelés
- kereső szűrő oldal
- címke szűrő oldal
- footer komponens

### 7. alkalom - 2018 június 26.

[Tematika](assets/mm-vue07.png)

#### 7/1. feladat - Firebase project

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/07-01_firebase-project

#### 7/2. feladat - DataService bővítés

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/07-02_dataservice-bovites

#### 7/3. feladat - Contact form

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/07-03_contact-form

### 8. alkalom - 2018 június 28.

[Tematika](assets/mm-vue08.png)

#### 8/1. feladat - Kérdőív oldal

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/08-01_kerdoiv-oldal

#### 8/2. feladat - DataService bővítés

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/08-02_dataservice-bovites

#### 8/3. feladat - Statisztika oldal

**Repository**

https://github.com/dosabalint/webfejleszto-vue-fizuhu/tree/08-03_statisztika-oldal

#### Egyéb linkek

- https://stackoverflow.com/questions/37922518/how-to-set-start-value-as-0-in-chartjs

## Gyakorláshoz

- jQuery kurzus példáinak átdolgozása VueJS alapon: https://github.com/dosabalint/webfejleszto-jquery
- JS kurzus példáinak átdolgozása VueJS alapon: https://github.com/dosabalint/webfejleszto-javascript
- VueJS.org példák: https://vuejs.org/v2/examples/
- Todo alkalmazás: https://vuejs.org/v2/examples/todomvc.html
