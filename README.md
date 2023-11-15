# Roman Dąbrowski - Portfolio
Cześć, miło mi Cię gościć w moim repozytorium testerskim.

<b>Proszę, rozejrzyj się :)</b>

Znajdziesz tutaj przykłady umiejętności, które zdobyłem w trakcie nauki <b>testowania oprogramowania</b>.

Jeżeli chciał_byś poznać mnie trochę bliżej, w ostatniej sekcji zamieściłem parę słów o mnie.

## Kursy i certyfikaty

<b>Kursy, które ukończyłem do tej pory na platformie Udemy</b>:

* <a href="https://www.udemy.com/course/praktyczny-kurs-testowania-oprogramowania/?kw=praktyczny+kurs+testowania&src=sac"><b>Praktyczny kurs testowania oprogramowania</b></a>

<img src="https://github.com/RomanDabrowski89/Resources/blob/0f9ade2bfed078ff73d2859c90eab205106e00d3/Certyfikat%20-%20Kurs%20Testowania%20Oprogramowania.png" alt="Certyfikat - Kurs Testowania Oprogramowania">
<hr>

* <a href="https://www.udemy.com/course/postman-od-podstaw-testowanie-rest-api/"><b>Postman od podstaw - testowanie REST API</b></a>

<img src="https://github.com/RomanDabrowski89/Resources/blob/main/Certyfikat%20-%20Kurs%20Postman%20od%20podstaw.png" alt="Certyfikat - Kurs Postman od Podstaw">
<hr>

<b>Kursy, które chcę zrealizować w następnej kolejności</b>:

* <a href="https://www.udemy.com/course/cypress-od-podstaw/"><b>Cypress od podstaw - Automatyzacja testów</b></a>

## Przykładowy Projekt Testowy
W ramach realizacji programu kursów przygotowałem i wykonałem projekt testowy na podstawie fake'owej aplikacji <a href="http://mrbuggy.pl">MrBuggy7.</a>
* <a href="https://github.com/RomanDabrowski89/Resources/blob/main/Projekt%20Testowy%20MrBuggy7/Test%20Plan%20-%20MrBuggy7.pdf">Test plan</a>
* <a href="https://github.com/RomanDabrowski89/Resources/blob/main/Projekt%20Testowy%20MrBuggy7/Scenariusz%20i%20przypadki%20testowe%20-%20Mr-Buggy-7.pdf">Scenariusz i przypadki testowe</a>
* <a href="https://github.com/RomanDabrowski89/Resources/tree/main/Projekt%20Testowy%20MrBuggy7/Wykonane%20przypadki%20testowe">Raporty z wykonanych przypadków testowych</a>
* <a href="https://github.com/RomanDabrowski89/Resources/tree/main/Projekt%20Testowy%20MrBuggy7/Zg%C5%82oszenia%20B%C5%82%C4%99d%C3%B3w%20w%20Jira">Przykładowe zgłoszenia błędów w programie JIRA wraz załącznikami</a>
* <a href="https://github.com/RomanDabrowski89/Resources/blob/main/Projekt%20Testowy%20MrBuggy7/Raport%20z%20Projektu%20Testowego%20-%20MrBuggy7.pdf">Raport z projektu testowego</a>
* <a href="https://github.com/RomanDabrowski89/Resources/blob/main/Projekt%20Testowy%20MrBuggy7/MrBuggy7-Specyfikacja-Techniczna-v1.pdf">Specyfikacja techniczna aplikacji MrBuggy7 (plik pdf do wglądu)</a>

## Testy API - Postman, automatyzacja i integracja z narzędziami CI/CD
<img src="https://github.com/RomanDabrowski89/Resources/blob/8b9ade79eaa7bdbd1db05070ca6cd9496dc8c3b5/Baner_Postman%2BNewman%2BJenkins.png" alt="Baner Postman Newman Jenkins">

W trakcie kursów zdobyłem wiedzę teoretyczną z obszaru działania usług sieciowych (<b>RPC</b>, <b>SOAP</b>, <b>REST API</b>) jak i praktyczne umiejętności w pracy z programem <b>Postman</b> i weryfikacji poprawności działania <b>API</b> serwerów, aplikacji webowych oraz stron www stworzonych w architekturze <b>REST</b> metodami <b>GET</b>, <b>POST</b>, <b>PUT</b>, <b>DELETE</b>. Nauczyłem się jak korzystać z <b>asercji Chai</b> do automatyzacji testów API w Postmanie oraz poznałem metody integracji testów API Postman z narzędziami <b>CI/CD</b> takimi jak <b>Newman</b> oraz <b>Jenkins</b>.

