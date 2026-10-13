# Privacy Policy / Политика приватности / Politika privatnosti / Adatvédelmi nyilatkozat

Select your language / Изаберите језик / Izaberite jezik / Válasszon nyelvet:
* [🇷🇸 Српски (Ћирилица)](#српски-ћирилица)
* [🇷🇸 Srpski (Latinica)](#srpski-latinica)
* [🇭🇺 Magyar](#magyar)
* [🇬🇧 English](#english)

---

## Српски (Ћирилица)

**Датум ступања на снагу:** 22. јун 2026.  
**Архитектура апликације:** Прогресивна веб апликација (PWA) / Власнички бесплатни софтвер  
**Назив апликације:** Kabasti-SU  
**Развојни тим / Издавач:** cvekiboy  

### 1. Приватност и прикупљање података
Kabasti-SU је дизајниран као апликација која првенствено ради локално. Њена главна сврха је да помогне корисницима да прегледају распореде одвожења кабастог отпада и управљају подсетницима на сопственим уређајима.

Издавач, **cvekiboy**, намерно не прикупља имена корисника, имејл адресе, листе контаката нити друге информације које могу директно идентификовати корисника кроз основну функционалност апликације.

Апликација користи **Google Analytics 4 (GA4)** за прикупљање ограничене статистике о коришћењу, као што је описано у одељку 3 у наставку. Због тога се апликација не може сматрати потпуно ослобођеном од аналитике или телеметрије.

### Локални статус апликације
Kорисничка подешавања, конфигурација интерфејса, изабране заједнице и подешавања подсетника чувају се локално на уређају корисника, користећи локално складиште апликације и/или складиште података апликације.

Ове информације се користе искључиво за очување подешавања и омогућавање функционалности апликације. Оне се намерно не отпремају (не шаљу) издавачу у оквиру уобичајеног рада подсетника и мапа.

### Рад ван мреже (Оффлине)
Након што се преузму или кеширају неопходни подаци о мапама и елементи апликације, апликација је дизајнирана да пружи своју основну функционалност мапа и распореда ван мреже (оффлине), свуда где су тражени локални подаци доступни.

Активна интернет веза је неопходна за онлајн функције, као што су провера ажурирања апликације, преузимање ажурираних елемената и пренос аналитичких догађаја. Ове онлајн функције могу бити недоступне када је уређај ван мреже.

### 2. Мрежни приступ и логика контроле верзија
Kако би се осигурала тачност мапа и исправност апликације, мрежне могућности које захтева ова ПWА апликација строго су ограничене на следећу анонимну условну проверу:

1. **Провера верзије:** При покретању, апликација проверава удаљени (`version.json`) фајл и упоређује га са метаподацима о верзији који долазе уз инсталирану апликацију.
2. **Условно преузимање:** 
   * **Ако се верзије подударају:** Подаци се не преузимају. Апликација користи фајлове који се налазе искључиво локално у корисничком директоријуму са подацима апликације (`app_data`).
   * **Ако се верзије разликују:** Апликација преузима ажуриране статичке, неличне податке — конкретно језичке преводе (`translations.json`) и географске маркере за месне заједнице (`kabasti_MZs.geojson`).
3. **Учесталост ажурирања:** Географски подаци о распореду и преводи се генерално ажурирају по потреби, обично око пролећног и јесењег периода сакупљања отпада. Стварна учесталост ажурирања може варирати.
4. **Мрежни метаподаци:** Kао и код обичних интернет захтева, сервери који управљају овим везама могу примити техничке информације о вези, као што је ИП адреса, и могу обрађивати сервер логове у складу са сопственим правилима. Апликација намерно не укључује име или имејл адресу корисника у свој захтев за проверу верзије.

## 3. Статистика коришћења и Гоогле Аналyтицс 4
Kabasti-SU користи **Google Analytics 4 (GA4)** за ограничену статистичку анализу са циљем да помогне издавачу да разуме како се апликација користи и које верзије апликације су и даље у употреби.

Сврха ове анализе је подршка одржавању, доношењу одлука о компатибилности и будућем развоју — а не приказивање огласа (реклама) корисницима.

У зависности од платформе апликације и аналитичког догађаја, информације које се преносе сервису Google Analytics могу укључивати:

- Догађаји у апликацији: као што су покретање апликације и прегледи страница или екрана.  
- Информације о верзији апликације и платформи: (оперативном систему).  
- Технички параметри догађаја: као што су наслови и локације страница или екрана, где је то примењиво.  
- Псеудонимни идентификатор клијента и информације о сесији: који се користе за разликовање активности током времена.  
- Стандардне аналитичке информације: које Google Analytics може извести из захтева, као што су приближни географски подаци и карактеристике уређаја или веб-прегледача, у зависности од имплементације и конфигурације.  

Издавач намерно не укључује имена корисника, имејл адресе или изабране подсетнике у аналитичке догађаје. Аналитички идентификатори нису исто што и име особе, али могу разликовати клијента или инсталацију апликације током времена.

Аналитички подаци се преносе и обрађују од стране компаније **Google**, која и пружа услугу аналитике. Googl-ово управљање овим информацијама такође подлеже њиховим сопственим правилима и условима коришћења:

https://policies.google.com/privacy

Издавач користи добијене извештаје за статистику апликације и доношење одлука о развоју. Није предвиђено да се ова имплементација аналитике користи за оглашавање, ремаркетинг или продају личних података.

Аналитика захтева мрежни приступ. Уколико се захтеви за аналитику не могу извршити, апликација треба да настави да пружа своју основну функционалност, независно од мрежне повезаности са аналитиком.

### 4. Скраћени приказ софтверске лиценце (Власничка)
Софтверски извршни фајлови, дизајн интерфејса и омот апликације лиценцирани су под **Власничким и затвореним бесплатним софтвером** (Proprietary & Closed-Source Freeware).
* Додељује вам се бесплатна, неексклузивна лиценца за личну, образовну или интерну пословну употребу.
* Строго је забрањено декомпајлирање, реверзибилни инжењеринг, измена извршних фајлова, комерцијално подлиценцирање или редистрибуција софтверског кода без навођења линка ка званичном репозиторијуму.

### 5. Лиценца за географске податке и обавезно навођење извора (ODbL v1.0)
Ова апликација садржи и стримује пратећи географски ресурс (`subotica.pmtiles`) који се чува унутар нашег система.

* **Обавештење о дериватној бази података:** Ресурс `subotica.pmtiles` је *Дериватна база података* која садржи модификоване географске податке преузете са [OpenStreetMap](https://openstreetmap.org).
* **Отвореност и независност података:** За разлику од власничког софтверског кода апликације, ова база података представља отворене податке, који су строго регулисани лиценцом [Open Data Commons Open Database License (ODbL) v1.0](https://opendatacommons.org).
* **Права на преузимање и измене:** Корисници имају право да копирају, дистрибуирају, преносе и прилагођавају ову базу података. Можете преузети ову компоненту директно преко [subotica.pmtiles](https://raw.githubusercontent.com/cvekiboy/Kabasti-SU/main/OSM-Data/subotica.pmtiles) путање репозиторијума. Све измене морају бити дељене под потпуно истим условима ODbL лиценце.
* **Обавезно правно навођење аутора:** Географски подаци © корисници [OpenStreetMap](https://www.openstreetmap.org/copyright)-а.
* **Локализовани услови:** За комплетне локалне дефиниције и језичка својства погледајте фајл [DATA_LICENSE.md](https://github.com/cvekiboy/Kabasti-SU/blob/main/DATA_LICENSE.md#српски-ћирилица) у нашем репозиторијуму.

### 6. Kонтрола података и контакт
Kорисници могу користити основне функције апликације без креирања налога или давања свог имена или имејл адресе.

Локална подешавања апликације и подешавања подсетника могу се уклонити брисањем локалних података апликације или деинсталирањем апликације, у зависности од начина на који оперативни систем управља подацима апликације.

Пренос аналитике је одвојен од локалних подсетника и података о мапама. Kорисници који желе да спрече мрежне захтеве аналитике могу користити одговарајуће контроле на уређају или мрежи како би их блокирали, иако апликација тренутно не пружа наменску опцију за искључивање аналитике унутар саме апликације.

За питања о овој политици или пракси поступања са подацима у апликацији, можете контактирати издавача путем контакт информација наведених на званичној страници апликације на Microsoft Store-у, Google Play-у или на страници пројекта.

Ова политика може бити ажурирана када се промене функције апликације или пракса поступања са подацима.

---

## Srpski (Latinica)

**Datum stupanja na snagu:** 22. jun 2026.  
**Arhitektura aplikacije:** Progresivna veb aplikacija (PWA) / Vlasnički besplatni softver  
**Naziv aplikacije:** Kabasti-SU  
**Razvojni tim / Izdavač:** cvekiboy  

### 1. Privatnost i prikupljanje podataka
Kabasti-SU je dizajniran kao aplikacija koja prvenstveno radi lokalno (local-first). Njena glavna svrha je da pomogne korisnicima da pregledaju rasporede odvoženja kabastog otpada i upravljaju podsetnicima na sopstvenim uređajima.

Izdavač, **cvekiboy**, namerno ne prikuplja imena korisnika, imejl adrese, liste kontakata niti druge informacije koje mogu direktno identifikovati korisnika kroz osnovnu funkcionalnost aplikacije.

Aplikacija koristi **Google Analytics 4 (GA4)** za prikupljanje ograničene statistike o korišćenju, kao što je opisano u odeljku 3 u nastavku. Zbog toga se aplikacija ne može smatrati potpuno oslobođenom od analitike ili telemetrije.

### Lokalni status aplikacije
Korisnička podešavanja, konfiguracija interfejsa, izabrane zajednice i podešavanja podsetnika čuvaju se lokalno na uređaju korisnika, koristeći lokalno skladište aplikacije i/ili skladište podataka aplikacije.

Ove informacije se koriste isključivo za očuvanje podešavanja i omogućavanje funkcionalnosti aplikacije. One se namerno ne otpremaju (ne šalju) izdavaču u okviru uobičajenog rada podsetnika i mapa.

### Rad van mreže (Offline)
Nakon što se preuzmu ili keširaju neophodni podaci o mapama i elementi aplikacije, aplikacija je dizajnirana da pruži svoju osnovnu funkcionalnost mapa i rasporeda van mreže (offline), svuda gde su traženi lokalni podaci dostupni.

Aktivna internet veza je neophodna za onlajn funkcije, kao što su provera ažuriranja aplikacije, preuzimanje ažuriranih elemenata i prenos analitičkih događaja. Ove onlajn funkcije mogu biti nedostupne kada je uređaj van mreže.

### 2. Mrežni pristup i logika kontrole verzija
Kako bi se osigurala tačnost mapa i ispravnost aplikacije, mrežne mogućnosti koje zahteva ova PWA aplikacija strogo su ograničene na sledeću anonimnu uslovnu proveru:

1. **Provera verzije:** Pri pokretanju, aplikacija proverava udaljeni (`version.json`) fajl i upoređuje ga sa metapodacima o verziji koji dolaze uz instaliranu aplikaciju.
2. **Uslovno preuzimanje:** 
   * **Ako se verzije podudaraju:** Podaci se ne preuzimaju. Aplikacija koristi fajlove koji se nalaze isključivo lokalno u korisničkom direktorijumu sa podacima aplikacije (`app_data`).
   * **Ako se verzije razlikuju:** Aplikacija preuzima ažurirane statičke, nelične podatke — konkretno jezičke prevode (`translations.json`) i geografske markere za mesne zajednice (`kabasti_MZs.geojson`).
3. **Učestalost ažuriranja:** Geografski podaci o rasporedu i prevodi se generalno ažuriraju po potrebi, obično oko prolećnog i jesenjeg perioda sakupljanja otpada. Stvarna učestalost ažuriranja može varirati.
4. **Mrežni metapodaci:** Kao i kod običnih internet zahteva, serveri koji upravljaju ovim vezama mogu primiti tehničke informacije o vezi, kao što je IP adresa, i mogu obrađivati server logove u skladu sa sopstvenim pravilima. Aplikacija namerno ne uključuje ime ili imejl adresu korisnika u svoj zahtev za proveru verzije.

## 3. Statistika korišćenja i Google Analytics 4
Kabasti-SU koristi **Google Analytics 4 (GA4)** za ograničenu statističku analizu sa ciljem da pomogne izdavaču da razume kako se aplikacija koristi i koje verzije aplikacije su i dalje u upotrebi.

Svrha ove analize je podrška održavanju, donošenju odluka o kompatibilnosti i budućem razvoju — a ne prikazivanje oglasa (reklama) korisnicima.

U zavisnosti od platforme aplikacije i analitičkog događaja, informacije koje se prenose servisu Google Analytics mogu uključivati:

- Događaji u aplikaciji: kao što su pokretanje aplikacije i pregledi stranica ili ekrana.  
- Informacije o verziji aplikacije i platformi: (operativnom sistemu).  
- Tehnički parametri događaja: kao što su naslovi i lokacije stranica ili ekrana, gde je to primenjivo.  
- Pseudonimni identifikator klijenta i informacije o sesiji: koji se koriste za razlikovanje aktivnosti tokom vremena.  
- Standardne analitičke informacije: koje Google Analytics može izvesti iz zahteva, kao što su približni geografski podaci i karakteristike uređaja ili veb-pregledača, u zavisnosti od implementacije i konfiguracije.  

Izdavač namerno ne uključuje imena korisnika, imejl adrese ili izabrane podsetnike u analitičke događaje. Analitički identifikatori nisu isto što i ime osobe, ali mogu razlikovati klijenta ili instalaciju aplikacije tokom vremena.

Analitički podaci se prenose i obrađuju od strane kompanije **Google**, koja i pruža uslugu analitike. Google-ovo upravljanje ovim informacijama takođe podleže njihovim sopstvenim pravilima i uslovima korišćenja:

https://policies.google.com/privacy

Izdavač koristi dobijene izveštaje za statistiku aplikacije i donošenje odluka o razvoju. Nije predviđeno da se ova implementacija analitike koristi za oglašavanje, remarketing ili prodaju ličnih podataka.

Analitika zahteva mrežni pristup. Ukoliko se zahtevi za analitiku ne mogu izvršiti, aplikacija treba da nastavi da pruža svoju osnovnu funkcionalnost, nezavisno od mrežne povezanosti sa analitikom.

### 4. Skraćeni prikaz softverske licence (Vlasnička)
Softverski izvršni fajlovi, dizajn interfejsa i omot aplikacije licencirani su pod **Vlasničkim i zatvorenim besplatnim softverom** (Proprietary & Closed-Source Freeware).
* Dodeljuje vam se besplatna, neekskluzivna licenca za ličnu, obrazovnu ili internu poslovnu upotrebu.
* Strogo je zabranjeno dekompajliranje, reverzibilni inženjering, izmena izvršnih fajlova, komercijalno podlicenciranje ili redistribucija softverskog koda bez navođenja linka ka zvaničnom repozitorijumu.

### 5. Licenca za geografske podatke i obavezno navođenje izvora (ODbL v1.0)
Ova aplikacija sadrži i strimuje prateći geografski resurs (`subotica.pmtiles`) koji se čuva unutar našeg sistema.

* **Obaveštenje o derivatnoj bazi podataka:** Resurs `subotica.pmtiles` je *Derivatna baza podataka* koja sadrži modifikovane geografske podatke preuzete sa [OpenStreetMap](https://openstreetmap.org).
* **Otvorenost i nezavisnost podataka:** Za razliku od vlasničkog softverskog koda aplikacije, ova baza podataka predstavlja otvorene podatke, koji su strogo regulisani licencom [Open Data Commons Open Database License (ODbL) v1.0](https://opendatacommons.org).
* **Prava na preuzimanje i izmene:** Korisnici imaju pravo da kopiraju, distribuiraju, prenose i prilagođavaju ovu bazu podataka. Možete preuzeti ovu komponentu direktno preko [subotica.pmtiles](https://raw.githubusercontent.com/cvekiboy/Kabasti-SU/main/OSM-Data/subotica.pmtiles) putanje repozitorijuma. Sve izmene moraju biti deljene pod potpuno istim uslovima ODbL licence.
* **Obavezno pravno navođenje autora:** Geografski podaci © korisnici [OpenStreetMap](https://www.openstreetmap.org/copyright)-a.
* **Lokalizovani uslovi:** Za kompletne lokalne definicije i jezička svojstva pogledajte fajl [DATA_LICENSE.md](https://github.com/cvekiboy/Kabasti-SU/blob/main/DATA_LICENSE.md#srpski-latinica) u našem repozitorijumu.

### 6. Kontrola podataka i kontakt
Korisnici mogu koristiti osnovne funkcije aplikacije bez kreiranja naloga ili davanja svog imena ili imejl adrese.

Lokalna podešavanja aplikacije i podešavanja podsetnika mogu se ukloniti brisanjem lokalnih podataka aplikacije ili deinstaliranjem aplikacije, u zavisnosti od načina na koji operativni sistem upravlja podacima aplikacije.

Prenos analitike je odvojen od lokalnih podsetnika i podataka o mapama. Korisnici koji žele da spreče mrežne zahteve analitike mogu koristiti odgovarajuće kontrole na uređaju ili mreži kako bi ih blokirali, iako aplikacija trenutno ne pruža namensku opciju za isključivanje analitike unutar same aplikacije.

Za pitanja o ovoj politici ili praksi postupanja sa podacima u aplikaciji, možete kontaktirati izdavača putem kontakt informacija navedenih na zvaničnoj stranici aplikacije na Microsoft Store-u, Google Play-u ili na stranici projekta.

Ova politika može biti ažurirana kada se promene funkcije aplikacije ili praksa postupanja sa podacima.

---

## Magyar

**Hatálybalépés dátuma:** 2026. június 22.  
**Alkalmazás architektúra:** Progresszív webalkalmazás (PWA) / Tulajdonosi ingyenes szoftver  
**Alkalmazás neve:** Kabasti-SU  
**Fejlesztő / Kiadó:** cvekiboy  

### 1. Adatvédelem és adatgyűjtés
A Kabasti-SU egy alapvetően helyi működésű (local-first) alkalmazásnak készült. Elsődleges célja, hogy segítsen a felhasználóknak megtekinteni a lomtalanítási menetrendeket és kezelni az emlékeztetőket a saját eszközeikkel.

A kiadó, **cvekiboy**, az alkalmazás alapvető funkcióin keresztül szándékosan nem gyűjti a felhasználók nevét, e-mail címét, névjegyzékét vagy egyéb közvetlen azonosításra alkalmas adatát.

Az alkalmazás a **Google Analytics 4 (GA4)** szolgáltatást használja a korlátozott használati statisztikák gyűjtésére, a lenti 3. szakaszban leírtak szerint. Ezért az alkalmazás nem tekinthető teljesen analitika- vagy telemetriamentesnek.

### Helyi alkalmazásállapot
A felhasználói beállítások, a felület konfigurációja, a kiválasztott közösségek és az emlékeztető beállítások helyileg, a felhasználó eszközén tárolódnak az alkalmazás helyi tárhelye és/vagy alkalmazásadat-tárhelye segítségével.

Ezek az információk a beállítások megőrzésére és az alkalmazás funkcióinak biztosítására szolgálnak. A szokásos emlékeztető- és térképfunkciók részeként ezek az adatok szándékosan nem kerülnek feltöltésre a kiadóhoz.

### Offline működés
A szükséges térképadatok és alkalmazásfájlok letöltése vagy gyorsítótárazása után az alkalmazást úgy tervezték, hogy alapvető térkép- és menetrend-funkcióit offline (internetkapcsolat nélkül) is biztosítsa, amennyiben a szükséges helyi adatok rendelkezésre állnak.

Aktív internetkapcsolat szükséges az olyan online funkciókhoz, mint az alkalmazásfrissítések ellenőrzése, a frissített tartalmak letöltése és az analitikai események továbbítása. Ezek az online funkciók nem érhetők el, ha az eszköz offline állapotban van.

### 2. Hálózati hozzáférés és verziókezelési logika
A térképek pontosságának és az alkalmazás megfelelő működésének biztosítása érdekében az ezen PWA által kért hálózati képességek szigorúan a következő anonim, feltételes ellenőrzésre korlátozódnak:

1. **Verzióellenőrzés:** Indításkor az alkalmazás ellenőriz egy távoli (`version.json`) fájlt, és összehasonlítja azt a telepített alkalmazáshoz mellékelt verzió-metadatokkal.
2. **Feltételes letöltés:** 
   * **Ha a verziók egyeznek:** Nem történik adatletöltés. Az alkalmazás kizárólag a felhasználói alkalmazásadat-könyvtárban (`app_data`) helyileg tárolt fájlokat használja.
   * **Ha a verziók eltérnek:** Az alkalmazás frissített statikus, nem személyes állományokat tölt le — kifejezetten nyelvi kulcsokat (`translations.json`) és a helyi közösségek (helyi önkormányzatok) földrajzi fedvényjelölőit (`kabasti_MZs.geojson`).
3. **Frissítési gyakoriság:** A földrajzi menetrendi adatok és fordítások általában szükség szerint frissülnek, jellemzően a tavaszi és őszi hulladékgyűjtési időszakok környékén. A tényleges frissítési gyakoriság változhat.
4. **Hálózati metaadatok:** A szokásos internetes kérésekhez hasonlóan az ezeket a kapcsolatokat kezelő szerverek technikai kapcsolati információkat kaphatnak, például egy IP-címet, és a szervernaplókat a saját szabályzatuk szerint dolgozhatják fel. Az alkalmazás szándékosan nem tartalmazza a felhasználó nevét vagy e-mail címét a verzióellenőrzési kérelemben.

## 3. Használati statisztikák és Google Analytics 4
A Kabasti-SU a **Google Analytics 4 (GA4)** szolgáltatást használja korlátozott statisztikai elemzésekhez, amelyek célja, hogy segítsék a kiadót annak megértésében, hogyan használják az alkalmazást, és mely alkalmazásverziók maradtak használatban.

Ennek az elemzésnek a célja a karbantartás, a kompatibilitási döntések és a jövőbeli fejlesztések támogatása — nem pedig a hirdetések kézbesítése a felhasználóknak.

Az alkalmazásplatformtól és az analitikai eseménytől függően a Google Analytics felé továbbított információk a következőket tartalmazhatják:

- Alkalmazásesemények: például az alkalmazás elindítása, valamint az oldal- vagy képernyőmegtekintések.  
- Alkalmazásverzió- és platforminformációk: (operációs rendszer).  
- Technikai eseményparaméterek: például az oldalak vagy képernyők címei és helyei, ahol ez alkalmazható.  
- Álnevesített (pszeudonimizált) ügyfél-azonosító és munkamenet-információk: a tevékenységek időbeli megkülönböztetésére.  
- Standard analitikai információk: amelyeket a Google Analytics vezethet le a kérésekből, például a hozzávetőleges földrajzi adatok, valamint az eszköz vagy a böngésző jellemzői, az implementációtól és a konfigurációtól függően.  

A kiadó szándékosan nem foglalja bele a felhasználók nevét, e-mail címét vagy emlékeztető-beállításait az analitikai eseményekbe. Az analitikai azonosítók nem egyenértékűek a személy nevével, de idővel megkülönböztethetik az ügyfelet vagy az alkalmazás-telepítést.

Az analitikai adatok továbbítását és feldolgozását a **Google** végzi, amely az analitikai szolgáltatást biztosítja. A Google ezen információk kezelése során a saját szabályzataira és feltételeire is támaszkodik:

https://policies.google.com/privacy

A kiadó a kapott jelentéseket alkalmazásstatisztikákhoz és fejlesztési döntésekhez használja fel. Az analitika ezen implementációja nem használható hirdetésre, remarketingre vagy személyes adatok értékesítésére.

Az analitika használatához hálózati hozzáférés szükséges. Ha az analitikai kérések nem teljesíthetők, az alkalmazásnak az analitikai kapcsolattól függetlenül is tovább kell biztosítana az alapvető funkcióit.

## 4. Szoftverlicenc összefoglaló (Tulajdonosi)
A szoftver bináris fájljai, a felület kialakítása és az alkalmazáscsomagolás a Tulajdonosi és zárt forráskódú ingyenes szoftver (Proprietary & Closed-Source Freeware) modell alá tartoznak.
* Ön ingyenes, nem kizárólagos licencet kap személyes, oktatási vagy belső üzleti célú felhasználásra.
* Szigorúan tilos a szoftverkód visszafejtése, forráskódjának visszafordítása, bináris módosítása, kereskedelmi továbblicencelése vagy terjesztése anélkül, hogy visszamutatna a hivatalos repozitóriumra.

## 5. Térképadat-licenc és kötelező forrásmegjelölés (ODbL v1.0) 
Ez az alkalmazás magában foglal és streamel egy kísérő földrajzi állományt (`subotica.pmtiles`), amely a rendszerünkben van tárolva.

* **Származtatott adatbázisra vonatkozó megjegyzés:** A `subotica.pmtiles` állomány egy *Származtatott adatbázis* amely az [OpenStreetMap](https://openstreetmap.org)oldalról származó, módosított földrajzi adatokat tartalmaz.
* **Adatok nyíltsága és függetlensége:** Az alkalmazás tulajdonosi szoftverkódjától eltérően ez az adatbázis nyílt adat, amelyet szigorúan az [Open Data Commons Open Database License (ODbL) v1.0](https://opendatacommons.org) szabályoz. 
* **Letöltési és módosítási jogok:** A felhasználóknak joguk van ezen alapuló állomány másolására, terjesztésére, továbbítására és adaptálására. Az összetevőt közvetlenül letöltheti a következő elérési [subotica.pmtiles](https://raw.githubusercontent.com/cvekiboy/Kabasti-SU/main/OSM-Data/subotica.pmtiles) repozitórium úton. Bármilyen módosítást pontosan ugyanazon ODbL licencfeltételek mellett kell megosztani.
* **Kötelező jogi forrásmegjelölés:** Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.
* **Helyi feltételek:** A teljes helyi definíciókért és nyelvi tulajdonságokért tekintse meg a repozitóriumunkban található [DATA_LICENSE.md](https://github.com/cvekiboy/Kabasti-SU/blob/main/DATA_LICENSE.md#magyar) fájlt.

## 6. Adatkezelés és kapcsolat
A felhasználók fiók létrehozása, valamint nevük vagy e-mail címük megadása nélkül is használhatják az alkalmazás alapvető funkcióit.

A helyi alkalmazásbeállítások és az emlékeztető beállítások eltávolíthatók az alkalmazás helyi adatainak törlésével vagy az alkalmazás eltávolításával (deinstalálásával), az operációs rendszer adatkezelési módjától függően.

An analitikai adatok továbbítása elkülönül a helyi emlékeztetőktől és térképadatoktól. Azok a felhasználók, akik meg akarják akadályozni az analitikai hálózati kéréseket, megfelelő eszköz- vagy hálózati szabályozókkal blokkolhatják azokat, bár az alkalmazás jelenleg nem biztosít külön alkalmazáson belüli funkciót az analitika kikapcsolására.

Az ezzel a szabályzattal vagy az alkalmazás adatkezelési gyakorlatával kapcsolatos kérdésekkel forduljon a kiadóhoz az alkalmazás Microsoft Store adatlapján, Google Play adatlapján vagy a projektoldalon megadott elérhetőségeken.

Ez a szabályzat frissülhet, ha az alkalmazás funkciói vagy adatkezelési gyakorlata megváltozik.

---

## English

**Effective Date:** June 22, 2026  
**Application Architecture:** Progressive Web App (PWA) / Proprietary Freeware  
**Application Name:** Kabasti-SU  
**Developer / Publisher:** cvekiboy  

## 1. Privacy & Data Collection
Kabasti-SU is designed to be a local-first application. Its primary purpose is to help users view bulky-waste collection schedules and manage reminders on their own devices.

The publisher, **cvekiboy**, does not intentionally collect users' names, email addresses, contact lists, or other directly identifying information through the application's core functionality.

The application does use **Google Analytics 4 (GA4)** to collect limited usage statistics, as described in Section 3 below. Therefore, the application should not be considered completely free of analytics or telemetry.

### Local Application State

User preferences, interface configuration, selected communities, and reminder settings are stored locally on the user's device using the application's local storage and/or application data storage.

This information is used to preserve settings and provide the application's features. It is not intentionally uploaded to the publisher as part of the normal reminder and map functionality.

### Offline Operation

After the necessary map data and application assets have been downloaded or cached, the application is designed to provide its core map and schedule functionality offline wherever the required local data is available.

An active internet connection is required for online features such as checking for application updates, downloading updated assets, and transmitting analytics events. These online features may be unavailable when the device is offline.

## 2. Network Access & Version Updates
To maintain accurate schedules and provide application updates, Kabasti-SU can access the following online resources:

1. **Version Checking:** On launch, the application checks a remote (`version.json`) file and compares it with the version metadata bundled with the installed application.
2. **Conditional Updates:** 
   * **If versions match:** No data is downloaded. The app utilizes files exclusively stored locally within the user app data directory (`app_data`).
   * **If versions differ:** The app downloads updated static, non-personal assets—specifically language keys (`translations.json`) and geographic overlay markers (`kabasti_MZs.geojson`).
3. **Update frequency:** Geographic schedule data and translations are generally updated when needed, typically around the spring and autumn collection periods. Actual update frequency may vary.
4. **Network metadata:** As with ordinary internet requests, the servers handling these connections may receive technical connection information, such as an IP address, and may process server logs according to their own policies. The application does not intentionally include a user's name or email address in its version-check request.

## 3. Usage Statistics & Google Analytics 4
Kabasti-SU uses **Google Analytics 4 (GA4)** for limited statistical analysis intended to help the publisher understand how the application is used and which application versions remain in use.

The purpose of this analysis is to support maintenance, compatibility decisions, and future development — not to deliver advertising to users.

Depending on the application platform and the analytics event, information transmitted to Google Analytics may include:

- Application events, such as application launches and page or screen views.  
- Application version and platform information.  
- Technical event parameters, such as page or screen titles and locations, where applicable.  
- A pseudonymous client identifier and session-related information used to distinguish activity over time.  
- Standard analytics information that Google Analytics may derive from requests, such as approximate geographic information and device or browser characteristics, depending on the implementation and configuration.  

The publisher does not intentionally include user's names, email addresses, or reminder selections in analytics events. Analytics identifiers are not equivalent to a person's name, but they may distinguish a client or installation over time.

Analytics data is transmitted to and processed by **Google**, which provides the analytics service. Google's handling of this information is also subject to its own policies and terms:

https://policies.google.com/privacy

The publisher uses the resulting reports for application statistics and development decisions. The application is not intended to use this analytics implementation for advertising, remarketing, or the sale of personal information.

Analytics requires network access. If analytics requests cannot be completed, the application should continue to provide its core functionality independently of analytics connectivity.

## 4. Software License Summary (Proprietary)
The software binaries, interface design, and application wrapper are licensed under a **Proprietary & Closed-Source Freeware** model.
* You are granted a free, non-exclusive license for personal, educational, or internal business use.
* Decompilation, reverse engineering, binary modification, commercial sublicensing, or redistribution of the software code without linking back to the official repository is strictly prohibited.

## 5. Geographic Data License & Mandatory Attribution (ODbL v1.0)
This application bundles and streams a companion geographic asset (`subotica.pmtiles`) stored within our framework. 

* **Derivative Database Notice:** The `subotica.pmtiles` asset is a *Derivative Database* containing modified geographic data sourced from [OpenStreetMap](https://openstreetmap.org).
* **Data Openness & Independence:** Unlike the proprietary application software code, this database is open data, strictly governed by the [Open Data Commons Open Database License (ODbL) v1.0](https://opendatacommons.org). 
* **Download & Modification Rights:** Users have the right to copy, distribute, transmit, and adapt this underlying asset. You can download the component directly via the [subotica.pmtiles](https://raw.githubusercontent.com/cvekiboy/Kabasti-SU/main/OSM-Data/subotica.pmtiles) Repository Path. Any modifications must be shared under the exact same ODbL license terms.
* **Mandatory Legal Attribution:** Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.
* **Localized Terms:** For complete local definitions and language properties, see our repository [DATA_LICENSE.md](https://github.com/cvekiboy/Kabasti-SU/blob/main/DATA_LICENSE.md#english).

## 6. Data Control & Contact
Users can use the application's core features without creating an account or providing their name or email address.

Local application preferences and reminder settings can be removed by clearing the application's local data or uninstalling the application, subject to the operating system's handling of application data.

Analytics transmission is separate from the local reminder and map data. Users who wish to prevent analytics network requests may use suitable device or network controls to block them, although the application does not currently provide a dedicated in-app analytics opt-out.

For questions about this policy or the application's data practices, contact the publisher through the contact information provided on the application's Microsoft Store listing, Google Play listing or project page.

This policy may be updated when the application's features or data practices change.

