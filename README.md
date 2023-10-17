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

<b>W trakcie</b>:

* <a href="https://www.udemy.com/course/cypress-od-podstaw/"><b>Cypress od podstaw - Automatyzacja testów</b></a>

## Przykładowy Projekt Testowy
W ramach realizacji programu kursów przygotowałem i wykonałem projekt testowy na podstawie fake'owej aplikacji <a href="http://mrbuggy.pl">MrBuggy7.</a>
* <a href="https://drive.google.com/file/d/1EECXOz-r8O28YpjqDiTg6zASwV-j1f5D/view?usp=sharing">Test plan</a>
* <a href="https://drive.google.com/file/d/1dJUUCbfbufjuhbVU7GxnM6ukjo6JlonJ/view?usp=sharing">Scenariusze i przypadki testowe</a>
* <a href="https://drive.google.com/drive/folders/1y3APODqmUxKS-DIqTkJtHAdyJ3WuCIy-?usp=sharing">Raporty z wykonanych przypadków testowych</a>
* <a href="https://drive.google.com/drive/folders/14_-K_8wi1qG5-IP2dDzeBs5KOgVLuJrT?usp=sharing">Przykładowe zgłoszenia błędów w programie JIRA wraz załącznikami</a>
* <a href="https://drive.google.com/file/d/1e048GXPURkOsNt55zcx6zMUQvg67NJGS/view?usp=sharing">Kompletny raport z projektu testowego</a>
* <a href="https://drive.google.com/file/d/1L691Ou5MtI0tLph0aR7kJzXtMXUG_VbT/view?usp=sharing">Specyfikacja techniczna aplikacji MrBuggy7 (plik pdf do wglądu)</a>

## Testy API - Postman, automatyzacja i integracja z narzędziami CI/CD
<img src="https://github.com/RomanDabrowski89/Resources/blob/8b9ade79eaa7bdbd1db05070ca6cd9496dc8c3b5/Baner_Postman%2BNewman%2BJenkins.png" alt="Baner Postman Newman Jenkins">

W trakcie kursów zdobyłem wiedzę teoretyczną z obszaru działania usług sieciowych (<b>RPC</b>, <b>SOAP</b>, <b>REST API</b>) jak i praktyczne umiejętności w pracy z programem <b>POSTMAN</b> i weryfikacji poprawności działania <b>API</b> serwerów, aplikacji webowych oraz stron www stworzonych w architekturze <b>REST</b> metodami <b>GET</b>, <b>POST</b>, <b>PUT</b>, <b>DELETE</b>. Nauczyłem się jak korzystać z <b>asercji Chai</b> do automatyzacji testów API w Postmanie oraz poznałem metody integracji testów API Postman z narzędziami <b>CI/CD</b> takimi jak <b>Newman</b> oraz <b>Jenkins</b>.

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

<p>&#8595; <b>POBIERZ</b>:<br><a href="https://drive.google.com/drive/folders/1PmoPQfls-4R0QhqPbrtvFfnpM6NWqx8G?usp=sharing">Kolekcja requestów <b>Trello API</b> oraz <b>środowisko</b></a> ze zmiennymi programu <b>Postman</b> (pliki w formacie json).</p>

<hr>

<p>&#9998; <b>PROJEKT</b>: TESTOWANIE ZABEZPIECZEŃ API PRZED NIEAUTORYZOWANYM DOSTĘPEM DO DANYCH.

* Weryfikacja poprawności działania <b>zabezpieczeń API</b> w serwisie <a href="https://httpbin.org"><b>HTTP BIN</b></a> metodami <b>basic auth</b> oraz <b>bearer token</b>. W kolekcji zostały zaimplementowane skrypty testów automatycznych w postaci asercji Chai.

<p>&#8595; <b>POBIERZ</b>:<br><a href="https://drive.google.com/drive/folders/1IV7Lj_TcqSkBcHH2uD6OD1uoPQkYADwH?usp=sharing">Kolekcja requestów testujących <b>autoryzację</b></a> (plik w formacie json).</p>

<hr>

<p>&#9998; <b>PROJEKT</b>: STWORZENIE MOCK SERWERA W PROGRAMIE POSTMAN.
  
* Stworzenie <b>emulacji API</b> serwera fake'owej aplikacji mediów społecznościowych zwracającego odpowiedzi na żądania <b>GET</b>, <b>POST</b>, <b>PUT</b>, <b>DELETE</b>. W kolekcji zostały zaimplementowane skrypty testów automatycznych w postaci asercji Chai.

<p>&#10004;<b>PROCES TWORZENIA I TESTOWANIA MOCK SERVER'A</b>:</p>

* określenie <b>żądań</b> oraz <b>endpoint'ów</b>, na które będzie zwracał odpowiedzi Mock server;
* określenie zwracanych przez Mock server <b>status kodów</b>, <b>nagłówków</b> oraz <b>ładunków</b>;
* implementacja skryptów testów automatycznych w postaci <b>asercji Chai</b> weryfikujących zwracane przez API Mock serwera odpowiedzi.

<p>&#8595; <b>POBIERZ</b>:<br><a href="https://drive.google.com/drive/folders/1FfKpYjDsUHPYp44xtUHIquT5X4NY6iG_?usp=sharing">Kolekcja requestów testujących <b>API Mock serwera</b></a> (plik w formacie json).</p>

