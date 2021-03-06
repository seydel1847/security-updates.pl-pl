---
TOCTitle: 'MS09-SEP'
Title: 'Podsumowanie biuletynów zabezpieczeń firmy Microsoft za wrzesień 2009 r.'
ms:assetid: 'ms09-sep'
ms:contentKeyID: 61233107
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms09-sep(v=Security.10)'
---
Podsumowanie biuletynów zabezpieczeń firmy Microsoft za wrzesień 2009 r.
========================================================================

Opublikowano: 8 września 2009 | Zaktualizowano: 10 listopada 2009

**Wersja:** 3.0

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za wrzesień 2009 r.

Z chwilą opublikowania biuletynów za wrzesień 2009 r. niniejsze podsumowanie biuletynów zastępuje powiadomienie o biuletynach zabezpieczeń wydane 3 września 2009 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j. ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

9 września 2009 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępni emisję internetową, w której znajdą się odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). [Zarejestruj się, aby zobaczyć emisję internetową dotyczącą biuletynów zabezpieczeń za wrzesień](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407486&eventcategory=4&culture=en-us&countrycode=us). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

Firma Microsoft udostępnia także informacje, dzięki którym klienci mogą ustalić priorytety dla aktualizacji zabezpieczeń w związku z niezwiązanymi z zabezpieczeniami aktualizacjami o wysokim priorytecie, które publikowane są w tym samym dniu, co comiesięczne aktualizacje zabezpieczeń. Zapoznaj się z sekcją **Inne informacje**.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157304">MS09-045</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach aparatu skryptów JScript umożliwia zdalne wykonanie kodu (971961)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w zabezpieczeniach aparatu skryptów JScript umożliwiającą zdalne wykonanie kodu, gdy użytkownik otworzy specjalnie spreparowany plik lub odwiedzi specjalnie spreparowaną witrynę sieci Web i wywoła nieprawidłowy skrypt. Jeśli użytkownik jest zalogowany jako administrator, osoba atakująca, która pomyślnie wykorzysta tę lukę, może uzyskać pełną kontrolę nad systemem, którego ta luka dotyczy. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=151360">MS09-049</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach usługi Autokonfiguracja bezprzewodowej sieci LAN umożliwia zdalne wykonanie kodu (970710)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w zabezpieczeniach usługi Autokonfiguracja bezprzewodowej sieci LAN. Luka ta może umożliwić zdalne wykonanie kodu, jeśli klient lub serwer z włączonym interfejsem sieci bezprzewodowej odbierze specjalnie spreparowane ramki sieci bezprzewodowej. Systemy bez włączonej karty bezprzewodowej nie są zagrożone przez tą lukę.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158082">MS09-047</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach formatu Windows Media umożliwiają zdalne wykonanie kodu (973812)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach formatu Windows Media, które zostały zgłoszone przez użytkowników. Każda z tych luk umożliwia zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik multimedialny. Jeśli użytkownik jest zalogowany jako administrator, osoba atakująca, która pomyślnie wykorzysta tę lukę, może uzyskać pełną kontrolę nad systemem, którego ta luka dotyczy. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155978">MS09-048</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach interfejsu TCP/IP systemu Windows umożliwiają zdalne wykonanie kodu (967723)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa kilka zgłoszonych przez użytkowników luk w zabezpieczeniach przetwarzania protokołu TCP/IP (Transmission Control Protocol/Internet Protocol). Luki te umożliwiają zdalne wykonanie kodu, gdy osoba atakująca wyśle przez sieć specjalnie spreparowane pakiety TCP/IP do komputera z usługą nasłuchiwania. Sprawdzone metody działania stosowane w zaporach oraz standardowe domyślne konfiguracje zapór mogą pomóc w zabezpieczeniu sieci przed atakami spoza obszaru działania przedsiębiorstwa. Zgodnie ze standardowymi zasadami działania zaleca się, aby w systemach połączonych z Internetem była otwarta jak najmniejsza liczba portów.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158009">MS09-046</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach formantu ActiveX składnika edycji w formacie DHTML może umożliwić zdalne wykonanie kodu (956844)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach formantu ActiveX składnika edycji w formacie DHTML, która została zgłoszona przez użytkowników. Osoba atakująca może wykorzystać tę lukę poprzez utworzenie specjalnie spreparowanej strony sieci Web. Gdy użytkownik odwiedza taką stronę sieci Web, luka w zabezpieczeniach może pozwolić na zdalne wykonanie kodu. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak zalogowany użytkownik. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Wskaźnik możliwości wykorzystania luki  
--------------------------------------
  
