---
TOCTitle: 'MS11-APR'
Title: 'Podsumowanie biuletynów zabezpieczeń firmy Microsoft za kwiecień 2011 r.'
ms:assetid: 'ms11-apr'
ms:contentKeyID: 61233120
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms11-apr(v=Security.10)'
---
Podsumowanie biuletynów zabezpieczeń firmy Microsoft za kwiecień 2011 r.
========================================================================

Opublikowano: 12 kwietnia 2011 | Zaktualizowano: 26 października 2011

**Wersja:** 6.1

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za kwiecień 2011 r.

Z chwilą opublikowania biuletynów zabezpieczeń za kwiecień 2011 r. niniejsze podsumowanie biuletynów zastąpi powiadomienie o biuletynach zabezpieczeń wydane 7 kwietnia 2011 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j. ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

13 kwietnia 2011 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępni emisję internetową, w której znajdą się odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). [Zarejestruj się, aby zobaczyć emisję internetową dotyczącą biuletynów zabezpieczeń za kwiecień](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032455069&eventcategory=4). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

Firma Microsoft udostępnia także informacje, dzięki którym klienci mogą ustalić priorytety dla aktualizacji zabezpieczeń w związku z niezwiązanymi z zabezpieczeniami aktualizacjami, które publikowane są w tym samym dniu, co comiesięczne aktualizacje zabezpieczeń. Zapoznaj się z sekcją **Inne informacje**.

### Informacje o biuletynie

Streszczenia
------------

<span></span>
Następująca tabela zawiera podsumowanie biuletynów zabezpieczeń za ten miesiąc (uporządkowanych według wskaźnika ważności).

Szczegółowe informacje o programach, których dotyczy luka, znajdują się w następnej sekcji, **Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**.

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Identyfikator biuletynu</th>
<th style="border:1px solid black;" >Tytuł biuletynu i streszczenie</th>
<th style="border:1px solid black;" >Maksymalny wskaźnik ważności oraz wpływ luki</th>
<th style="border:1px solid black;" >Wymaganie dotyczące ponownego uruchomienia</th>
<th style="border:1px solid black;" >Programy, których dotyczy problem</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td style="border:1px solid black;"><strong>Zbiorcza aktualizacja zabezpieczeń programu Internet Explorer(2497640)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa cztery luki w zabezpieczeniach programu Internet Explorer zgłoszone przez użytkowników i jedną lukę w zabezpieczeniach programu Internet Explorer zgłoszoną przez organizacje publiczne. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „krytyczny” dla programów Internet Explorer 6, Internet Explorer 7 i Internet Explorer 8 na klientach systemu Windows oraz wskaźnik ważności „umiarkowany” dla programów Internet Explorer 6, Internet Explorer 7 i Internet Explorer 8 na serwerach Windows. Omawiane luki w zabezpieczeniach nie dotyczą programu Internet Explorer 9.<br />
<br />
Najpoważniejsze z tych luk umożliwiają zdalne wykonanie kodu, jeśli użytkownik wyświetli specjalnie spreparowaną stronę sieci Web przy użyciu programu Internet Explorer. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212314">MS11-019</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach klienta SMB umożliwiają zdalne wykonanie kodu (2511455)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa jedną lukę zgłoszoną przez organizacje publiczne oraz jedną lukę zgłoszoną przez użytkowników. Istnieją one w systemie Windows. Groźniejsze spośród tych luk w zabezpieczeniach umożliwiają zdalne wykonanie kodu, jeśli osoba atakująca wyśle specjalnie spreparowaną odpowiedź SMB na żądanie SMB zainicjowane przez klienta. Aby wykorzystać lukę, osoba atakująca musi przekonać użytkownika do zainicjowania połączenia SMB ze specjalnie spreparowanym serwerem SMB.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212236">MS11-020</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach serwera SMB umożliwia zdalne wykonanie kodu (2508429)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows. Luka ta umożliwia zdalne wykonanie kodu, jeśli osoba atakująca utworzy specjalnie spreparowany pakiet SMB i wyśle go do systemu, którego dotyczy problem. Stosowanie najlepszych rozwiązań dotyczących zapór oraz standardowych konfiguracji domyślnej zapory może uchronić sieci przed atakami mającymi wykorzystać omawiane luki, których źródło znajduje się poza granicami przedsiębiorstwa.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=214005">MS11-027</a></td>
<td style="border:1px solid black;"><strong>Zbiorcza aktualizacja zabezpieczeń bitów „zabicia”</strong> <strong>dla formantów ActiveX (2508272)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach oprogramowania Microsoft zgłoszone przez użytkowników i jedną lukę w zabezpieczeniach oprogramowania Microsoft zgłoszoną przez organizacje publiczne. Luki te mogą pozwolić na zdalne wykonanie kodu, jeśli użytkownik wyświetli za pomocą programu Internet Explorer specjalnie spreparowaną stronę sieci Web, która uruchamia określony formant ActiveX. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi. Niniejsza aktualizacja obejmuje także bity „zabicia” dla trzech formantów ActiveX innych producentów.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207931">MS11-028</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach systemu .NET Framework umożliwia zdalne wykonanie kodu (2484015)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach platformy Microsoft .NET Framework zgłoszoną przez organizację publiczną. Luka w zabezpieczeniach umożliwia zdalne wykonanie kodu w systemie klienta, jeśli użytkownik wyświetli specjalnie spreparowaną stronę sieci Web w przeglądarce obsługującej aplikacje przeglądarki XAML (XBAP). Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi. Omawiana luka umożliwia także zdalne wykonanie kodu w systemach serwerowych z działającym programem IIS, jeśli dany serwer zezwala na przetwarzanie stron ASP.NET, a osobie atakującej uda się przekazać na ten serwer specjalnie spreparowaną stronę ASP.NET i uruchomić ją, tak jak mogłoby to wyglądać w scenariuszu z wykorzystaniem hostingu w sieci Web. Omawiana luka może też zostać wykorzystana przez aplikacje Windows .NET do obejścia ograniczeń zabezpieczeń dostępu kodu (CAS).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208524">MS11-029</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach interfejsu GDI+ umożliwia zdalne wykonanie kodu (2489979)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach interfejsu GDI+ systemu Microsoft Windows, która została zgłoszona przez użytkowników. Luka ta umożliwia zdalne wykonanie kodu, jeśli użytkownik wyświetli specjalnie spreparowany plik obrazu przy użyciu oprogramowania, którego dotyczy problem, lub jeśli przejdzie do witryny sieci Web zawierającej specjalnie spreparowaną zawartość. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212595">MS11-030</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach usługi rozpoznawania nazw DNS umożliwia zdalne wykonanie kodu (2509553)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w zabezpieczeniach usługi rozpoznawania nazw DNS systemu Windows. Luka może pozwolić na zdalne wykonanie kodu, jeśli osoba atakująca uzyska dostęp do sieci i utworzy niestandardowy program, który będzie rozsyłać kwerendy emisji LLMNR do systemów docelowych. Sprawdzone metody działania stosowane w zaporach oraz standardowe domyślne konfiguracje zapór mogą pomóc w zabezpieczeniu sieci przed atakami spoza obszaru działania przedsiębiorstwa. Zgodnie ze standardowymi zasadami działania zaleca się, aby w systemach połączonych z Internetem była otwarta jak najmniejsza liczba portów. W takim przypadku dostęp do portów LLMNR z Internetu powinien zostać zablokowany.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212243">MS11-031</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach aparatów obsługi skryptów JScript i VBScript</strong> <strong>umożliwia zdalne wykonanie kodu (2514666)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach aparatów obsługi skryptów JScript i VBScript, która została zgłoszona przez użytkowników. Ta luka w zabezpieczeniach umożliwia zdalne wykonanie kodu, jeśli użytkownik odwiedzi specjalnie spreparowaną witrynę sieci Web. Intruz nie może w żaden sposób zmusić użytkowników do odwiedzenia tej witryny. Musi natomiast przekonać użytkowników do odwiedzenia tej witryny, najczęściej zachęcając do kliknięcia łącza w wiadomości e-mail lub wiadomości błyskawicznej, które przekieruje użytkowników do witryny osoby atakującej.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212224">MS11-032</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach sterownika OpenType Compact Font Format (CFF) umożliwia zdalne wykonanie kodu (2507618)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach sterownika OpenType Compact Font Format (CFF), która została zgłoszona przez użytkowników. Luka umożliwia zdalne wykonanie kodu, jeśli użytkownik wyświetli zawartość zawierającą specjalnie spreparowaną czcionkę CFF. Jednakże w żadnym przypadku osoba atakująca nie może zmusić użytkowników do wyświetlenia specjalnie spreparowanej zawartości. Musi natomiast przekonać użytkowników do odwiedzenia witryny sieci Web, najczęściej zachęcając do kliknięcia łącza w wiadomości e-mail lub wiadomości błyskawicznej, które przekieruje użytkowników do witryny osoby atakującej.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach programu Microsoft Excel umożliwiają zdalne wykonanie kodu (2489279)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa dziewięć luk w zabezpieczeniach pakietu Microsoft Office, które zostały zgłoszone przez użytkowników. Luki te mogą umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik programu Excel. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać takie same uprawnienia jak zalogowany użytkownik. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach programu Microsoft PowerPoint umożliwiają zdalne wykonanie kodu (2489283)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa trzy luki w zabezpieczeniach programu Microsoft PowerPoint, które zostały zgłoszone przez użytkowników. Luki te mogą umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik programu PowerPoint. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi. Automatyczna opcja <strong>naprawy firmy Microsoft</strong> dla programów PowerPoint 2010, „Wyłączenie edycji w widoku chronionym w programie PowerPoint 2010&quot;, dostępna w <a href="http://support.microsoft.com/kb/2501584">artykule 2501584 bazy wiedzy Microsoft Knowledge Base</a>, blokuje kierunki ataku umożliwiające wykorzystanie luk oznaczonych jako CVE-2011-0655 i CVE-2011-0656.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Oprogramowanie serwerów firmy Microsoft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210206">MS11-023</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach pakietu Microsoft Office umożliwiają zdalne wykonanie</strong> <strong>kodu (2489293)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa jedną lukę zgłoszoną przez organizacje publiczne oraz jedną lukę zgłoszoną przez użytkowników. Istnieją one w pakiecie Microsoft Office. Luki umożliwiają zdalne wykonanie kodu, gdy użytkownik otworzy specjalnie spreparowany plik pakietu Office lub gdy otworzy prawidłowy plik pakietu Office znajdujący się w tym samym katalogu, co specjalnie spreparowany plik biblioteki. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać takie same uprawnienia, jak użytkownik zalogowany. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212226">MS11-024</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach aplikacji Edytor stron tytułowych faksu systemu Windows mogą pozwalać na zdalne wykonanie kodu (2527308)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach systemu Microsoft Windows, które zostały zgłoszone przez organizację publiczną. Luki te mogą umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik strony tytułowej faksu (.cov) za pomocą programu Edytor stron tytułowych faksu systemu Windows. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać takie same uprawnienia jak zalogowany użytkownik. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=209720">MS11-025</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach biblioteki Microsoft Foundation Class (MFC) Library umożliwia zdalne</strong> <strong>wykonanie kodu (2500212)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa zgłoszoną przez organizację publiczną lukę w zabezpieczeniach określonych aplikacji stworzonych przy użyciu biblioteki Microsoft Foundation Classes (MFC). Omawiana luka może pozwolić na zdalne wykonanie kodu, jeśli użytkownik otworzy prawidłowy plik skojarzony z zagrożoną aplikacją, który znajduje się w tym samym folderze sieciowym, co specjalnie spreparowany plik biblioteki. Aby atak mógł się powieść, użytkownik musi odwiedzić niezaufaną zdalną lokalizację systemu plików lub udział WebDAV i otworzyć dokument z tej lokalizacji, który następnie zostanie załadowany przez aplikację, której dotyczy luka.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Narzędzia i oprogramowanie firmy Microsoft dla deweloperów</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212523">MS11-026</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach protokołu MHTML umożliwia ujawnienie informacji (2503658)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach procedury obsługi protokołu MHTML w systemach Microsoft Windows. Luka może pozwolić na ujawnienie informacji, jeśli użytkownik odwiedzi specjalnie spreparowaną witrynę sieci Web. W przypadku ataku za pośrednictwem sieci Web witryna sieci Web mogłaby zawierać specjalnie spreparowane łącze służące do wykorzystania tej luki. Osoba atakująca musi przekonać użytkowników do jej odwiedzenia i kliknięcia specjalnie spreparowanego łącza.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Ujawnienie informacji</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208110">MS11-033</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach konwerterów tekstu programu WordPad może umożliwić zdalne wykonanie kodu (2485663)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „ważny” dla wszystkich obsługiwanych wersji systemów Windows XP i Windows Server 2003. Luka nie dotyczy wszystkich obsługiwanych wersji systemów Windows Vista, Windows Server 2008, Windows 7 i Windows Server 2008 R2.<br />
<br />
Luka ta może umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik za pomocą programu WordPad. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach sterowników trybu jądra systemu Windows umożliwiają podniesienie uprawnień (2506223)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa trzydzieści luk w zabezpieczeniach systemu Microsoft Windows, które zostały zgłoszone przez użytkowników. Luki te mogą umożliwić podniesienie uprawnień, jeśli osoba atakująca zaloguje się lokalnie i uruchomi specjalnie spreparowaną aplikację. Osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania oraz być w stanie zalogować się lokalnie, aby wykorzystać możliwości stwarzane przez luki. Nie jest możliwe wykorzystanie luk w sposób zdalny ani przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Wskaźnik możliwości wykorzystania luki  
--------------------------------------
  