## Język SQL - przykłady poleceń

Poznałem również podstawowe polecenia wykorzystywane w <b>języku SQL</b>.

<img src="https://github.com/RomanDabrowski89/Resources/blob/cb5168f9f624191e156997a8c51c8c2d6e76828c/SQL%20logo.png" width="85" height="45" alt="SQL logo">

[Jeżeli po kliknięciu w któryś z poniższych plików Dysk Google wyświetla komunikat <b>"Podgląd niedostępny"</b>, proszę odświeżyć stronę, np. klawiszem F5].

* <a href="https://drive.google.com/drive/folders/1k9RvWRgV-NecmNqAZr5nGUCgi8xf1F36?usp=sharing">SELECT</a>
* <a href="https://drive.google.com/drive/folders/1vxCQLkX9v1hNSGJGEsf1xZKTkKXALCO7?usp=sharing">INSERT</a>
* <a href="https://drive.google.com/drive/folders/1QgzH_fCcGW_zX-1kg0w3YrrrDmwbllCh?usp=sharing">UPDATE</a>
* <a href="https://drive.google.com/drive/folders/11hlbF4pKjT4UxfabQap6mIHOTzbGGx3B?usp=sharing">DELETE</a>
* <a href="https://drive.google.com/drive/folders/1yOBUHk2ALxw3GHf7lge89a_ZwEUZwQYW?usp=sharing">INNER JOIN</a>
* <a href="https://drive.google.com/file/d/1tymCcd0n7uee9DUG-Kmy65nuS8vPSF79/view?usp=sharing">LEFT JOIN</a>
* <a href="https://drive.google.com/file/d/1sDHbuJc2cDP-nmeH5av_QCQ1bc25j5QJ/view?usp=sharing">RIGHT JOIN</a>

## System kontroli wersji GIT

Zapoznałem się i pracowałem z rozproszonym systemem kontroli wersji GIT. Uczyłem się korzystania z terminala GIT (oraz GIT GUI) na maszynie lokalnej i za pomocą odpowiednich poleceń integrowania danych z repozytorium na serwerze github.com.

<img src="https://github.com/RomanDabrowski89/Resources/blob/4ed9ce972512276cf6239b962a5f0dbadb3e5840/GIT%20logo.png" width="105" height="105" alt="GIT logo">

## Narzędzia
W trakcie nauki zapoznałem się i korzystałem z oprogramowania oraz narzędzi przydatnych w codziennej pracy <b>Testera Oprogramowania</b>:

<img src="https://github.com/RomanDabrowski89/Resources/blob/a2870ddefcb02626343642f1fa6322d7b6863cbc/Tools%20logo.png" width="80" height="80" alt="Tools logo">

* PicPick
* Sharex
* Przeglądarki internetowe: Chrome, Edge, Firefox, Opera wraz z rozszerzeniami (PerfectPixel, ColorZilla, GoFullPage, JSON Viewer, WhatFont)
* Devtools
* TestLink
* JIRA
* Postman
* GIT
* Owasp Zap
* Jmeter
* BrowserStack
## Parę słów o mnie
<img src="https://github.com/RomanDabrowski89/Resources/blob/7fccdf36dc81655cb50c9bd8f7a411a20896b1ce/Baner%20About.png" alt="Baner About">

Pojęcie procesu tworzenia, rozwoju oraz dostarczania oprogramowania w filozofii <b>Agile</b> nie jest mi obce, zarówno jak i metodyka w <b>Scrum'owym</b> systemie pracy.
Z natury jestem bardzo skrupulatną, dokładną oraz spostrzegawczą osobą. Lubię wiedzieć jak coś działa, <b>a jeszcze bardziej dlaczego coś NIE działa :)</b>. Cechy te na pewno okażą się przydatne w codziennej pracy testera.

W kręgu moich zainteresowań znajdują się m. in. sprzęt komputerowy, oprogramowanie, nowinki technologiczne oraz gry komputerowe, które uwielbiam od najmłodszych lat. Biorę udział w beta testach gry dedykowanej na na urządzenia mobilne i system operacyjny Android, gdzie przeprowadzam testy eksploracyjne oraz niefunkcjonalne na poziomie systemowym i akceptacyjnym.

W kontaktach i komunikacji interpersonalnej staram się pamiętać, że to do nadawcy należy obowiązek sformułowania komunikatu tak, aby był zrozumiały dla odbiorcy. Lubię jasno określone obowiązki, stałe godziny pracy oraz ciszę, dzięki którym łatwiej, efektywniej i przede wszystkim przyjemniej wykonuję swoje zadania. Zależy mi na możliwości pracy hybrydowej lub docelowo zdalnej. Cenię sobie umiejętność merytorycznej i kulturalnej rozmowy na każdy, w tym również trudny temat. Nie akceptuję pracy opartej na domysłach, pod ciągłą presją czasu i chaosu (zarówno organizacyjnego, komunikacyjnego, jak i w otoczeniu).

Jestem pogodny, wyrozumiały i przyjazny oraz doskonale potrafię wysłuchać innych. W miejscach, w których przebywam roztaczam wspierającą i pozytywną atmosferę.
