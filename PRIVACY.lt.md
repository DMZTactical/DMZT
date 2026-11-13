# DMZ Tactical privatumo politika

Atnaujinta: 2026 m. lapkričio 14 d. · [English](PRIVACY.md)

DMZ Tactical yra nepriklausoma nemokama Call of Duty DMZ pagalbinė programa. Čia aprašyta, kokius duomenis tvarko programa ir mūsų Discord serveris, kodėl ir kaip juos ištrinti.

Kontaktas privatumo klausimais: **dmztacticaltool@gmail.com**

## Trumpai

* Paskyros nereikia. Be jos žemėlapis, planai, daiktų sąrašai ir nustatymai lieka tavo kompiuteryje. Prisijungus reido planai, Orders progresas, "Ką surinkti" sąrašas, išsaugoti ginklų komplektai ir Operator Traits rinkinys saugomi ir tavo paskyroje, kad kituose tavo kompiuteriuose būtų tokie patys.
* Reklamų nėra. Programa analitikos nesiunčia, nebent Nustatymuose įjungi **Anoniminę statistiką** (pagal nutylėjimą išjungta). Svetainėje jos nėra.
* Komandos paieška neprivaloma. Tavo Activision ID, žaidimo stilių ir portretą mato tik žaidėjai, kuriuos serveris įtraukia į tavo komandą.
* DMZ Tactical niekada neskaito žaidimo failų, atminties ar inventoriaus.
* Paskyrą programoje gali ištrinti bet kada.

## Be paskyros

Be paskyros žemėlapis, reido planai, daiktų sąrašai, ginklų komplektai ir nustatymai saugomi tik tavo kompiuteryje (Windows naudotojo profilyje arba Mac programos duomenyse). Jie mums nesiunčiami.

Kad patikrintų ir atsisiųstų atnaujinimus, programa jungiasi prie GitHub. GitHub mato tavo IP adresą ([GitHub privatumo pareiškimas](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)).

Kad tarp programos versijų gautų žemėlapio, daiktų ir misijų atnaujinimus, programa atsisiunčia pasirašytą duomenų paketą iš dmzt.app, kurią talpina Cloudflare. Cloudflare mato tavo IP adresą; užklausoje nėra paskyros, profilio ar planų duomenų.

DMZ Tactical neskaito ir nekeičia žaidimo failų, atminties ar inventoriaus. Programoje nėra reklamos, ir ji nesiunčia nieko apie tai, kaip ja naudojiesi, nebent įjungi anoniminę statistiką.

## Anoniminė statistika (neprivaloma)

Pagal nutylėjimą išjungta. Jei programos Nustatymuose įjungi **Anoniminę statistiką**, Windows programa siunčia:

* kelių žingsnių dienos sumas: programa paleista (skaičiuojama kartą per dieną), prisijungta, operatorius išsaugotas ar atmestas, prisijungta prie komandos paieškos, komanda sudaryta;
* trumpus programos klaidų pranešimus, iš kurių prieš siunčiant išvalyti skaičiai, el. pašto adresai ir nuorodos;
* programos versiją.

Kartu nesaugomas joks žaidėjo, Discord ar Activision ID, diegimo identifikatorius ar IP adresas. Duomenys keliauja į Supabase Europos Sąjungoje ir padeda mums rasti klaidas (BDAR 6 straipsnio 1 dalies a punktas, tavo sutikimas). Nustatymuose gali ją bet kada išjungti; nuo tada daugiau niekas nesiunčiama.

## Su paskyra (komandos paieška ir sinchronizavimas)

Paskyra neprivaloma. Ji naudojama komandos paieškai ir tam, kad planai būtų visuose tavo kompiuteriuose. Prisijungi per Discord, ir mes saugome:

* **Iš Discord:** Discord naudotojo ID, vardą, avatarą ir el. pašto adresą. Mūsų prisijungimo paslauga el. pašto adresą iš Discord gauna kiekvieną kartą, kai prisijungi per Discord. Jo niekam nerodome ir laiškų juo nesiunčiame.
* **Operatoriaus profilį:** Activision ID, portretą, žaidimo stilių, regioną, kalbą ir mikrofono pasirinkimą.
* **Tavo planus, sąrašus ir rinkinius:** reido planus (pavadinimą, maršrutą, tikslus, raktus ir sąrašą), Orders progresą, "Ką surinkti" tikslus bei kiekius, išsaugotus ginklų komplektus (pavadinimą, ginklą ir priedus) ir Operator Traits rinkinį, kad kituose tavo kompiuteriuose jie būtų tokie patys. Vykstantis reidas ir aplankytos vietos lieka kompiuteryje, kuriame žaidi.
* **Paieškos metu:** kalbą, regioną, Duo ar Trio, Discord balso pasirinkimą ir eilės įrašą, kurį programa atnaujina, kol veikia.
* **Tavo komandą:** jos narius, jų „Pasiruošęs“ atsakymus ir balso komandai nuorodą į balso kambarį mūsų Discord serveryje.
* **Užblokuotus žaidėjus:** kad serveris jų daugiau nepriskirtų tavo komandai.
* **Tavo pranešimus:** pasirinktą priežastį, tavo ir praneštojo žaidėjo Discord naudotojo ID, jo Activision ID ir komandą. Pranešimą mato mūsų Discord moderatoriai privačiame kanale.