W trakcie pracy z programem nauczyłem się również tworzenia <b>Mock serwerów</b> do emulacji serwerów produkcyjnych w środowisku testowym, praktycznego korzystania ze <b>zmiennych</b> (globalnych, środowiskowych, kolekcji) oraz operowaniem <b>parametrami zapytań</b>.

<hr>

<p>&#9998; <b>PROJEKT</b>: PRAKTYCZNE TESTOWANIE <b>REST API</b> APLIKACJI WEBOWEJ <a href="https://trello.com/pl"><b>TRELLO</b></a>.
  
* Weryfikacja działania <b>REST API</b> Trello zaimplementowanego na środowisku produkcyjnym na podstawie oficjalnej <a href="https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/">dokumentacji technicznej</a>. W kolekcji zostały zaimplementowane skrypty żądań wstępnych oraz skrypty testów automatycznych w postaci asercji Chai.</p>

<p>&#10004;<b>PROCES TESTOWANIA TRELLO API</b>:</p>

* przygotowanie oraz skonfigurowanie <b>obszaru roboczego</b> (workspace);
* stworzenie środowiska, kolekcji oraz poszczególnych requestów z metodami <b>GET</b>, <b>POST</b>, <b>PUT</b>, <b>DELETE</b>;
* stworzenie i wykorzystanie <b>zmiennych środowiskowych</b>, <b>kolekcji</b> oraz <b>globalnych</b>;
* operowanie <b>parametrami zapytań</b> w requestach;
* implementacja <b>Skryptów żądań wstępnych</b> (m. in. generator pseudolosowych adresów e-mail oraz nazw użytkowników);
* implementacja <b>Skryptów testów automatycznych</b> w postaci <b>asercji Chai</b> weryfikujących response zwracany przez API serwera Trello;
* agregacja utworzonych requestów i skryptów testowych w <b>automatyczną sekwencję testową</b> za pomocą <b>Runnera kolekcji Postman</b> i <b>Postman Monitors</b>;
* testowanie <b>zabezpieczeń API</b> przed nieautoryzowanym dostępem do danych metodami: <b>API Key</b> oraz <b>API Token</b>;
* integracja testów API Postman z programem <b>Newman</b> uruchamianych z poziomu <b>wiersza poleceń</b> (<b>CLI</b>) - za pomocą plików programu Postman w formacie json oraz adresów URL;
* integracja testów API Postman z <b>serwerem automatyzacji testów Jenkins</b>.

<p>&#8595; <b>POBIERZ</b>:<br><a href="https://github.com/RomanDabrowski89/Resources/tree/main/Postman%20-%20testowanie%20API/Trello%20REST%20API%20Tests">Kolekcja requestów <b>Trello API</b> oraz <b>środowisko</b></a> ze zmiennymi programu <b>Postman</b> (pliki w formacie json).</p>

<hr>

<p>&#9998; <b>PROJEKT</b>: TESTOWANIE ZABEZPIECZEŃ API PRZED NIEAUTORYZOWANYM DOSTĘPEM DO DANYCH.

* Weryfikacja poprawności działania <b>zabezpieczeń API</b> w serwisie <a href="https://httpbin.org"><b>HTTP BIN</b></a> metodami <b>basic auth</b> oraz <b>bearer token</b>. W kolekcji zostały zaimplementowane skrypty testów automatycznych w postaci asercji Chai.

<p>&#8595; <b>POBIERZ</b>:<br><a href="https://github.com/RomanDabrowski89/Resources/blob/main/Postman%20-%20testowanie%20API/HTTP_BIN-Auth_verification.json">Kolekcja requestów testujących <b>autoryzację</b></a> (plik w formacie json).</p>

<hr>

<p>&#9998; <b>PROJEKT</b>: STWORZENIE MOCK SERWERA W PROGRAMIE POSTMAN.
  
* Stworzenie <b>emulacji API</b> serwera fake'owej aplikacji mediów społecznościowych zwracającego odpowiedzi na żądania <b>GET</b>, <b>POST</b>, <b>PUT</b>, <b>DELETE</b>. W kolekcji zostały zaimplementowane skrypty testów automatycznych w postaci asercji Chai.

<p>&#10004;<b>PROCES TWORZENIA I TESTOWANIA MOCK SERVER'A</b>:</p>

* określenie <b>żądań</b> oraz <b>endpoint'ów</b>, na które będzie zwracał odpowiedzi Mock server;
* określenie zwracanych przez Mock server <b>status kodów</b>, <b>nagłówków</b> oraz <b>ładunków</b>;
* implementacja skryptów testów automatycznych w postaci <b>asercji Chai</b> weryfikujących zwracane przez API Mock serwera odpowiedzi.

<p>&#8595; <b>POBIERZ</b>:<br><a href="https://github.com/RomanDabrowski89/Resources/blob/main/Postman%20-%20testowanie%20API/Mock_server-Dummy_app.json">Kolekcja requestów testujących <b>API Mock serwera</b></a> (plik w formacie json).</p>