<span></span>
Poniższa tabela przedstawia ocenę możliwości wykorzystania luk dla każdej luki opisywanej w tym miesiącu. Luki są wymienione wg identyfikatora biuletynu i identyfikatora CVE.
  
**W jaki sposób korzystać z tej tabeli?**
  
Tabela ta pozwala sprawdzić prawdopodobieństwo, że w ciągu 30 dni od wydania biuletynu zabezpieczeń dla każdej z aktualizacji zabezpieczeń, których zainstalowanie może być potrzebne, opublikowany zostanie działający kod wykorzystujący lukę w zabezpieczeniach. Aby ustalić priorytety wdrażania, zapoznaj się z dostępnymi poniżej ocenami, rozpatrując je w kontekście posiadanej konfiguracji. Więcej informacji na temat znaczenia tych ocen oraz sposobu ich wyznaczania można znaleźć na stronie sieci Web [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Identyfikator biuletynu                                   | Tytuł biuletynu                                                                                                          | CVE ID                                                                           | Ocena wskaźnika możliwości wykorzystania luki                                                                              | Najważniejsze uwagi                                                                                                        |  
|-----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|  
| [MS09-045](http://go.microsoft.com/fwlink/?linkid=157304) | Luka w zabezpieczeniach aparatu skryptów JScript umożliwia zdalne wykonanie kodu (971961)                                | [CVE-2009-1920](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1920) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                     |  
| [MS09-046](http://go.microsoft.com/fwlink/?linkid=158009) | Luka w zabezpieczeniach formantu ActiveX składnika edycji w formacie DHTML może umożliwić zdalne wykonanie kodu (956844) | [CVE-2009-2519](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2519) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                     |  
| [MS09-047](http://go.microsoft.com/fwlink/?linkid=158082) | Luki w zabezpieczeniach formatu Windows Media umożliwiają zdalne wykonanie kodu (973812)                                 | [CVE-2009-2498](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2498) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                     |  
| [MS09-047](http://go.microsoft.com/fwlink/?linkid=158082) | Luki w zabezpieczeniach formatu Windows Media umożliwiają zdalne wykonanie kodu (973812)                                 | [CVE-2009-2499](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2499) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                     |  
| [MS09-048](http://go.microsoft.com/fwlink/?linkid=155978) | Luki w zabezpieczeniach protokołu TCP/IP systemu Windows umożliwiają zdalne wykonanie kodu (967723)                      | [CVE-2008-4609](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4609) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — działający kod wykorzystujący lukę mało prawdopodobny | Jest to atak typu „odmowa usługi” powodujący wykorzystanie pamięci.                                                        |  
| [MS09-048](http://go.microsoft.com/fwlink/?linkid=155978) | Luki w zabezpieczeniach protokołu TCP/IP systemu Windows umożliwiają zdalne wykonanie kodu (967723)                      | [CVE-2009-1925](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1925) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny niespójny kod wykorzystujący lukę       | Istnieje możliwość powstania działającego kodu, ale jest to mało prawdopodobne. Bardziej prawdopodobna jest odmowa usługi. |  
| [MS09-048](http://go.microsoft.com/fwlink/?linkid=155978) | Luki w zabezpieczeniach protokołu TCP/IP systemu Windows umożliwiają zdalne wykonanie kodu (967723)                      | [CVE-2009-1926](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1926) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — działający kod wykorzystujący lukę mało prawdopodobny | Jest to atak typu „odmowa usługi” powodujący wykorzystanie pamięci.                                                        |  
| [MS09-049](http://go.microsoft.com/fwlink/?linkid=151360) | Luka w zabezpieczeniach usługi Autokonfiguracja bezprzewodowej sieci LAN umożliwia zdalne wykonanie kodu (970710)        | [CVE-2009-1132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1132) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny niespójny kod wykorzystujący lukę       | Zabezpieczenia stosu utrudniają niezawodne wykorzystanie tej luki w zabezpieczeniach.                                      |
  
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
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://go.microsoft.com/fwlink/?linkid=157304)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://go.microsoft.com/fwlink/?linkid=151360)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://go.microsoft.com/fwlink/?linkid=158082)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://go.microsoft.com/fwlink/?linkid=155978)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://go.microsoft.com/fwlink/?linkid=158009)
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
Brak
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 z dodatkiem Service Pack 4
</td>
<td style="border:1px solid black;">
[JScript 5.1 i JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=2bb3af8d-f36c-4497-9f48-fc59bcff2583)  
(KB971961)  
(Krytyczny)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=b2773db5-b17d-4b98-b4e2-219b23854abd)  
(KB975542)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=02b9dc42-38c2-44b1-a77c-34854f4a86c4)  
(KB968816)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 z dodatkiem Service Pack 4<sup>[3]</sup>
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=6dd4b0f8-6b54-49a6-a6df-9420f9fd3333)  
(Krytyczny)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://go.microsoft.com/fwlink/?linkid=157304)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://go.microsoft.com/fwlink/?linkid=151360)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://go.microsoft.com/fwlink/?linkid=158082)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://go.microsoft.com/fwlink/?linkid=155978)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://go.microsoft.com/fwlink/?linkid=158009)
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
Brak
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Niski**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[JScript 5.6 w systemie Windows XP z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0af373b2-2240-4079-a748-a38d1bc06f39)  
(KB971961)  
(Krytyczny)  
[JScript 5.7 w systemie Windows XP z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)<sup>[1]</sup>
(KB971961)  
(Krytyczny)  
[JScript 5.7 w systemie Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a)  
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=992602d8-d857-41cf-b7b1-527afdc1dc0f)<sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 i Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=6ffc081e-f892-4818-acb9-6d79e15d473c)  
(KB968816)  
(Krytyczny)  
(tylko system Windows XP z dodatkiem Service Pack 2)  
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 i Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=31585f5a-9aaa-40da-b15a-11284b4b800c)  
(KB968816)  
(Krytyczny)  
(tylko system Windows XP z dodatkiem Service Pack 3)
</td>
<td style="border:1px solid black;">
Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3<sup>[3]</sup>
(Niski)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8523d5be-88a2-4124-9b02-660f612e2a12)  
(Krytyczny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=0d671004-da4e-4dbd-a066-861b53b0c59c)  
(KB971961)  
(Krytyczny)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=9aae426d-ee9a-4736-b0a2-e0f8890a6895)<sup>[1]</sup>
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=00bae02a-64eb-4b91-965f-da2dc987a2ff)<sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=3780d565-d027-4f54-8fc0-05f5c3c6ba1a)  
(KB968816)  
(Krytyczny)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
(Krytyczny)  
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=9a465f92-3067-4a5a-9882-1fc2cf796c99)  
(KB968816)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2<sup>[3]</sup>
(Niski)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dbc33f6b-61bf-409a-89b5-60002192e0e0)  
(Krytyczny)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://go.microsoft.com/fwlink/?linkid=157304)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://go.microsoft.com/fwlink/?linkid=151360)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://go.microsoft.com/fwlink/?linkid=158082)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://go.microsoft.com/fwlink/?linkid=155978)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://go.microsoft.com/fwlink/?linkid=158009)
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
Brak
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=6acc9d2d-b71f-4b5c-9aea-b217b6ae240b)  
(KB971961)  
(Krytyczny)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=6af5d034-fd89-42e2-bc18-d44b7a6b0a85)<sup>[1]</sup>
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ecf9f7e2-3104-4de2-8b3d-99dcdcae6e62)<sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=4ab34e3d-34cb-4e35-a2da-b348ace8a8f7)  
(KB968816)  
(Krytyczny)  
[Windows Media Services 9.1](http://www.microsoft.com/downloads/details.aspx?familyid=61cd0581-c36e-4da6-ae95-41609adbe922)  
(KB972554)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48d82036-2fde-4bb0-a60e-92eed83ddc3f)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7478f73f-dd20-4cfa-a650-4c84f37ada2f)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=d0de3ab1-73e9-4a09-841f-81ade41a8c81)  
(KB971961)  
(Krytyczny)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=8f48bc05-ffac-4a21-8d21-dd20355cda8a)<sup>[1]</sup>
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=643f9e2f-2e5b-48dd-b1a0-22ccb633ed18)<sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=8654ee33-6083-447f-ae5b-43ef8d8b613d)  
(KB968816)  
(Krytyczny)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c)  
(KB968816)  
(Krytyczny)  
[Windows Media Services 9.1](http://www.microsoft.com/downloads/details.aspx?familyid=67c46f26-e6df-4ba2-9c03-1590b31e454c)  
(KB972554)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0298ddf-026e-4137-8197-ed9d9b889825)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=88bf502d-1a7c-447a-ac4c-401e1698669b)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=e78cf021-54f5-4526-b5f0-f781aebf9d72)  
(KB971961)  
(Krytyczny)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=fb1ca290-cea4-49c0-a37e-613a654bff3c)<sup>[1]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c948c4d8-5788-4c1a-9fb6-a969b06a888d)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=8d881ff8-f51f-4476-8cb6-2bebd5b2047f)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://go.microsoft.com/fwlink/?linkid=157304)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://go.microsoft.com/fwlink/?linkid=151360)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://go.microsoft.com/fwlink/?linkid=158082)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://go.microsoft.com/fwlink/?linkid=155978)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://go.microsoft.com/fwlink/?linkid=158009)
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
Brak
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=bcb12e57-f5d6-4b4e-88ab-13c28137f11a)  
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=80e7390f-df39-4d99-b2e1-01c7f6a951bb)<sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e9fe967f-d78d-43c2-bbcc-5098bd20267e)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 i Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=d2bdefcc-f6b9-47c3-a55d-a4f33f967828)  
(KB968816)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d72f845-9feb-4685-a669-f9d6ab54f9ed)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=8b1b76d5-a6b0-4c2f-8768-e55e82c2c118)  
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=24457cdd-1973-40c9-9c2d-c1a75fdfa7fa)<sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f93470bd-2e6d-4340-88c6-bb212baf750a)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 i Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=97f00b25-fb8f-4300-80c0-c63179f32182)  
(KB968816)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b2930ff1-5f0a-4a5d-bf2a-9fb76dd8da63)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://go.microsoft.com/fwlink/?linkid=157304)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://go.microsoft.com/fwlink/?linkid=151360)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://go.microsoft.com/fwlink/?linkid=158082)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://go.microsoft.com/fwlink/?linkid=155978)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://go.microsoft.com/fwlink/?linkid=158009)
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=df88e6e5-78d3-4fa6-858d-b935d812cada)\*  
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=e7b07be6-a4f8-4847-9c55-9b3d2965fa77)\* <sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=ac3f6800-bc3e-4b35-a482-54e1a2da1ab5)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 i Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=9c111bff-aff6-4ff7-81f6-e736cfcbe3ed)\*\*  
(KB968816)  
(Krytyczny)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=2801f69b-37d0-4d0f-9632-31382b824d36)\*  
(KB972554)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=35c1d5a9-a953-4fc6-90c0-d2358c7b89e6)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=f584f8ca-f6b1-4285-a44c-3df5e51e75de)\*  
(KB971961)  
(Krytyczny)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=9eddbb89-4178-49c2-836a-2d292fe50936)\* <sup>[2]</sup>
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=7d1b9b4f-bf35-44aa-a660-afb2ef2c9e30)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 i Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=59615c8b-a07f-4326-836d-f17b2fcc4695)\*\*  
(KB968816)  
(Krytyczny)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=7fad3793-174f-46db-9d0a-873a0ea8be65)\*  
(KB972554)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=6e46822e-f79d-492d-ad01-ee680ad324f5)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=b84fca1d-914d-45af-a48c-d9bc5d20c6b7)  
(KB971961)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=2ac76ee2-b1b6-4300-9cba-af33d9dd54eb)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
</table>
 