Eilėje laukiantys žaidėjai vienas kito nemato. Kai serveris sudaro komandą, tavo Activision ID, žaidimo stilių ir portretą mato tik jos nariai. Kai sustabdai paiešką ar uždarai programą, eilės įrašas ištrinamas per 90 sekundžių.

Activision ID tikriname tik pagal formatą. DMZ Tactical niekada neprisijungia prie tavo Activision paskyros.

Prisijungimo duomenys saugomi tavo kompiuteryje: Windows - užšifruoti Windows (DPAPI) tik tavo Windows naudotojui, Mac - tavo prisijungimo raktinėje (Keychain).

## Discord serveris ir botas

Jei naudojiesi mūsų Discord serveriu, DMZ Tactical botas saugo:

* Activision ID, kurį įvedi komanda `/activisionid` (botas jį perduoda į tavo paskyrą);
* mainų skelbimus su Activision ID (prieš skelbiant botas įspėja, kad ID bus viešas);
* mainų pranešimų nustatymus;
* uždarytus pagalbos pokalbius su žinutėmis ir priedais privačiame archyve;
* kai ieškai komandos komanda `/findsquad`: eilės įrašą toje pačioje komandos paieškos eilėje kaip programa ir privatų tavo komandos balso kambarį, kuris ištrinamas, kai lieka tuščias.

## Kur ir kodėl saugome

| Duomenys | Kur saugomi |
| --- | --- |
| Paskyros duomenys | [Supabase](https://supabase.com/privacy), Europos Sąjungoje |
| Anoniminė statistika (jei įjungta) | [Supabase](https://supabase.com/privacy), Europos Sąjungoje |
| Boto duomenys | Sparked Host, Paryžiuje, Prancūzijoje |

Duomenis naudojame:

* komandos paieškai, planų sinchronizavimui ir tavo pasirinktoms Discord funkcijoms teikti (BDAR 6 straipsnio 1 dalies b punktas);
* pagalbos pokalbiams išsaugoti ir paslaugai apsaugoti (6 straipsnio 1 dalies f punktas).

Duomenų neparduodame ir reklamai neperduodame.

## Kiek laiko saugome

| Duomenys | Kiek saugome |
| --- | --- |
| Paskyra ir profilis | Kol juos ištrini |
| Sinchronizuoti planai, sąrašai ir rinkiniai | Kol juos ar paskyrą ištrini; ištrintas įrašas laikomas 90 dienų, kad jį ištrintų ir kiti tavo kompiuteriai |
| Eilės įrašai | 90 sekundžių po paskutinio programos atnaujinimo; `/findsquad` – iki 30 minučių |
| Komandos ir jų balso kambarių nuorodos | 1 valandą |
| Užblokuoti žaidėjai | Kol ištrini paskyrą |
| Pranešimai apie komandos narius | 30 dienų |
| Anoniminė statistika | 90 dienų |
| Uždarytų pagalbos pokalbių archyvai | 12 mėnesių, paskui ištrinami |
| Boto duomenų bazės atsarginės kopijos | Kasdien pakeičiamos naujomis, saugomos paskutinės trys |

## Svetainė

[DMZ Tactical svetainė](https://dmzt.app/lt/) talpinama Cloudflare Pages. Joje nėra analitikos ir reklamų, ir ji pati nenustato slapukų. Cloudflare tvarko tavo IP adresą, kad pateiktų puslapius ir atsijotų botus, ir tam gali nustatyti būtiną apsaugos slapuką ([Cloudflare privatumo politika](https://www.cloudflare.com/privacypolicy/)).

## Kaip ištrinti duomenis

* **Programoje:** atverk **Paskyros nustatymus**, pasirink **Ištrinti paskyrą** ir patvirtink. Taip ištrinama paskyra, operatoriaus profilis, sinchronizuoti planai, sąrašai ir rinkiniai, išsaugotas Activision ID, eilės įrašas ir tavo užblokuoti žaidėjai. Kopijos tavo kompiuteriuose lieka.
* **Boto duomenis:** atidaryk pagalbos pokalbį komanda `/ticket` arba rašyk dmztacticaltool@gmail.com. Atsakome per 30 dienų.

## Tavo teisės

Gali prašyti:

* leisti susipažinti su savo duomenimis arba gauti jų kopiją;
* ištaisyti ar ištrinti savo duomenis.

Taip pat gali nesutikti, kad tavo duomenys būtų naudojami.

Skundą gali pateikti Valstybinei duomenų apsaugos inspekcijai ([vdai.lrv.lt](https://vdai.lrv.lt)).

## Pakeitimai

Apie politikos pakeitimus skelbiame svetainėje, šioje saugykloje ir Discord serveryje.

---

[Svetainė](https://dmzt.app/lt/privacy/) · [Atsisiuntimo puslapis](README.lt.md) · [Discord](https://discord.gg/PzCZNqmybB)