## Język SQL - przykłady poleceń

Poznałem również podstawowe polecenia wykorzystywane w <b>języku SQL</b>.

<img src="https://github.com/RomanDabrowski89/Resources/blob/cb5168f9f624191e156997a8c51c8c2d6e76828c/SQL%20logo.png" width="85" height="45" alt="SQL logo">

* <a href="https://github.com/RomanDabrowski89/Resources/tree/main/SQL/SELECT">SELECT</a>
* <a href="https://github.com/RomanDabrowski89/Resources/tree/main/SQL/INSERT">INSERT</a>
* <a href="https://github.com/RomanDabrowski89/Resources/tree/main/SQL/UPDATE">UPDATE</a>
* <a href="https://github.com/RomanDabrowski89/Resources/tree/main/SQL/DELETE">DELETE</a>
* <a href="https://github.com/RomanDabrowski89/Resources/tree/main/SQL/INNER%20JOIN">INNER JOIN</a>
* <a href="https://github.com/RomanDabrowski89/Resources/blob/main/SQL/SQL%20-%20polecenie%20LEFT%20JOIN%20-%201.png">LEFT JOIN</a>
* <a href="https://github.com/RomanDabrowski89/Resources/blob/main/SQL/SQL%20-%20polecenie%20RIGHT%20JOIN%20-%201.png">RIGHT JOIN</a>
* <a href="https://github.com/RomanDabrowski89/Resources/blob/main/SQL/SQL%20-%20polecenie%20LEFT%2BRIGHT%20JOIN%20-%201.png">LEFT+RIGHT JOIN</a>

## System kontroli wersji GIT

Zapoznałem się i pracowałem z rozproszonym systemem kontroli wersji GIT. Uczyłem się korzystania z terminala GIT (oraz GIT GUI) na maszynie lokalnej i za pomocą odpowiednich poleceń integrowania danych z repozytorium na serwerze github.com.

<img src="https://github.com/RomanDabrowski89/Resources/blob/4ed9ce972512276cf6239b962a5f0dbadb3e5840/GIT%20logo.png" width="105" height="105" alt="GIT logo">

## Narzędzia
W trakcie nauki zapoznałem się i korzystałem z oprogramowania oraz narzędzi przydatnych w codziennej pracy <b>Testera Oprogramowania</b>:

<img src="https://github.com/RomanDabrowski89/Resources/blob/a2870ddefcb02626343642f1fa6322d7b6863cbc/Tools%20logo.png" width="80" height="80" alt="Tools logo">

* Postman
* TestLink
* JIRA
* Devtools
* Jenkins
* Newman
* GIT
* BrowserStack
* PicPick
* Sharex
* Przeglądarki internetowe: Chrome, Edge, Firefox, Opera wraz z rozszerzeniami (PerfectPixel, ColorZilla, GoFullPage, JSON Viewer, WhatFont)
* Owasp Zap
* Jmeter
## Parę słów o mnie
<img src="https://github.com/RomanDabrowski89/Resources/blob/7fccdf36dc81655cb50c9bd8f7a411a20896b1ce/Baner%20About.png" alt="Baner About">

Pojęcie procesu tworzenia, rozwoju oraz dostarczania oprogramowania w filozofii <b>Agile</b> nie jest mi obce, zarówno jak i metodyka w <b>Scrum'owym</b> systemie pracy.
Z natury jestem bardzo skrupulatną, dokładną oraz spostrzegawczą osobą. Lubię wiedzieć jak coś działa, <b>a jeszcze bardziej dlaczego coś NIE działa :)</b>. Cechy te na pewno okażą się przydatne w codziennej pracy testera.

W kręgu moich zainteresowań znajdują się m. in. sprzęt komputerowy, oprogramowanie, nowinki technologiczne oraz gry komputerowe, które uwielbiam od najmłodszych lat. Biorę udział w beta testach gry dedykowanej na na urządzenia mobilne i system operacyjny Android, gdzie przeprowadzam testy eksploracyjne, niefunkcjonalne oraz E2E na poziomie akceptacyjnym.

Lubię pracę według wytycznych, jasno określone obowiązki oraz porządek. Cechuje mnie świetna organizacja pracy, zaangażowanie, dokładność, rzetelność oraz chęć do nauki i samorozwoju. Cenię umiejętność merytorycznej i kulturalnej rozmowy na każdy, w tym również trudny temat.

Jestem pogodny i przyjaźnie nastawiony wobec ludzi. Potrafię doskonale wsłuchiwać w innych, a w miejscach w których przebywam roztaczam wspierającą i pozytywną atmosferę.