<span></span>
Poniższa tabela przedstawia ocenę możliwości wykorzystania luk dla każdej luki opisywanej w tym miesiącu. Luki są wymienione według malejącego poziomu oceny możliwości wykorzystania, a nie według identyfikatora CVE. Uwzględniono wyłącznie te luki, które w biuletynach mają nadany wskaźnik ważności „krytyczny” lub „ważny”.
  
**W jaki** **sposób korzystać z tej tabeli?**
  
Tabela ta pozwala sprawdzić prawdopodobieństwo, że w ciągu 30 dni od wydania biuletynu zabezpieczeń dla każdej z aktualizacji zabezpieczeń, których zainstalowanie może być potrzebne, opublikowany zostanie działający kod wykorzystujący lukę w zabezpieczeniach. Aby ustalić priorytety wdrażania, zapoznaj się z dostępnymi poniżej ocenami, rozpatrując je w kontekście posiadanej konfiguracji. Więcej informacji na temat znaczenia tych ocen oraz sposobu ich dokonywania można znaleźć na stronie sieci Web [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

 
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Identyfikator biuletynu</th>
<th style="border:1px solid black;" >Nazwa luki w zabezpieczeniach</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >Ocena wskaźnika możliwości wykorzystania luki</th>
<th style="border:1px solid black;" >Najważniejsze uwagi</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=209720">MS11-025</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z niebezpiecznym ładowaniem biblioteki MFC</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3190">CVE-2010-3190</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207931">MS11-028</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach systemu .NET Framework związana z uszkodzeniem stosu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3958">CVE-2010-3958</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212224">MS11-032</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach czcionek OpenType związana z przepełnieniem stosu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0034">CVE-2011-0034</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208524">MS11-029</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach interfejsu GDI+ związana z przepełnieniem liczby całkowitej</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0041">CVE-2011-0041</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z uszkodzeniem pamięci obsługi układów</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0094">CVE-2011-0094</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;"><strong>Ta luka w zabezpieczeniach jest wykorzystywana</strong> <strong>w niewielkiej liczbie ukierunkowanych ataków</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z przepełnieniem liczby całkowitej</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0097">CVE-2011-0097</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z przepełnieniem stosu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0098">CVE-2011-0098</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z czcionkami WriteAV podczas analizy rekordów</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0101">CVE-2011-0101</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210206">MS11-023</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach składnika pakietu Office związana z niebezpiecznym ładowaniem bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0107">CVE-2011-0107</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z uszkodzeniem pamięci MSHTML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0346">CVE-2011-0346</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212314">MS11-019</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach klienta SMB związana z analizowaniem odpowiedzi</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0660">CVE-2011-0660</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212236">MS11-020</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z analizowaniem transakcji SMB</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0661">CVE-2011-0661</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0662">CVE-2011-0662</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0665">CVE-2011-0665</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0666">CVE-2011-0666</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0667">CVE-2011-0667</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0670">CVE-2011-0670</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0671">CVE-2011-0671</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0672">CVE-2011-0672</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0673">CVE-2011-0673</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0674">CVE-2011-0674</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0675">CVE-2011-0675</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0676">CVE-2011-0676</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0677">CVE-2011-0677</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach OfficeArt Atom umożliwiająca zdalne wykonanie kodu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0976">CVE-2011-0976</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z indeksowaniem tablic</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0978">CVE-2011-0978</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z uszkodzeniem połączonej listy</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0979">CVE-2011-0979</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z zawieszonym wskaźnikiem</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0980">CVE-2011-0980</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1225">CVE-2011-1225</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1226">CVE-2011-1226</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1227">CVE-2011-1227</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1228">CVE-2011-1228</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1229">CVE-2011-1229</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1230">CVE-2011-1230</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1231">CVE-2011-1231</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1232">CVE-2011-1232</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z odwołaniem odniesienia do pustego wskaźnika</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1233">CVE-2011-1233</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1235">CVE-2011-1235</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1236">CVE-2011-1236</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1237">CVE-2011-1237</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1239">CVE-2011-1239</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1240">CVE-2011-1240</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1241">CVE-2011-1241</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1242">CVE-2011-1242</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z uszkodzeniem pamięci zarządzania obiektami</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1345">CVE-2011-1345</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;"><strong>Ta luka w zabezpieczeniach jest wykorzystywana w niewielkiej</strong> <strong>liczbie ukierunkowanych ataków</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=208110">MS11-033</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach konwertera programu WordPad związana z analizowaniem</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0028">CVE-2011-0028</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z uszkodzeniem pamięci</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0103">CVE-2011-0103</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z zastąpieniem buforu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0104">CVE-2011-0104</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Excel związana z inicjalizacją danych</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0105">CVE-2011-0105</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212314">MS11-019</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach przeglądarki związana z uszkodzeniem puli</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0654">CVE-2011-0654</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach Techno-color Time Bandit związana z liczbami zmiennoprzecinkowymi i umożliwiająca zdalne wykonanie kodu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0655">CVE-2011-0655</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z pozostającym katalogiem i umożliwiająca zdalne wykonanie kodu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0656">CVE-2011-0656</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212595">MS11-030</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z kwerendami DNS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0657">CVE-2011-0657</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212243">MS11-031</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach obsługi skryptów związana z ponownym przydzielaniem pamięci</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0663">CVE-2011-0663</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=210206">MS11-023</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach pakietu Microsoft Office związana z odwołaniem odniesienia do obiektu graficznego</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0977">CVE-2011-0977</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1234">CVE-2011-1234</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> — prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212226">MS11-024</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z uszkodzeniem pamięci aplikacji Edytor stron tytułowych faksu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3974">CVE-2010-3974</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212226">MS11-024</a></td>
<td style="border:1px solid black;">Luka dotycząca strony tytułowej faksu związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4701">CVE-2010-4701</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212523">MS11-026</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach protokołu MHTML związana ze sposobem interpretowania żądań w formacie MIME</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0096">CVE-2011-0096</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie.<br />
<br />
Ta luka może doprowadzić do ujawnienia informacji.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach sterownika Win32k związana z użyciem po zwolnieniu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1238">CVE-2011-1238</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach skryptów Javascript umożliwiająca ujawnienie informacji</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1245">CVE-2011-1245</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> — działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Ta luka może doprowadzić do ujawnienia informacji.</td>
</tr>
</tbody>
</table>
  
Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki  
---------------------------------------------------------------------------------
  
<span></span>
Poniższe tabele wymieniają biuletyny według najważniejszych kategorii programów i wskaźnika ważności.
  
**Jak korzystać z tych tabel?**
  
Tabele te pozwalają odczytać informacje o aktualizacjach zabezpieczeń, których zainstalowanie może być konieczne. Należy zapoznać się z informacjami dotyczącymi każdego wymienionego programu lub składnika oprogramowania w celu sprawdzenia, czy aktualizacje zabezpieczeń odnoszą się do danej instalacji. Jeśli program lub składnik znajduje się na liście, dostępne jest łącze prowadzące do aktualizacji oprogramowania i podana jest informacja o wskaźniku ważności tej aktualizacji.
  
**Uwaga** Konieczne może być zainstalowanie kilku aktualizacji zabezpieczeń dotyczących jednej luki. Przejrzyj całą kolumnę dla każdego wymienionego identyfikatora biuletynu, aby sprawdzić, jakie aktualizacje musisz zainstalować, w oparciu o programy bądź składniki zainstalowane w systemie.
  
#### System operacyjny Windows i jego składniki:

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="14">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-018**](http://go.microsoft.com/fwlink/?linkid=214126)
</td>
<td style="border:1px solid black;">
[**MS11-019**](http://go.microsoft.com/fwlink/?linkid=212314)
</td>
<td style="border:1px solid black;">
[**MS11-020**](http://go.microsoft.com/fwlink/?linkid=212236)
</td>
<td style="border:1px solid black;">
[**MS11-027**](http://go.microsoft.com/fwlink/?linkid=214005)
</td>
<td style="border:1px solid black;">
[**MS11-028**](http://go.microsoft.com/fwlink/?linkid=207931)
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-030**](http://go.microsoft.com/fwlink/?linkid=212595)
</td>
<td style="border:1px solid black;">
[**MS11-031**](http://go.microsoft.com/fwlink/?linkid=212243)
</td>
<td style="border:1px solid black;">
[**MS11-032**](http://go.microsoft.com/fwlink/?linkid=212224)
</td>
<td style="border:1px solid black;">
[**MS11-024**](http://go.microsoft.com/fwlink/?linkid=212226)
</td>
<td style="border:1px solid black;">
[**MS11-026**](http://go.microsoft.com/fwlink/?linkid=212523)
</td>
<td style="border:1px solid black;">
[**MS11-033**](http://go.microsoft.com/fwlink/?linkid=208110)
</td>
<td style="border:1px solid black;">
[**MS11-034**](http://go.microsoft.com/fwlink/?linkid=211826)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=c3a8cec0-f947-4d4e-a6ae-c7f4f1f311b0)  
(Krytyczny)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0b7d0403-8965-4c62-970c-20b561f66713)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=689c5496-56c4-48a6-9f3d-b5f5aaf3e566)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f5378e7b-4619-4c42-9d9f-87b209c6d878)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ccb08a8a-f4d9-4320-8ffb-3fd4fe217987)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b031a496-aa74-4367-b2ae-24843c061745)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(Krytyczny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=59266a9d-a319-4309-a046-7f15c6da0136)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2d433adb-bcaf-4c59-9405-a4892f8ccba3)  
(Ważny)
</td>
<td style="border:1px solid black;">
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=637f4d4c-de07-4c6a-95f8-3bd0cbfe77b2)  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=fbe1e7e3-1d5f-4daf-a4a5-67fe79292963)  
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9080c5a1-e638-4047-a70a-9367f1acced7)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=50fc3869-f2fc-43c8-8049-aad62f2cb332)  
(KB2491683)  
(Ważny)  
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a8220a21-02fc-4ad6-988d-844276b2fd66)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7f0a4616-8e3e-4925-9d95-ce6e614e45ae)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6753ca98-feb4-4c7f-9969-9294038a2bbb)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=39e55bbf-c1c5-4696-bfe7-632e997cd98e)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=986f07ae-0fdc-4be2-8a74-5eb56d4300ef)  
(Krytyczny)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=ed88f183-dd06-46f6-ae8a-a594a752f248)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6d3433ee-c2e1-433f-a3d9-c049d66e2190)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c01441da-8933-4f60-923b-d9b00db8ba3d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7ee202da-a711-42ee-bea3-7202a70e4ea0)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eddd2964-9765-461d-9df8-2c05402948e8)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(Krytyczny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3797009a-b9a4-4e83-8614-e1589c8b5090)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=29ff546e-a232-4f23-a223-c029c71ff1c6)  
(Ważny)
</td>
<td style="border:1px solid black;">
[JScript 5.6 i VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=a5586246-2908-4def-9298-c16060098197)  
(KB2510587)  
(Krytyczny)  
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=3a5f65e0-bb00-4e55-b8b5-77751349a3ec)  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=57aa7ee2-254d-40b5-9ff0-cba969daf45a)  
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2374e09a-cb3e-4bc3-bb4b-53b611025121)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b93311b4-1b8f-478d-8833-750c5e01e6f8)  
(KB2491683)  
(Ważny)  
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f60fc99-cd88-4237-8b31-a4e618502f7e)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b01fe9a5-66a4-4683-963b-e78aea214579)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3c94bc96-99ea-44a1-9052-e69de5e21f81)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=83771177-284e-4918-86a9-980e8229c7c9)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-018**](http://go.microsoft.com/fwlink/?linkid=214126)
</td>
<td style="border:1px solid black;">
[**MS11-019**](http://go.microsoft.com/fwlink/?linkid=212314)
</td>
<td style="border:1px solid black;">
[**MS11-020**](http://go.microsoft.com/fwlink/?linkid=212236)
</td>
<td style="border:1px solid black;">
[**MS11-027**](http://go.microsoft.com/fwlink/?linkid=214005)
</td>
<td style="border:1px solid black;">
[**MS11-028**](http://go.microsoft.com/fwlink/?linkid=207931)
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-030**](http://go.microsoft.com/fwlink/?linkid=212595)
</td>
<td style="border:1px solid black;">
[**MS11-031**](http://go.microsoft.com/fwlink/?linkid=212243)
</td>
<td style="border:1px solid black;">
[**MS11-032**](http://go.microsoft.com/fwlink/?linkid=212224)
</td>
<td style="border:1px solid black;">
[**MS11-024**](http://go.microsoft.com/fwlink/?linkid=212226)
</td>
<td style="border:1px solid black;">
[**MS11-026**](http://go.microsoft.com/fwlink/?linkid=212523)
</td>
<td style="border:1px solid black;">
[**MS11-033**](http://go.microsoft.com/fwlink/?linkid=208110)
</td>
<td style="border:1px solid black;">
[**MS11-034**](http://go.microsoft.com/fwlink/?linkid=211826)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Niski**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b902c58a-9e2f-4352-8d2f-fffda5344598)  
(Umiarkowany)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5c464287-3dab-4342-a38d-a12719d3b158)  
(Umiarkowany)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=45feb35b-b24e-4160-adb0-d0b7ae530e90)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d46fe0bf-28c2-4696-87bc-dd3c8287fc28)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=64c550d4-c927-4382-91e1-473ed6790819)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=53756404-39e4-43af-81e9-81471536aa66)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(Krytyczny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fd284233-e177-4064-9b02-f83dcb727dbe)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=753ed6e3-df2e-4b2d-9e9f-7275cd94d214)  
(Ważny)
</td>
<td style="border:1px solid black;">
[JScript 5.6 i VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=e026f2ed-8a20-4268-9b29-04a78bde1999)  
(KB2510587)  
(Krytyczny)  
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=5b0ed0b2-07f9-43da-bb5d-5be5a45969ee)  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=01aa2beb-9fc1-40f0-a2a4-bcd3d9cb31f8)  
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5d71d3f5-fd6b-4f3b-8389-37c899748d4b)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=edda8cce-b764-4ef1-afbe-391fbd087362)  
(KB2491683)  
(Ważny)  
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bf084b4c-aac9-4cc6-bb30-87fc96ba9430)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0209a004-f23a-40d9-991f-864046f4605f)  
(Niski)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9fbfc742-6c74-49a2-b3cc-e1d5d8c84b77)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=af320f27-bb3a-4e76-a279-4632267c8761)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5d8f14d1-85cc-478f-8b50-5c355a331f59)  
(Umiarkowany)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9d8bbea9-c456-4569-ad96-c2cd0f5fae7e)  
(Umiarkowany)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=979d2ec5-5114-4ec7-aa97-e9289c590cbb)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ca0fb4d3-7651-4760-83fa-b71c86cbe459)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ef62db94-4f72-4245-ac9f-6391035e2516)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c8d59f49-45ec-4527-b3a8-4925f710bbfd)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(Krytyczny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d5adaf4e-4cd7-42ea-8202-31b5c856f5e3)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a0192dbc-4d0d-4555-9ef7-3e10209a6389)  
(Ważny)
</td>
<td style="border:1px solid black;">
[JScript 5.6 i VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=83ce6c99-a57d-4ed1-972b-a6b6798e6675)  
(KB2510587)  
(Krytyczny)  
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=af791715-77a1-405b-a69e-d63f75dd7ccd)  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=bf0a2966-25c4-4717-bcd6-016ce610d220)  
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3a498ff0-21d9-493a-b127-6bc20f1baf95)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f04d939a-da11-4a9f-9e03-b6c3bf3ca58b)  
(KB2491683)  
(Ważny)  
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=12b01f3a-ccf8-41c1-ac5a-e417a6ddbe95)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6c287571-54ea-4298-8b7d-b98b2c830cc3)  
(Niski)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=897b97b0-1bab-4b1b-b417-950fab0d4a65)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9c95f81c-9812-4070-88d7-34422c638e42)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=8afe86fc-58b4-4a95-b047-c09138fa4f5e)  
(Umiarkowany)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f1abfb48-3c8a-4b2d-b739-cc61628b387d)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=87eb8b93-9829-45ec-9528-52787732044e)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=79aeb3cd-7c73-467b-b91e-02c6ea01e911)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9c784734-f44f-4a3c-8223-6289f7dc2ad8)  
(Brak wskaźnika ważności<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(Krytyczny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=72a513bb-f901-4992-8562-d1afe1afec8a)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=f5ad6963-2d6a-4d59-9e25-4fc088647fcd)  
(Ważny)
</td>
<td style="border:1px solid black;">
[JScript 5.6 i VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=b7d36bae-7ca4-4a40-9efb-13f484fa5518)  
(KB2510587)  
(Krytyczny)  
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=3f519013-ed14-41a8-aa45-cf8b095d3152)  
(KB2510581)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c71f4398-2e3b-4b81-a650-8806e618db7f)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=efb575c7-3259-49b1-b59c-89d9544e37a6)  
(KB2491683)  
(Ważny)  
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=03a7ee49-7bd6-4215-9779-1b48c10d08b9)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3fb450a0-d087-4f36-9301-05ffbf94cc1a)  
(Niski)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ede38974-4e57-4ea1-8731-b91e96534693)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=f58cf64a-bf31-4496-be75-5775a123338b)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="14">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-018**](http://go.microsoft.com/fwlink/?linkid=214126)
</td>
<td style="border:1px solid black;">
[**MS11-019**](http://go.microsoft.com/fwlink/?linkid=212314)
</td>
<td style="border:1px solid black;">
[**MS11-020**](http://go.microsoft.com/fwlink/?linkid=212236)
</td>
<td style="border:1px solid black;">
[**MS11-027**](http://go.microsoft.com/fwlink/?linkid=214005)
</td>
<td style="border:1px solid black;">
[**MS11-028**](http://go.microsoft.com/fwlink/?linkid=207931)
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-030**](http://go.microsoft.com/fwlink/?linkid=212595)
</td>
<td style="border:1px solid black;">
[**MS11-031**](http://go.microsoft.com/fwlink/?linkid=212243)
</td>
<td style="border:1px solid black;">
[**MS11-032**](http://go.microsoft.com/fwlink/?linkid=212224)
</td>
<td style="border:1px solid black;">
[**MS11-024**](http://go.microsoft.com/fwlink/?linkid=212226)
</td>
<td style="border:1px solid black;">
[**MS11-026**](http://go.microsoft.com/fwlink/?linkid=212523)
</td>
<td style="border:1px solid black;">
[**MS11-033**](http://go.microsoft.com/fwlink/?linkid=208110)
</td>
<td style="border:1px solid black;">
[**MS11-034**](http://go.microsoft.com/fwlink/?linkid=211826)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=00c3c176-feff-4022-ac4c-2d4732ca3d78)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5ea94705-4f76-4b0d-bbbc-afb5e75204bf)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=da8dd55d-6630-484e-836c-9feeab5cc311)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6eddff4-a242-4dec-9d84-72891db2b754)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=80bf050a-9aff-4cd4-8e2f-196b0a92b1c0)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Tylko Windows Vista z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(Krytyczny)  
Tylko Windows Vista z dodatkiem Service Pack 2:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(Krytyczny)  
Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4ff2e440-79c2-4045-b225-913d1740fdb9)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2a17e44f-54aa-423d-b3c7-a4f404f7c28b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=719e2c86-30e5-4cd5-94f4-d6de54efee5f)  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=21decb84-75ef-4bde-a802-1e661a505e94)<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e7c4fc81-d1ef-4378-862b-e955d75fb2de)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=11a8f240-51b3-4e31-a24a-a235179f3396)  
(KB2491683)  
(Ważny)  
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e6cba040-9d7c-4777-a2f7-e4dd11dfb845)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c8fce0fb-4c90-479b-8ce9-75e60d52d256)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b4743167-9614-445a-9e91-10efdac505a8)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=79f52733-44e4-47b6-86ca-1395a095b4e7)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bc63b233-9db0-4fb1-a61c-fa7e9e44ba10)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=040f8b46-f458-4a72-a1b0-ad8a65a1194c)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2878c587-6544-40b4-9288-fc3b3ce1128d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a81412d0-2516-4bf4-87f7-3e41ebf6b82b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Tylko Windows Vista x64 Edition z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(Krytyczny)  
Tylko Windows Vista x64 Edition z dodatkiem Service Pack 2:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(Krytyczny)  
Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4d826026-e62a-4cec-8682-49fbe7f65cd6)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e708d24f-e348-4c4d-99ed-e78dd1689d01)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=89b9d01e-bcbc-4f2c-973b-51051494f406)  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=d4ac199e-7bf8-4661-a4e5-c53719b2673a)<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8d654a78-0e4f-452c-8874-fbf478813857)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=61db662e-88d7-4454-b4b7-e987728fb137)  
(KB2491683)  
(Ważny)  
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1c942282-0f80-46c1-aeef-1ef948e105a3)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7da10b64-d0a9-4e42-aa3a-87c657122a8c)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7e410d5c-b9f7-4a63-8300-36b2d57c6128)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-018**](http://go.microsoft.com/fwlink/?linkid=214126)
</td>
<td style="border:1px solid black;">
[**MS11-019**](http://go.microsoft.com/fwlink/?linkid=212314)
</td>
<td style="border:1px solid black;">
[**MS11-020**](http://go.microsoft.com/fwlink/?linkid=212236)
</td>
<td style="border:1px solid black;">
[**MS11-027**](http://go.microsoft.com/fwlink/?linkid=214005)
</td>
<td style="border:1px solid black;">
[**MS11-028**](http://go.microsoft.com/fwlink/?linkid=207931)
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-030**](http://go.microsoft.com/fwlink/?linkid=212595)
</td>
<td style="border:1px solid black;">
[**MS11-031**](http://go.microsoft.com/fwlink/?linkid=212243)
</td>
<td style="border:1px solid black;">
[**MS11-032**](http://go.microsoft.com/fwlink/?linkid=212224)
</td>
<td style="border:1px solid black;">
[**MS11-024**](http://go.microsoft.com/fwlink/?linkid=212226)
</td>
<td style="border:1px solid black;">
[**MS11-026**](http://go.microsoft.com/fwlink/?linkid=212523)
</td>
<td style="border:1px solid black;">
[**MS11-033**](http://go.microsoft.com/fwlink/?linkid=208110)
</td>
<td style="border:1px solid black;">
[**MS11-034**](http://go.microsoft.com/fwlink/?linkid=211826)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Niski**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7d8603b8-bb52-4cf6-be8b-bb3475d30fc5)\*\*  
(Umiarkowany)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d5d76e90-1cef-47e8-9d8d-2c5a43f42ba3)\*\*  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=f8c9390a-5ca1-492a-9e35-a516de48deb5)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=31c48ba9-7774-4633-862d-5c27c3703584)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=c3247886-76d0-4292-be9d-3e9b0221c46a)\*\*  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
Tylko Windows Server 2008 dla systemów 32-bitowych:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)\*\*  
(KB2449741)  
(Krytyczny)  
Tylko Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)\*\*  
(KB2449742)  
(Krytyczny)  
Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*\*<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=fbada866-7d36-4b85-acde-fd856a998737)\*\*\*  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=9894be38-a582-4c15-ad0e-cc3afab2aebc)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=d8b33ffd-eff1-4a10-b6fc-3c8f01e0fec5)\*\*  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=afd128ff-717f-4d98-b214-f2c28d59623d)\*\*<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=9105377e-83c7-4010-8fd6-26e42e98c2cc)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=90f56368-776b-4d45-ad68-91afbd316d25)\*\*  
(KB2491683)  
(Ważny)  
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=fa972742-1166-4a9e-ab64-6a4f968f9c6d)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=036f1285-7484-4e3b-8799-2c6c08166596)\*\*  
(Niski)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=c6ac26b8-8cc8-40fe-baab-22bf13df1aa8)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c6d58f64-bdd5-4fe6-96f4-9641b8e7b570)\*\*  
(Umiarkowany)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=51203a31-368b-4b47-96a5-9e9e5a55cd76)\*\*  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=b0cfd5e0-6de5-4863-b5e4-b223a0e36d72)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=de843115-cf98-4511-aa93-f620e4572555)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=51521b6b-94a7-4bcf-ad5f-fc304728b10f)\*\*  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
Tylko Windows Server 2008 dla systemów opartych na procesorach x64:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)\*\*  
(KB2449741)  
(Krytyczny)  
Tylko Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)\*\*  
(KB2449742)  
(Krytyczny)  
Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*\*<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów opartych na procesorze x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów opartych na procesorze x64](http://www.microsoft.com/downloads/details.aspx?familyid=8f4ddfcb-374d-4cad-8c61-2b988b46f628)\*\*\*  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=2d7d2021-020f-4cc9-a027-258d7e5faec9)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=6c2e6b87-afcd-461a-8a43-9a2fb277b18a)\*\*  
(KB2510581)  
(Krytyczny)  
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=40e8beca-0b5a-43b0-98f8-b32a82ad65d6)\*\*<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=060e8b20-edca-4427-9d60-eb57261eb668)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=22a001fc-5c2e-4539-85c9-0c2054a1777d)\*\*  
(KB2491683)  
(Ważny)  
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=fc250c8a-ebaf-4264-9393-dc23cc372d9f)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=1438cec8-8dab-4510-ad75-dc6959dac0d8)\*\*  
(Niski)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=ac49f5d3-5e2f-4916-99be-a3254278da7e)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f6f6f22c-fc7f-4e96-b6b5-be3c1acecf6e)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=8eaf51cd-2f6e-4bbc-bc4f-9deed03649ac)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b89b8e28-cd98-4bcc-8729-5e51d52d1e92)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e7c38b0d-7240-420a-88d3-2749a40e386f)  
(Brak wskaźnika ważności<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
Tylko Windows Server 2008 dla systemów z procesorem Itanium:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(Krytyczny)  
Tylko Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(Krytyczny)  
Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2fd71543-0e18-4907-89b9-355d24d7db69)  
(KB2412687)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c0275df0-10ac-4500-ab86-b7e9a34f8e1d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.7 i VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=afb49d24-1913-4e5f-a3ea-c6c9642e2017)  
(KB2510581)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2b8571cb-2dae-4bff-9f13-feb89840044c)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=421024f1-aa86-459e-b6de-53851a3fcba2)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=f35ecdd1-6b5c-40e7-a00b-ca083bdf5cba)  
(Niski)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3b93de4f-01f4-4efd-afc1-31d87b92fad2)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-018**](http://go.microsoft.com/fwlink/?linkid=214126)
</td>
<td style="border:1px solid black;">
[**MS11-019**](http://go.microsoft.com/fwlink/?linkid=212314)
</td>
<td style="border:1px solid black;">
[**MS11-020**](http://go.microsoft.com/fwlink/?linkid=212236)
</td>
<td style="border:1px solid black;">
[**MS11-027**](http://go.microsoft.com/fwlink/?linkid=214005)
</td>
<td style="border:1px solid black;">
[**MS11-028**](http://go.microsoft.com/fwlink/?linkid=207931)
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-030**](http://go.microsoft.com/fwlink/?linkid=212595)
</td>
<td style="border:1px solid black;">
[**MS11-031**](http://go.microsoft.com/fwlink/?linkid=212243)
</td>
<td style="border:1px solid black;">
[**MS11-032**](http://go.microsoft.com/fwlink/?linkid=212224)
</td>
<td style="border:1px solid black;">
[**MS11-024**](http://go.microsoft.com/fwlink/?linkid=212226)
</td>
<td style="border:1px solid black;">
[**MS11-026**](http://go.microsoft.com/fwlink/?linkid=212523)
</td>
<td style="border:1px solid black;">
[**MS11-033**](http://go.microsoft.com/fwlink/?linkid=208110)
</td>
<td style="border:1px solid black;">
[**MS11-034**](http://go.microsoft.com/fwlink/?linkid=211826)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=59676b71-8b9d-4230-a9e0-b20db3e3ec7e)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=0dcba089-19f7-46ca-9e52-24eaebad4715)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=d3ef905b-3584-4842-9ec2-cf3856305d49)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=46510959-e4a2-4c21-b33c-fd3d97b3ac3d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Windows 7 dla systemów 32-bitowych:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(Krytyczny)  
Tylko Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(Krytyczny)  
Windows 7 dla systemów 32-bitowych i Windows 7 dla systemów 32-bitowych z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=8fdae09b-d1bb-4ef5-aa45-2a05f2a5e12d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=17ebf291-fdae-4e78-9377-871b3103ce16)<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=751c45ea-0943-4948-807f-8716c6ff9198)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=bf762b86-b949-4e84-8ca4-93ebe669c1b8)  
(KB2491683)  
(Ważny)  
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=0f5a122e-dd5e-4b08-881a-f13b38642720)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=aed201c1-f1fb-4df9-8875-6f57ea0eb15b)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych i Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=6e7ff003-ff3f-49bb-8e45-d869885dd8d7)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3a998678-2678-489e-8711-39322663147d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=b7fd356a-56d0-4638-8901-40acfa600f25)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=7ddc943b-6868-4e8f-a869-89b47133c287)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=432555cf-aed8-4329-a74f-526441521082)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Windows 7 dla systemów z procesorem x64:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(Krytyczny)  
Tylko Windows 7 z dla systemów z procesorem x64 z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(Krytyczny)  
Windows 7 dla systemów opartych na procesorach x64 i Windows 7 dla systemów opartych na procesorach x64 z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=40879dfb-efa4-41ba-8d5c-22e926a55eef)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=c95ad86d-da58-4d7a-9ffd-8441f92baaa5)<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=976c882a-bc07-4128-927f-82a2df46cf45)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=a6793ecf-a3f6-4989-8e4c-c5c0005f9ac4)  
(KB2491683)  
(Ważny)  
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=658301f1-103a-48a2-9b67-61cf8e1dad50)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=1a32bf04-7eed-4d27-a8e4-054b4a5b76cb)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów opartych na procesorach x64 i Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=0c0aef7e-501c-4ca3-ae7f-497a8c169121)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="14">
System Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-018**](http://go.microsoft.com/fwlink/?linkid=214126)
</td>
<td style="border:1px solid black;">
[**MS11-019**](http://go.microsoft.com/fwlink/?linkid=212314)
</td>
<td style="border:1px solid black;">
[**MS11-020**](http://go.microsoft.com/fwlink/?linkid=212236)
</td>
<td style="border:1px solid black;">
[**MS11-027**](http://go.microsoft.com/fwlink/?linkid=214005)
</td>
<td style="border:1px solid black;">
[**MS11-028**](http://go.microsoft.com/fwlink/?linkid=207931)
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-030**](http://go.microsoft.com/fwlink/?linkid=212595)
</td>
<td style="border:1px solid black;">
[**MS11-031**](http://go.microsoft.com/fwlink/?linkid=212243)
</td>
<td style="border:1px solid black;">
[**MS11-032**](http://go.microsoft.com/fwlink/?linkid=212224)
</td>
<td style="border:1px solid black;">
[**MS11-024**](http://go.microsoft.com/fwlink/?linkid=212226)
</td>
<td style="border:1px solid black;">
[**MS11-026**](http://go.microsoft.com/fwlink/?linkid=212523)
</td>
<td style="border:1px solid black;">
[**MS11-033**](http://go.microsoft.com/fwlink/?linkid=208110)
</td>
<td style="border:1px solid black;">
[**MS11-034**](http://go.microsoft.com/fwlink/?linkid=211826)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Niski**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c7b2482b-44bf-4c01-99d8-f93868659a24)\*\*  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=27a3847b-695b-4f60-aea5-86b0dbe68945)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=c4352802-9c5a-4c07-8303-3a4b78d3f954)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=e4fa8ed0-acb0-4864-be18-29a27f8501de)\*\*  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
Tylko Windows Server 2008 R2 dla systemów opartych na procesorach x64:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)\*  
(KB2446709)  
(Krytyczny)  
Tylko Windows Server 2008 R2 dla systemów opartych na procesorach x64:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)  
Tylko Windows Server 2008 R2 dla systemów opartych na procesorach x64 z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)\*  
(KB2446710)  
(Krytyczny)  
Tylko Windows Server 2008 R2 dla systemów opartych na procesorach x64 z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=2084c726-187e-41f9-9bea-da18f490d29e)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=aecc2c7a-285c-409d-be23-c5b4b5449496)\*\*<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=6f2a52cc-4833-448d-becc-2eac1a447410)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=465c0478-6a74-4b00-8608-938cc492549f)\*\*  
(KB2491683)  
(Ważny)  
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=4c5c3a0f-0672-49d0-bcbd-c7f40e11d092)\*  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=665faa7e-2368-4421-9dd5-ea6df2c79498)\*\*  
(Niski)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64 i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=2fc66224-45c6-4e8f-ad00-6a1ec30b4505)\*  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=af6db318-fbec-4286-a3a7-4081620146e5)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1e7d3f21-bdbd-4826-855d-85422aa5f836)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=0005377b-443f-44ca-a890-620b2dcea6f1)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d7bcf4d7-b697-4c5f-adbc-a2b3700e0ad5)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
Tylko Windows Server 2008 R2 dla systemów z procesorem Itanium:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(Krytyczny)  
Tylko Windows Server 2008 R2 dla systemów z procesorem Itanium z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(Krytyczny)  
Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=34d2793e-a2cd-49f6-b524-6598ea86175f)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[JScript 5.8 i VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=e1bc0ed8-5a93-4d01-b407-919dfd894b5f)<sup>[1]</sup>
(KB2510531)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c6ca0b7c-8151-4d54-aa9b-5ec2b75d8ab6)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1a993f8c-d28a-4a95-a3c6-059f06e75461)  
(KB2506212)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=140ea384-2877-401f-ac3b-f84f6966e970)  
(Niski)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium i Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=485ccf96-27a0-499e-9f52-2836b73d26d2)  
(Ważny)
</td>
</tr>
</table>
 