**Uwagi dotyczące systemu Windows Server 2008**

**\*Luka w zabezpieczeniach dotyczy instalacji Server Core systemu Windows Server 2008.** W przypadku obsługiwanych wersji systemu Windows Server 2008 ta aktualizacja ma zastosowanie, z takim samym wskaźnikiem ważności, niezależnie od tego, czy system Windows Server 2008 został zainstalowany przy użyciu opcji instalacji Server Core. Aby uzyskać więcej informacji na temat tej opcji instalacji, zobacz [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008; zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core systemu operacyjnego Windows Server 2008.** Lukom usuwanym przez tę aktualizację zabezpieczeń nie podlegają obsługiwane wersje systemu Windows Server 2008, jeżeli system Windows Server 2008 został zainstalowany przy użyciu opcji instalacji Server Core. Aby uzyskać więcej informacji na temat tej opcji instalacji, zobacz [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008; zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Uwagi dotyczące biuletynu MS09-045**

<sup>[1]</sup>W systemach z zainstalowanym programem Internet Explorer 7

<sup>[2]</sup>W systemach z zainstalowanym programem Internet Explorer 8

**Uwaga dotycząca biuletynu MS09-048**

<sup>[3]</sup> Brak dostępnej aktualizacji. Więcej informacji można znaleźć w sekcji **Często zadawane pytania dotyczące tej aktualizacji zabezpieczeń** w biuletynie [MS09-048](http://go.microsoft.com/fwlink/?linkid=155978).

Narzędzia wykrywania i wdrażania oraz wskazówki
-----------------------------------------------

<span></span>
**Centrum zabezpieczeń**

Zarządzanie oprogramowaniem oraz aktualizacjami zabezpieczeń, które należy zainstalować na serwerach oraz komputerach stacjonarnych i przenośnych w organizacji. Więcej informacji można znaleźć w [Centrum TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Witryna [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) zawiera dodatkowe informacje na temat zabezpieczeń w produktach firmy Microsoft. Użytkownicy mogą także uzyskać dostęp do tych informacji w witrynie [Bezpieczeństwo w domu](http://go.microsoft.com/fwlink/?linkid=85102), klikając łącze „Najnowsze aktualizacje zabezpieczeń”.

Aktualizacje zabezpieczeń dostępne są w witrynach [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) i [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizacje zabezpieczeń są także dostępne w witrynie [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.

Aktualizacje zabezpieczeń można także pobierać z [Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=96155). Wykaz usługi Microsoft Update zawiera katalog zawartości z możliwością przeszukiwania, który udostępniany jest poprzez usługi Windows Update i Microsoft Update i obejmuje aktualizacje zabezpieczeń, sterowniki i dodatki Service Pack. Wyszukiwanie przy użyciu numeru biuletynu zabezpieczeń (np. „MS07-036”) pozwala dodać do koszyka wszystkie odpowiednie aktualizacje (w tym różne wersje językowe aktualizacji) i pobrać pliki do wybranego folderu. Więcej informacji na temat Wykazu usługi Microsoft Update można znaleźć w [Często zadawanych pytaniach dotyczących Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=97900).

**Uwaga** Dnia 1 sierpnia 2009 r. firma Microsoft zakończyła świadczenie pomocy technicznej dla usługi Office Update oraz narzędzia Office Update Inventory Tool. Aby w dalszym ciągu otrzymywać najnowsze aktualizacje dla produktów Microsoft Office, skorzystaj z witryny [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Aby uzyskać więcej informacji, zobacz artykuł [Informacje o witrynie Microsoft Office Update: Często zadawane pytania](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Porady dotyczące wykrywania i wdrażania**

Firma Microsoft udziela porad dotyczących wykrywania i wdrażania aktualizacji zabezpieczeń. Porady takie zawierają zalecenia i informacje ułatwiające specjalistom IT poznanie obsługi różnych narzędzi do wykrywania i wdrażania aktualizacji zabezpieczeń. Więcej informacji na ten temat można znaleźć w [artykule 961747 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Narzędzie Microsoft Baseline Security Analyzer (MBSA)**

Narzędzie Microsoft Baseline Security Analyzer umożliwia administratorom skanowanie lokalnych i zdalnych systemów w poszukiwaniu brakujących aktualizacji zabezpieczeń oraz typowych błędów konfiguracji zabezpieczeń. Więcej informacji na temat narzędzia MBSA można znaleźć w witrynie sieci Web[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Korzystając z programu Windows Server Update Services (WSUS), administratorzy mogą szybko i niezawodnie wdrożyć najnowsze aktualizacje krytyczne i aktualizacje zabezpieczeń przeznaczonych dla systemu operacyjnego Windows 2000 i nowszych, pakietu Office XP i nowszych, programu Exchange Server 2003 oraz SQL Server 2000 w systemie operacyjnym Windows 2000 i nowszych.

Więcej informacji na temat sposobu wdrażania tej aktualizacji zabezpieczeń za pomocą programu Windows Server Update Services można znaleźć w [witrynie sieci Web programu Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Program Systems Management Server**

Program Systems Management Server (SMS) jest przeznaczonym dla przedsiębiorstw i w znacznym stopniu konfigurowalnym rozwiązaniem służącym do zarządzania aktualizacjami. Program SMS umożliwia administratorom znalezienie komputerów z systemem Windows, na których należy zainstalować aktualizację zabezpieczeń, a także przeprowadzić kontrolowane wdrożenie tych aktualizacji w całym przedsiębiorstwie, w minimalnym stopniu zakłócając przy tym pracę użytkowników końcowych. Dostępne jest kolejne wydanie programu SMS, System Center Configuration Manager 2007. Zapoznaj się także z zawartością witryny [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Więcej informacji na temat możliwości wykorzystania przez administratorów programu SMS 2003 do wdrażania aktualizacji zabezpieczeń można znaleźć w [witrynie sieci Web zarządzania poprawkami zabezpieczeń programu SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Użytkownicy programu SMS 2.0 mogą także skorzystać z narzędzia Security Update Inventory Tool (SUIT) ułatwiającego wdrożenie aktualizacji zabezpieczeń. Więcej informacji na temat programu SMS można znaleźć w witrynie sieci Web [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Uwaga** Program SMS zapewnia obsługę rozwiązań zawartych w biuletynach zabezpieczeń dzięki narzędziu Microsoft Baseline Security Analyzer. Narzędzia te mogą nie wykrywać wszystkich aktualizacji oprogramowania. W takich przypadkach administratorzy mogą wykorzystywać dostępne w programie SMS funkcje zarządzania zasobami do przyporządkowania poszczególnych aktualizacji określonym systemom. Aby uzyskać więcej informacji dotyczących tej procedury, zobacz [Wdrażanie aktualizacji oprogramowania za pomocą funkcji Software Distribution programu SMS](http://go.microsoft.com/fwlink/?linkid=33341). Niektóre aktualizacje oprogramowania wymagają od użytkownika uprawnień administratora po ponownym uruchomieniu systemu. Do zainstalowania tych aktualizacji administratorzy mogą użyć narzędzia Elevated Rights Deployment Tool (dostępnego w dodatkach [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) oraz [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Tester zgodności aktualizacji i zestaw narzędzi do sprawdzania zgodności aplikacji**

Często aktualizacje zapisują informacje w tych samych plikach i ustawieniach rejestru niezbędnych do działania określonych aplikacji użytkownika. Może to prowadzić do niezgodności i wydłużyć czas wdrażania aktualizacji zabezpieczeń. Dzięki składnikom narzędzia [Tester zgodności aplikacji](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) znajdującego się w [Zestawie narzędzi do sprawdzania zgodności aplikacji](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) można usprawnić proces testowania i sprawdzania poprawności aktualizacji systemu Windows.

W Zestawie narzędzi do sprawdzania zgodności aplikacji znajdują się niezbędne narzędzia i dokumentacja, które umożliwiają ocenę zgodności aplikacji przed wdrożeniem systemu Microsoft Windows Vista, aktualizacji dla systemu Windows, aktualizacji zabezpieczeń firmy Microsoft lub nowej wersji programu Windows Internet Explorer w środowisku użytkownika, oraz ograniczenie problemów ze zgodnością aplikacji.

### Inne informacje:

#### Narzędzie Microsoft Windows do usuwania złośliwego oprogramowania

Firma Microsoft opublikowała zaktualizowaną wersję narzędzia Microsoft Windows Malicious Software Removal Tool, która dostępna jest w witrynach sieci Web Windows Update i Microsoft Update, poprzez usługi Windows Server Update Services i w witrynie Microsoft Download Center.

#### Aktualizacje o wysokim priorytecie niezwiązane z zabezpieczeniami, dostępne w witrynach MU, WU oraz usługach WSUS

Aby uzyskać informacje na temat publikacji niezwiązanych z zabezpieczeniami, dostępnych w witrynach Windows Update i Microsoft Update, zobacz:

-   [Artykuł 894199 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Opis zmian zawartości Usług aktualizacji oprogramowania i usług Windows Server Update Services. Zawiera wszystkie treści dotyczące systemu Windows.
-   [Aktualizacje z poprzednich miesięcy dla usług Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Wyświetla nowe, zmienione i opublikowane ponownie aktualizacje dla produktów firmy Microsoft innych niż Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

W celu zwiększenia poziomu bezpieczeństwa swoich klientów firma Microsoft dostarcza informacje na temat luk w zabezpieczeniach największym dostawcom oprogramowania zabezpieczającego przed publikacją comiesięcznej aktualizacji zabezpieczeń. Dzięki informacjom dotyczącym luk w zabezpieczeniach dostawcy oprogramowania zabezpieczającego mogą zaoferować swoim klientom zaktualizowane poprawki za pośrednictwem programów lub urządzeń zabezpieczających np. programów antywirusowych, sieciowych systemów wykrywania włamań lub hostowych systemów zapobiegania włamaniom. Aby sprawdzić, czy dostawcy oprogramowania zabezpieczającego zapewniają aktywną ochronę, odwiedź witryny poszczególnych partnerów programu, których listę znaleźć można w sekcji [Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

#### Strategie i społeczność związane z zabezpieczeniami

**Strategie zarządzania aktualizacjami**

Na stronie [Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (Wskazówki z zakresu bezpieczeństwa dotyczące zarządzania aktualizacjami) znajdują się dodatkowe informacje o zalecanych przez firmę Microsoft najlepszych sposobach stosowania aktualizacji zabezpieczeń.

**Uzyskiwanie innych aktualizacji zabezpieczeń**

Aktualizacje dotyczące innych problemów związanych z zabezpieczeniami można uzyskać w następujących lokalizacjach:

-   Aktualizacje zabezpieczeń są dostępne w witrynie [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.
-   Aktualizacje dla poszczególnych platform są dostępne w [witrynie sieci Web Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizacje zabezpieczeń dostępne w tym miesiącu w witrynie Windows Update można otrzymać w witrynie Microsoft Download Center w postaci plików obrazu dysku CD zawierającego zabezpieczenia i aktualizacje krytyczne. Więcej informacji na ten temat można znaleźć w [artykule 913086 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Społeczność IT Pro Security Community**

Dowiedz się, jak poprawić bezpieczeństwo i zoptymalizować infrastrukturę informatyczną oraz weź udział w dyskusjach dotyczących zabezpieczeń wraz z innymi specjalistami branży IT, odwiedzając witrynę sieci Web społeczności [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (jęz. ang.).

#### Podziękowania

Firma Microsoft [dziękuje](http://go.microsoft.com/fwlink/?linkid=21127) wymienionym poniżej organizacjom i osobom za współpracę w dziedzinie ochrony klientów:

-   Ling i Wushi z [team509](http://www.team509.com/), we współpracy [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy Tipping Point, za zgłoszenie problemu opisanego w biuletynie MS09-045
-   Tavis Ormandy z firmy [Google Inc.](http://www.google.com/) za zgłoszenie problemu opisanego w biuletynie MS09-046
-   Peter Winter-Smith z firmy [NGS Software](http://www.ngssoftware.com/) za zgłoszenie problemu opisanego w biuletynie MS09-047
-   Hiroshi Noguchi z fanklubu Alice Carroll za zgłoszenie problemu opisanego w biuletynie MS09-047
-   Jack C. Louis z firmy [Outpost24](http://www.outpost24.com/) za zgłoszenie problemu opisanego w biuletynie MS09-048
-   Fabianowi Yamaguchi z firmy [Recurity Labs GmbH](http://www.recurity-labs.com/) za zgłoszenie problemu opisanego w biuletynie MS09-048

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pod numerem 0 801 802 000 (Opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne. Dodatkowe informacje dotyczące możliwości skorzystania z pomocy technicznej można znaleźć w witrynie [Pomoc i obsługa techniczna firmy Microsoft](http://support.microsoft.com/).
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (8 września 2009 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.
-   Wersja 2.0 (9 września 2009 r.): Dodano systemy Windows XP z dodatkiem Service Pack 2, Windows XP z dodatkiem Service Pack 3 oraz Windows XP Professional x64 Edition z dodatkiem Service Pack 2 do tabeli „Programy, których dotyczy problem” w biuletynie MS09-048. Nie są jednak dostępne aktualizacje dla tych platform. Zobacz wpis w sekcji **Często zadawane pytania dotyczące tej aktualizacji zabezpieczeń** w biuletynie MS09-048. W biuletynie tym nie wprowadzono żadnych zmian w zakresie oferowanych aktualizacji zabezpieczeń.
-   Wersja 3.0 (10 listopada 2009 r.): Do tabeli „Programy, których dotyczy problem” w biuletynie MS09-045 dodano program JScript 5.7 w systemie Microsoft Windows 2000 z dodatkiem Service Pack 4.

*Built at 2014-04-18T01:50:00Z-07:00*
