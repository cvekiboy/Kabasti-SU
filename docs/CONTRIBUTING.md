# Contributing Guidelines / Смернице за допринос / Smernice za doprinos / Közreműködési irányelvek

Select your language / Изаберите језик / Izaberite jezik / Válasszon nyelvet:
* [🇷🇸 Српски (Ћирилица)](#српски-ћирилица)
* [🇷🇸 Srpski (Latinica)](#srpski-latinica)
* [🇭🇺 Magyar](#magyar)
* [🇬🇧 English](#english)

---

## Српски (Ћирилица)

Хвала вам на интересовању за унапређење апликације Kabasti-SU! Ради очувања стабилности кода и обезбеђивања сигурносне верификације, сарадња на овом пројекту је структурисана искључиво око исправки података и превода.

### 🗺️ Локације контејнера и ажурирање распореда
Главна логика ове апликације је потпуно независна, али се географски подаци ослањају на јавне распореде. Ако се локација контејнера променила или ако су потребна прилагођавања координатних тачака унутар суботичких сектора:
1. **Немојте слати Pull Request-ове директно на овај главни репозиторијум.**
2. Сва сарадња у вези са подацима се обавља преко нашег наменског [**Updates репозиторијума**](https://github.com/cvekiboy/Kabasti-SU.updates).
3. Тамо можете изменити главни `kabasti_MZs.geojson` фајл или отворити "Issue" са тачним параметрима географске ширине и дужине (latitude/longitude).

### 🗣️ Исправке превода и језика
Ако сте уочили штампарску грешку, граматичку грешку или желите да побољшате изражавање на српском (латиници/ћирилици), мађарском или енглеском језику:
* Измене речника података такође треба послати на **Updates репозиторијум** путем `translations.json` фајла.
* За исправке превода главног распореда апликације или структурних текстова, молимо вас да прегледате активне теме пре слања било каквих измена.

### 💻 Главни изворни код
Ради усклађивања са смерницама за сертификацију апликација на глобалним продавницама (Google Play и Microsoft Store), изворни код компајлерског бекенда и фронтенд контејнера је закључан. Праћење техничких грешака и предлози за архитектуру система решавају се стриктно преко GitHub Issues на овом главном репозиторијуму.

---

## Srpski (Latinica)

Hvala vam na interesovanju za unapređenje aplikacije Kabasti-SU! Radi očuvanja stabilnosti koda i obezbeđivanja sigurnosne verifikacije, saradnja na ovom projektu je strukturisana isključivo oko ispravki podataka i prevoda.

### 🗺️ Lokacije kontejnera i ažuriranje rasporeda
Glavna logika ove aplikacije je potpuno nezavisna, ali se geografski podaci oslanjaju na javne rasporede. Ako se lokacija kontejnera promenila ili ako su potrebna prilagođavanja koordinatnih tačaka unutar subotičkih sektora:
1. **Nemojte slati Pull Request-ove direktno na ovaj glavni repozitorijum.**
2. Sva saradnja u vezi sa podacima se obavlja preko našeg namenskog [**Updates repozitorijuma**](https://github.com/cvekiboy/Kabasti-SU.updates).
3. Tamo možete izmeniti glavni `kabasti_MZs.geojson` fajl ili otvoriti "Issue" sa tačnim parametrima geografske širine i dužine (latitude/longitude).

### 🗣️ Ispravke prevoda i jezika
Ako ste uočili štamparsku grešku, gramatičku grešku ili želite da poboljšate izražavanje na srpskom (latinici/ćirilici), mađarskom ili engleskom jeziku:
* Izmene rečnika podataka takođe treba poslati na **Updates repozitorijum** putem `translations.json` fajla.
* Za ispravke prevoda glavnog rasporeda aplikacije ili strukturnih tekstova, molimo vas da pregledate aktivne teme pre slanja bilo kakvih izmena.

### 💻 Glavni izvorni kod
Radi usklađivanja sa smernicama za sertifikaciju aplikacija na globalnim prodavnicama (Google Play i Microsoft Store), izvorni kod kompajlerskog bekenda i frontend kontejnera je zaključan. Praćenje tehničkih grešaka i predlozi za arhitekturu sistema rešavaju se striktno preko GitHub Issues na ovom glavnom repozitorijumu.

---

## Magyar

Köszönjük a Kabasti-SU fejlesztése iránti érdeklődését! A kód stabilitásának megőrzése és a biztonsági ellenőrzés biztosítása érdekében a projekttel kapcsolatos közreműködés kizárólag az adat- és fordítási javításokra korlátozódik.

### 🗺️ Konténerlokációk és menetrend-frissítések
Az alkalmazás alapvető logikája teljesen független, de a földrajzi adatok a nyilvános menetrendeken alapulnak. Ha egy konténer helyszíne megváltozott, vagy ha a Szabadka szektorain belüli koordinátapontok korrekcióra szorulnak:
1. **Ne küldjön Pull Request-et közvetlenül ebbe a fő adattárba (core repository).**
2. Minden adattal kapcsolatos együttműködés a dedikált [**Updates adattárunkon**](https://github.com/cvekiboy/Kabasti-SU.updates) keresztül történik.
3. Ott módosíthatja a központi `kabasti_MZs.geojson` fájlt, vagy megnyithat egy "Issue"-t a pontos szélességi és hosszúsági (latitude/longitude) paraméterek megadásával.

### 🗣️ Fordítási és nyelvi javítások
Ha elírást, nyelvtani hibát észlel, vagy szeretné javítani a megfogalmazást szerb (latin/cirill), magyar vagy angol nyelven:
* Az adatszótár módosításait szintén az **Updates adattárba** kell benyújtani a `translations.json` fájlon keresztül.
* Az alkalmazás központi felületének vagy szerkezeti szövegeinek fordítási frissítései esetén kérjük, tekintse át az aktív témákat (issues), mielőtt bármilyen módosítást benyújtana.

### 💻 Központi forráskód
A globális alkalmazásáruházak (Google Play és Microsoft Store) tanúsítási irányelveinek való megfelelés érdekében a fordítóprogram-háttérrendszer (backend) és az előtér-konténer (frontend) forráskódja zárolva van. A technikai hibák követése és a rendszerarchitektúrára vonatkozó javaslatok kezelése szigorúan a GitHub Issues-on keresztül történik ebben a fő adattárban.

---

## English

Thank you for your interest in improving Kabasti-SU! To maintain code stability and ensure security verification, collaboration on this project is structured around data and translation corrections.

### 🗺️ Container Locations & Schedule Updates
The core logic of this application is fully independent, but the geographical data relies on public schedules. If a container location has changed, or if coordinate points inside the Subotica sectors need adjustments:
1. **Do not submit Pull Requests directly to this core repository.**
2. All data collaboration is handled via our dedicated [**Updates Repository**](https://github.com/cvekiboy/Kabasti-SU.updates).
3. You can modify the core `kabasti_MZs.geojson` file there or open an issue with the correct latitude/longitude parameters.

### 🗣️ Translation & Language Fixes
If you spotted a typo, grammatical error, or want to improve the phrasing in Serbian (Latin/Cyrillic), Hungarian, or English:
* Data dictionary modifications should also be submitted to the **Updates Repository** via the `translations.json` file.
* For core application layout or structural translation updates, please review the active issues before submitting any changes.

### 💻 Core Source Code
To comply with global marketplace app store certification guidelines (Google Play and Microsoft Store), the core compiler backend and frontend container source code are locked. Technical bug tracking is handled strictly via GitHub Issues on this main repository.