**Uwagi dotyczące systemu Windows Server 2008 i Windows Server 2008 R2**

**\*Luka w zabezpieczeniach dotyczy instalacji Server Core.** Ta aktualizacja ma zastosowanie, z takim samym wskaźnikiem ważności, w przypadku obsługiwanych wersji systemu Windows Server 2008 lub Windows Server 2008 R2, niezależnie od tego, czy zostały zainstalowane przy użyciu opcji instalacji Server Core. Więcej informacji na temat tej opcji instalacji można znaleźć w artykułach TechNet, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) i [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (jęz. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core.** Luki usuwane przez tę aktualizację zabezpieczeń nie dotyczą obsługiwanych wersji systemu Windows Server 2008 ani Windows Server 2008 R2, jeżeli systemy te zostały zainstalowane przy użyciu opcji instalacji Server Core. Więcej informacji na temat tej opcji instalacji można znaleźć w artykułach TechNet, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) i [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (jęz. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core.** Luki usuwane przez tę aktualizację zabezpieczeń nie dotyczą obsługiwanych wersji systemu Windows Server 2008 lub Windows Server 2008 R2, jeśli zostały one zainstalowane przy użyciu opcji instalacji Server Core, mimo że na komputerze mogą znajdować się pliki, których dotyczy omawiana luka. Aktualizacja ta będzie jednak w dalszym ciągu oferowana użytkownikom posiadającym pliki podlegające luce, ponieważ zaktualizowane pliki są nowsze (mają wyższe numery wersji) niż pliki znajdujące się obecnie w systemie. Więcej informacji na temat tej opcji instalacji można znaleźć w artykułach TechNet, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) i [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (jęz. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Uwaga dotycząca biuletynu MS11-027**

<sup>[1]</sup>Luki w zabezpieczeniach, które opisano w niniejszym biuletynie, nie dotyczą tego konkretnego systemu operacyjnego. Dostępna aktualizacja ustawia bity „zabicia” dla formantów innych firm.

**Uwaga dotycząca biuletynu MS11-028**

<sup>[1]</sup>**Dotyczy systemu .NET Framework 4.0 i .NET Framework 4.0 Client Profile.** Pakiety redystrybucyjne systemu .NET Framework w wersji 4 są dostępne w dwóch profilach: .NET Framework 4.0 i .NET Framework 4.0 Client Profile. .NET Framework 4.0 Client Profile to podzbiór wersji .NET Framework 4.0. Luka w zabezpieczeniach usuwana przez tę aktualizację dotyczy zarówno wersji .NET Framework 4.0, jak i .NET Framework 4.0 Client Profile. Aby uzyskać więcej informacji, zobacz artykuł: [Instalowanie systemu .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx) (j. ang.)

**Uwaga dotycząca biuletynu MS11-029**

Zobacz także pozostałe kategorie oprogramowania w sekcji **Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

**Uwaga dotycząca biuletynu MS11-031**

<sup>[1]</sup>Problem nie dotyczy systemów z zainstalowanym programem Internet Explorer 9 i nie wymagają one tej aktualizacji. Systemy, których nie uaktualniono przy użyciu programu Internet Explorer 9, będą wymagać odpowiedniej aktualizacji zainstalowanych w nich aparatów obsługi skryptów JScript i VBScript. Instrukcje dotyczące ustalania wersji aparatów obsługi skryptów JScript i VBScript zainstalowanych w systemie znajdują się w biuletynie.

**Uwaga dotycząca biuletynu MS11-024**

Jeśli dla jednego systemu operacyjnego są dostępne dwie aktualizacje, należy zainstalować obie.

#### Pakiety i oprogramowanie Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="5">
Pakiety Microsoft Office i ich składniki
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-021**](http://go.microsoft.com/fwlink/?linkid=210121)
</td>
<td style="border:1px solid black;">
[**MS11-022**](http://go.microsoft.com/fwlink/?linkid=210727)
</td>
<td style="border:1px solid black;">
[**MS11-023**](http://go.microsoft.com/fwlink/?linkid=210206)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik** **ważności**
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d)  
(KB2509461)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2002 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=db2c5cfe-588c-4646-b86a-3fb8248f7af4)  
(KB2466169)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2002 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0d215ab6-c9be-4f43-9501-658bb7ef008e)  
(KB2464617)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d)  
(KB2509461)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=916a076d-d754-4092-b23d-c8826db7e397)  
(KB2502786)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2ce8349f-79b1-41ef-a1c0-cbe40ccf9f20)  
(KB2464588)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8b68cf68-1606-4649-b860-a64702c6cf33)  
(KB2509503)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5ae34fe0-03bd-48a9-a7ac-de8f7b1aff90)<sup>[1]</sup>
(KB2464583)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6b2526fe-a061-4a17-992e-ac867bef130e)  
(KB2464594)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dbba0cd4-ab72-4e2b-9524-fd6be27f0b02)  
(KB2509488)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (wersje 32-bitowe)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (wersje 32-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=a427f0e2-b74d-4ef3-bec4-0a101d09bfa3)  
(KB2466146)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (wersje 32-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=549ca7f0-44bf-4965-a9d2-aa5e8dac2238)  
(KB2519975)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (wersje 64-bitowe)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (wersje 64-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=13dca35d-2209-4c5c-9150-d6db2bb3b496)  
(KB2466146)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (wersje 64-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=ef62deae-2b07-41c9-a4bf-b746566e59ee)  
(KB2519975)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<th colspan="5">
Microsoft Office dla komputerów Macintosh
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-021**](http://go.microsoft.com/fwlink/?linkid=210121)
</td>
<td style="border:1px solid black;">
[**MS11-022**](http://go.microsoft.com/fwlink/?linkid=210727)
</td>
<td style="border:1px solid black;">
[**MS11-023**](http://go.microsoft.com/fwlink/?linkid=210206)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 dla komputerów Macintosh
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 dla komputerów Macintosh
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2011 dla komputerów Macintosh
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Office 2011 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3)  
(KB2525412)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2011 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3)  
(KB2525412)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="5">
Inne programy pakietu Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-029**](http://go.microsoft.com/fwlink/?linkid=208524)
</td>
<td style="border:1px solid black;">
[**MS11-021**](http://go.microsoft.com/fwlink/?linkid=210121)
</td>
<td style="border:1px solid black;">
[**MS11-022**](http://go.microsoft.com/fwlink/?linkid=210727)
</td>
<td style="border:1px solid black;">
[**MS11-023**](http://go.microsoft.com/fwlink/?linkid=210206)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Przeglądarka programu Microsoft Excel z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Przeglądarka programu Microsoft Excel z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2d75786a-2368-4ef2-970b-fa2e57d63ca9)  
(KB2466158)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Podgląd programu Microsoft PowerPoint 2007 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Podgląd programu Microsoft PowerPoint 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e23d3c3-2944-42ea-80b3-0663af60d0f1)  
(KB2464623)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Podgląd programu Microsoft PowerPoint
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Podgląd programu Microsoft PowerPoint](http://www.microsoft.com/downloads/details.aspx?familyid=44a703f5-b581-4900-bdbb-0f0e8d9bf0e6)  
(KB2519984)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pakiet zgodności formatu plików pakietu Microsoft Office dla programów Word, Excel i PowerPoint 2007 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Pakiet zgodności formatu plików pakietu Microsoft Office dla programów Word, Excel i PowerPoint 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=946cc611-4d75-4728-b9d3-1c8b557b02c2)  
(KB2466156)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Pakiet zgodności formatu plików pakietu Microsoft Office dla programów Word, Excel i PowerPoint 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=913efc28-7deb-47b8-8c22-8eb5fc2631e4)  
(KB2464635)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
</table>
 
**Uwaga dotycząca biuletynu MS11-029**

Zobacz także pozostałe kategorie oprogramowania w sekcji **Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

**Uwaga dotycząca biuletynu MS11-021**

<sup>[1]</sup>Aby uchronić się przed działaniem luk opisanych w niniejszym biuletynie, użytkownicy programu Microsoft Excel 2007 z dodatkiem Service Pack 2 poza pakietem aktualizacji zabezpieczeń KB2464583 muszą zainstalować także aktualizację zabezpieczeń Pakietu zgodności formatu plików pakietu Microsoft Office dla programów Word, Excel i PowerPoint 2007 z dodatkiem Service Pack 2 (KB2466156).

**Uwaga dotycząca biuletynu MS11-022**

Zobacz także pozostałe kategorie oprogramowania w sekcji **Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

#### Oprogramowanie serwerów firmy Microsoft

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-022**](http://go.microsoft.com/fwlink/?linkid=210727)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Web App](http://www.microsoft.com/downloads/details.aspx?familyid=9847dc05-7d4a-4a64-9e6a-622d3fa171f9)  
(KB2520047)  
(Ważny)
</td>
</tr>
</table>
 
**Uwaga dotycząca biuletynu MS11-022**

Zobacz także pozostałe kategorie oprogramowania w sekcji **Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

#### Narzędzia i oprogramowanie firmy Microsoft dla deweloperów

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS11-025**](http://go.microsoft.com/fwlink/?linkid=209720)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e9501082-a651-452b-8c1a-43987ffd3102)  
(KB2465373)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ee64d83b-6c06-4ccf-b12d-99e2a7a7b18d)  
(KB2538218)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e6a8e024-12ee-43d5-9aae-4c721505d6df)  
(KB2538241)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010 i Microsoft Visual Studio 2010 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](http://www.microsoft.com/downloads/details.aspx?familyid=7fd643a8-8e05-4d27-8853-33f79f01cb26)  
(KB2542054)  
(Ważny)  
[Microsoft Visual Studio 2010 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1a21c9db-dfa3-4a07-a1e0-89a8069b7c17)  
(KB2565057)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Pakiet redystrybucyjny programu Microsoft Visual C++ 2005 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae2e1a40-7b45-4fe9-a20f-2ed2923aca62)  
(KB2538242)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Pakiet redystrybucyjny programu Microsoft Visual C++ 2008 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a821847e-4c44-45c0-9128-61c822bb3280)  
(KB2538243)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2010 i Microsoft Visual C++ 2010 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Pakiet redystrybucyjny programu Microsoft Visual C++ 2010](http://www.microsoft.com/downloads/details.aspx?familyid=fe558aed-9274-415f-8a0f-d9d8622fb35b)  
(KB2467173)  
(Ważny)  
[Pakiet redystrybucyjny programu Microsoft Visual C++ 2010 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7557d29b-731b-4abb-8815-2b87a4132efb)  
(KB2565063)  
(Ważny)
</td>
</tr>
</table>
 

Narzędzia wykrywania i wdrażania oraz wskazówki
-----------------------------------------------

<span></span>
**Centrum zabezpieczeń**

Zarządzanie oprogramowaniem oraz aktualizacjami zabezpieczeń, które należy zainstalować na serwerach oraz komputerach stacjonarnych i przenośnych w organizacji. Więcej informacji można znaleźć w [Centrum TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Witryna [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) zawiera dodatkowe informacje na temat zabezpieczeń w produktach firmy Microsoft. Użytkownicy mogą także uzyskać dostęp do tych informacji w witrynie [Bezpieczeństwo w domu](http://go.microsoft.com/fwlink/?linkid=85102), klikając łącze „Najnowsze aktualizacje zabezpieczeń”.

Aktualizacje zabezpieczeń dostępne są w witrynach [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) i [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizacje zabezpieczeń są także dostępne w witrynie [Centrum pobierania Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.

Użytkownicy pakietu Microsoft Office dla komputerów Macintosh mogą skorzystać z funkcji automatycznej aktualizacji firmy Microsoft, aby zapewnić aktualność posiadanego oprogramowania firmy Microsoft. Więcej informacji na temat korzystania z funkcji automatycznych aktualizacji dla komputerów Macintosh można znaleźć w artykule [Automatyczne sprawdzanie aktualizacji oprogramowania](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Aktualizacje zabezpieczeń można także pobierać z [Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=96155). Wykaz usługi Microsoft Update zawiera katalog zawartości z możliwością przeszukiwania, który udostępniany jest poprzez usługi Windows Update i Microsoft Update i obejmuje aktualizacje zabezpieczeń, sterowniki i dodatki Service Pack. Wyszukiwanie przy użyciu numeru biuletynu zabezpieczeń (np. „MS07-036”) pozwala dodać do koszyka wszystkie odpowiednie aktualizacje (w tym różne wersje językowe aktualizacji) i pobrać pliki do wybranego folderu. Więcej informacji na temat Wykazu usługi Microsoft Update można znaleźć w [Często zadawanych pytaniach dotyczących Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=97900).

**Porady dotyczące wykrywania i wdrażania**

Firma Microsoft udziela porad dotyczących wykrywania i wdrażania aktualizacji zabezpieczeń. Porady takie zawierają zalecenia i informacje ułatwiające specjalistom IT poznanie obsługi różnych narzędzi do wykrywania i wdrażania aktualizacji zabezpieczeń. Więcej informacji na ten temat można znaleźć w [artykule 961747 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Narzędzie Microsoft Baseline Security Analyzer (MBSA)**

Narzędzie Microsoft Baseline Security Analyzer umożliwia administratorom skanowanie lokalnych i zdalnych systemów w poszukiwaniu brakujących aktualizacji zabezpieczeń oraz typowych błędów konfiguracji zabezpieczeń. Więcej informacji na temat narzędzia MBSA można znaleźć w witrynie sieci Web [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Korzystając z programu Windows Server Update Services (WSUS), administratorzy mogą szybko i niezawodnie wdrożyć najnowsze aktualizacje krytyczne i aktualizacje zabezpieczeń przeznaczone dla systemów operacyjnych Microsoft Windows 2000 i nowszych, pakietów Office XP i nowszych, programu Exchange Server 2003 oraz SQL Server 2000 w systemach operacyjnych Microsoft Windows 2000 i nowszych.

Więcej informacji na temat sposobu wdrażania tej aktualizacji zabezpieczeń za pomocą programu Windows Server Update Services można znaleźć w [witrynie sieci Web programu Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**System Center Configuration Manager 2007**

Program Configuration Manager 2007 Software Update Management ułatwia realizację złożonych zadań dostarczania aktualizacji do systemów IT w firmie i zarządzania nimi. Dzięki programowi Configuration Manager 2007 administratorzy mogą dostarczać aktualizacje produktów firmy Microsoft do całej gamy urządzeń, takich jak komputery stacjonarne, laptopy, serwery i urządzenia mobilne.

System zautomatyzowanej oceny zagrożeń w programie Configuration Manager 2007 wykrywa potrzebne aktualizacje i sporządza raporty dotyczące zalecanych czynności. Funkcja Software Update Management w programie Configuration Manager 2007 powstała w oparciu o usługi Microsoft Windows Software Update Services (WSUS) — dobrze sprawdzoną infrastrukturę aktualizacji znaną administratorom na całym świecie. Więcej informacji na temat możliwości wykorzystania przez administratorów programu Configuration Manager 2007 do wdrażania aktualizacji zawiera dokument [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Więcej informacji dotyczących programu Configuration Manager znajduje się na stronie [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Program Systems Management Server (SMS) jest przeznaczonym dla przedsiębiorstw i w znacznym stopniu konfigurowalnym rozwiązaniem służącym do zarządzania aktualizacjami. Program SMS umożliwia administratorom znalezienie komputerów z systemem Windows, na których należy zainstalować aktualizację zabezpieczeń, a także przeprowadzić kontrolowane wdrożenie tych aktualizacji w całym przedsiębiorstwie, w minimalnym stopniu zakłócając przy tym pracę użytkowników końcowych.

**Uwaga** Program System Management Server 2003 od 12 stycznia 2010 roku nie jest objęty podstawową pomocą techniczną. Więcej informacji na temat cyklu pomocy technicznej dla produktów można znaleźć w witrynie zasad [cyklu pomocy technicznej firmy Microsoft](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Dostępne jest kolejne wydanie programu System Center Configuration Manager 2007 (SMS); zobacz wcześniejszą sekcję **System Center Configuration Manager 2007**.

Więcej informacji na temat możliwości wykorzystania przez administratorów programu SMS 2003 do wdrażania aktualizacji zabezpieczeń można znaleźć w artykule [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Więcej informacji na temat programu SMS można znaleźć w witrynie sieci Web [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Uwaga** Program SMS zapewnia obsługę rozwiązań zawartych w biuletynach zabezpieczeń dzięki narzędziu Microsoft Baseline Security Analyzer. Narzędzia te mogą nie wykrywać wszystkich aktualizacji oprogramowania. W takich przypadkach administratorzy mogą wykorzystywać dostępne w programie SMS funkcje zarządzania zasobami do przyporządkowania poszczególnych aktualizacji określonym systemom. Aby uzyskać więcej informacji dotyczących tej procedury, zobacz [Wdrażanie aktualizacji oprogramowania za pomocą funkcji Software Distribution programu SMS](http://go.microsoft.com/fwlink/?linkid=33341). Niektóre aktualizacje oprogramowania wymagają od użytkownika uprawnień administratora po ponownym uruchomieniu systemu. Do zainstalowania tych aktualizacji administratorzy mogą użyć narzędzia Elevated Rights Deployment Tool (dostępnego w dodatku [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

**Tester zgodności aktualizacji i zestaw narzędzi do sprawdzania zgodności aplikacji**

Często aktualizacje zapisują informacje w tych samych plikach i ustawieniach rejestru niezbędnych do działania określonych aplikacji użytkownika. Może to prowadzić do niezgodności i wydłużyć czas wdrażania aktualizacji zabezpieczeń. Dzięki składnikom narzędzia [Tester zgodności aplikacji](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) znajdującego się w [Zestawie narzędzi do sprawdzania zgodności aplikacji](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) można usprawnić proces testowania i sprawdzania poprawności aktualizacji systemu Windows.

W Zestawie narzędzi do sprawdzania zgodności aplikacji znajdują się niezbędne narzędzia i dokumentacja, które umożliwiają ocenę zgodności aplikacji przed wdrożeniem systemu Microsoft Windows Vista, aktualizacji dla systemu Windows, aktualizacji zabezpieczeń firmy Microsoft lub nowej wersji programu Windows Internet Explorer w środowisku użytkownika, oraz ograniczenie problemów ze zgodnością aplikacji.

### Inne informacje:

#### Narzędzie Microsoft Windows do usuwania złośliwego oprogramowania

Firma Microsoft opublikowała zaktualizowaną wersję narzędzia Microsoft Windows Malicious Software Removal Tool, która dostępna jest w witrynach sieci Web Windows Update i Microsoft Update, poprzez usługi Windows Server Update Services i w witrynie Centrum pobierania Microsoft.

#### Aktualizacje niezwiązane z zabezpieczeniami, dostępne w witrynach MU, WU oraz usługach WSUS

Aby uzyskać informacje na temat publikacji niezwiązanych z zabezpieczeniami, dostępnych w witrynach Windows Update i Microsoft Update, zobacz:

-   [Artykuł 894199 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Opis zmian zawartości Usług aktualizacji oprogramowania i usług Windows Server Update Services. Zawiera wszystkie treści dotyczące systemu Windows.
-   [Aktualizacje z poprzednich miesięcy dla usług Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Wyświetla nowe, zmienione i opublikowane ponownie aktualizacje dla produktów firmy Microsoft innych niż Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

W celu zwiększenia poziomu bezpieczeństwa swoich klientów firma Microsoft dostarcza informacje na temat luk w zabezpieczeniach największym dostawcom oprogramowania zabezpieczającego przed publikacją comiesięcznej aktualizacji zabezpieczeń. Dzięki informacjom dotyczącym luk w zabezpieczeniach dostawcy oprogramowania zabezpieczającego mogą zaoferować swoim klientom zaktualizowane poprawki za pośrednictwem programów lub urządzeń zabezpieczających np. programów antywirusowych, sieciowych systemów wykrywania włamań lub hostowych systemów zapobiegania włamaniom. Aby sprawdzić, czy dostawcy oprogramowania zabezpieczającego zapewniają aktywną ochronę, odwiedź witryny poszczególnych partnerów programu, których listę znaleźć można w sekcji [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201).

#### Strategie i społeczność związane z zabezpieczeniami

**Strategie zarządzania aktualizacjami**

Na stronie [Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (Wskazówki z zakresu bezpieczeństwa dotyczące zarządzania aktualizacjami) znajdują się dodatkowe informacje o zalecanych przez firmę Microsoft najlepszych sposobach stosowania aktualizacji zabezpieczeń.

**Uzyskiwanie innych aktualizacji zabezpieczeń**

Aktualizacje dotyczące innych problemów związanych z zabezpieczeniami można uzyskać w następujących lokalizacjach:

-   Aktualizacje zabezpieczeń są dostępne w witrynie [Centrum pobierania Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.
-   Aktualizacje dla poszczególnych platform są dostępne w [witrynie sieci Web Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizacje zabezpieczeń dostępne w tym miesiącu w witrynie Windows Update można otrzymać w witrynie Centrum pobierania Microsoft w postaci plików obrazu dysku CD zawierającego zabezpieczenia i aktualizacje krytyczne. Więcej informacji na ten temat można znaleźć w [artykule 913086 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Społeczność IT Pro Security Community**

Dowiedz się, jak poprawić bezpieczeństwo i zoptymalizować infrastrukturę informatyczną oraz weź udział w dyskusjach dotyczących zabezpieczeń wraz z innymi specjalistami z branży IT, odwiedzając witrynę sieci Web społeczności [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (jęz. ang.).

#### Podziękowania

Firma Microsoft [dziękuje](http://go.microsoft.com/fwlink/?linkid=21127) wymienionym poniżej organizacjom i osobom za współpracę w dziedzinie ochrony klientów:

-   Anonimowy analityk współpracujący z firmą [VeriSign iDefense Labs](http://labs.idefense.com/), za zgłoszenie problemu opisanego w biuletynie MS11-018
-   Firma [MITRE](http://mitre.org/) za współpracę przy rozwiązywaniu problemu opisanego w biuletynie MS11-018
-   Michał Zalewski z firmy [Google Inc.](http://www.google.com/), za współpracę przy rozwiązywaniu problemu opisanego w biuletynie MS11-018
-   David Bloom z firmy [Google Inc.](http://www.google.com/), za zgłoszenie dwóch problemów opisanych w biuletynie MS11-018
-   Stephen Fewer z firmy [Harmony Security](http://www.harmonysecurity.com/), współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS11-018
-   Alin Rad Pop z firmy [Secunia Research](http://secunia.com/) za zgłoszenie dwóch problemów opisanych w biuletynie MS11-021
-   Muhammad Junaid Bohio z firmy [Telus Security Labs](http://www.telussecuritylabs.com) za zgłoszenie problemu opisanego w biuletynie MS11-021
-   Aniway we współpracy z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/) za zgłoszenie trzech problemów opisanych w biuletynie MS11-021
-   Anonimowy analityk współpracujący z firmą [VeriSign iDefense Labs](http://labs.idefense.com/), za zgłoszenie problemu opisanego w biuletynie MS11-021
-   Rodrigo Rubira Branco z firmy [Check Point Vulnerability Discovery Team](http://www.checkpoint.com/) (VDT) za zgłoszenie problemu opisanego w biuletynie ms11-021
-   Anonimowy analityk współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/) za zgłoszenie problemu opisanego w biuletynie MS11-021
-   Anonimowy analityk współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/) za zgłoszenie problemu opisanego w biuletynie MS11-021
-   Oddział [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/) za zgłoszenie trzech problemów opisanych w biuletynie MS11-022
-   Haifei Li z [FortiGuard Labs firmy Fortinet](http://www.fortiguard.com/), za zgłoszenie problemu opisanego w biuletynie MS11-023
-   Anonimowy analityk współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/) za zgłoszenie problemu opisanego w biuletynie MS11-023
-   Carsten Eiram z firmy [Secunia](http://secunia.com/), za współpracę z firmą Microsoft przy rozwiązywaniu problemu opisanego w biuletynie MS11-024
-   Zespół [Google Security Team](http://www.google.com/), za współpracę z firmą Microsoft przy problemie opisanym w biuletynie MS11-026
-   Chris Ries z organizacji Carnegie Mellon University Information Security Office, za zgłoszenie problemu opisanego w biuletynie MS11-027
-   RadLSneak, współpracujący z firmą [iSIGHT Partners](http://www.isightpartners.com/) Global Vulnerability Partnership, za zgłoszenie problemu opisanego w biuletynie MS11-027
-   Nicolas Joly i Chaouki Bekrar z organizacji [VUPEN Threat Protection Program](http://www.vupen.com/english/services/tpp-index.php), za zgłoszenie problemu opisanego w biuletynie MS11-029
-   Neel Mehta z firmy [Google Inc.](http://www.google.com/), za zgłoszenie problemu opisanego w biuletynie MS11-030
-   [Jesse Ruderman](http://www.squarefree.com/) z firmy [Mozilla](http://www.mozilla.org/), za współpracę przy rozwiązywaniu problemu opisanego w biuletynie MS11-031
-   Adam Twardoch z firmy [Fontlab Ltd.](http://www.fontlab.com/), za zgłoszenie problemu opisanego w biuletynie MS11-032
-   Carsten Eiram z firmy [Secunia](http://secunia.com/), za zgłoszenie problemu opisanego w biuletynie MS11-033
-   Tarjei Mandt z firmy [Norman](http://www.norman.com/), za zgłoszenie 30 problemów opisanych w biuletynie MS11-034

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pod numerem 0 801 802 000 (opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne. Dodatkowe informacje dotyczące możliwości skorzystania z pomocy technicznej można znaleźć w witrynie [Pomoc i obsługa techniczna firmy Microsoft](http://support.microsoft.com/).
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (12 kwietnia 2011 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.
-   Wersja 1.1 (13 kwietnia 2011 r.): W przypadku biuletynu MS11-019 poprawiono opis luki w zabezpieczeniach w Streszczeniu.
-   Wersja 2.0 (15 kwietnia 2011 r.): W przypadku biuletynu MS11-032 podniesiono wskaźnik możliwości wykorzystania luki CVE-2011-0034 do poziomu „1 — prawdopodobne istnienie spójnego kodu wykorzystującego lukę”.
-   Wersja 3.0 (21 kwietnia 2011 r.): Zaktualizowano, aby udostępnić ponowne wydanie aktualizacji zabezpieczeń MS11-025.
-   Wer. 3.1 (27 kwietnia 2011 r.): W biuletynie MS11-024 poprawiono Wskaźnik możliwości wykorzystania luki, aby dodać lukę CVE-2010-4701 do wykazu luk, których dotyczy ta aktualizacja. Zmiana ta ma wyłącznie charakter informacyjny.
-   Wersja 4.0 (16 maja 2011 r.): Opublikowano biuletyn MS11-018, aby ponownie zaoferować aktualizację dla programu Internet Explorer 7 w obsługiwanych wersjach systemów Windows XP i Windows Server 2003. Zmiana objęła tylko wykrywanie. Nie wprowadzono żadnych zmian do plików binarnych. Aktualizacja będzie oferowana tylko tym użytkownikom, których dotyczy problem. Klienci, którzy zainstalowali aktualizację ręcznie, oraz posiadacze konfiguracji, których nie dotyczy zmiana w logice wykrywania nie muszą podejmować żadnych działań.
-   Wersja 5.0 (14 czerwca 2011 r.): W przypadku biuletynu MS11-025 ponownie zaoferowano aktualizacje programów Microsoft Visual Studio 2005 z dodatkiem Service Pack 1, Microsoft Visual Studio 2008 z dodatkiem Service Pack 1, Microsoft Visual Studio 2010, pakietu redystrybucyjnego programu Microsoft Visual C++ 2005 z dodatkiem Service Pack 1 oraz pakietu redystrybucyjnego programu Microsoft Visual C++ 2008 z dodatkiem Service Pack 1. Klienci, którzy wcześniej zainstalowali tę aktualizację, powinni zainstalować nowe pakiety w systemach zawierających lukę.
-   Wersja 6.0 (9 sierpnia 2011 r.): W biuletynie MS11-025 do listy oprogramowania, którego dotyczy problem, dodano program Microsoft Visual Studio 2010 z dodatkiem Service Pack 1 (KB2565057) oraz pakiet redystrybucyjny programu Microsoft Visual C++ 2010 z dodatkiem Service Pack 1 (KB2565063).
-   Wersja 6.1 (26 października 2011 r.): W biuletynie MS11-028 poprawiono zastosowanie instalacji Server Core dla oprogramowania .NET Framework 4 w systemie Windows Server 2008 R2 dla systemów opartych na procesorze x64.

*Built at 2014-04-18T01:50:00Z-07:00*
