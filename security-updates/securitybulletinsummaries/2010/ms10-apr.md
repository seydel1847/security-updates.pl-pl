---
TOCTitle: 'MS10-APR'
Title: 'Podsumowanie biuletynów zabezpieczeń firmy Microsoft za kwiecień 2010 r.'
ms:assetid: 'ms10-apr'
ms:contentKeyID: 61233108
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms10-apr(v=Security.10)'
---
Podsumowanie biuletynów zabezpieczeń firmy Microsoft za kwiecień 2010 r.
========================================================================

Opublikowano: 13 kwietnia 2010 | Zaktualizowano: 13 lipca 2010

**Wersja:** 4.0

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za kwiecień 2010 r.

Z chwilą opublikowania biuletynów za kwiecień 2010 r. niniejsze podsumowanie biuletynów zastępuje powiadomienie o biuletynach zabezpieczeń wydane 8 kwietnia 2010 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j. ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

14 kwietnia 2010 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępni emisję internetową, w której znajdą się odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). [Zarejestruj się, aby zobaczyć emisję internetową dotyczącą biuletynów zabezpieczeń za kwiecień](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427721&eventcategory=4&culture=en-us&countrycode=us). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184933">MS10-019</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach systemu Windows umożliwiają zdalne wykonanie kodu (981210)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa dwie zgłoszone przez użytkowników luki w zabezpieczeniach usługi Windows Authenticode Verification, które potencjalnie umożliwiają zdalne wykonanie kodu. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać pełną kontrolę nad systemem, którego dotyczy luka. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach klienta SMB umożliwiają zdalne wykonanie kodu (980232)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa jedną lukę zgłoszoną przez organizacje publiczne oraz kilka luk zgłoszonych przez użytkowników, które istnieją w systemie Microsoft Windows. Luki w zabezpieczeniach umożliwiają zdalne wykonanie kodu, jeśli osoba atakująca wyśle specjalnie spreparowaną odpowiedź SMB na żądanie SMB zainicjowane przez klienta. Aby wykorzystać te luki, osoba atakująca musi przekonać użytkownika do zainicjowania połączenia SMB ze specjalnie spreparowanym serwerem SMB.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185146">MS10-025</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft Windows Media Services może umożliwić zdalne wykonanie kodu (980858)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach programu Windows Media Services działającego w systemie Microsoft Windows 2000 Server, która została zgłoszona przez użytkowników. Luka ta umożliwia zdalne wykonanie kodu, gdy osoba atakująca wyśle specjalnie spreparowany pakiet informacji transportowych do systemu Microsoft Windows 2000 Server, w którym uruchomiono program Windows Media Services. Sprawdzone metody działania stosowane w zaporach oraz standardowe domyślne konfiguracje zapór mogą pomóc w ochronie sieci przed atakami spoza przedsiębiorstwa. Zgodnie ze standardowymi zasadami działania zaleca się, aby w systemach połączonych z Internetem była otwarta jak najmniejsza liczba portów. Program Windows Media Services jest opcjonalnym składnikiem systemu Microsoft Windows 2000 Server i domyślnie nie jest instalowany.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184752">MS10-026</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach koderów-dekoderów formatu MPEG Layer-3 firmy Microsoft może umożliwić zdalne wykonanie kodu (977816)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach kodera-dekodera audio formatu MPEG Layer-3 firmy Microsoft, która została zgłoszona przez użytkowników. Luka ta może umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik AVI zawierający strumień audio w formacie MPEG Layer-3. Jeśli użytkownik jest zalogowany jako administrator, osoba atakująca, która pomyślnie wykorzysta tę lukę, może uzyskać pełną kontrolę nad systemem, którego ta luka dotyczy. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184071">MS10-027</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Windows Media Player może umożliwić zdalne wykonanie kodu (979402)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w zabezpieczeniach programu Windows Media Player. Omawiana luka może pozwolić na zdalne wykonanie kodu, jeśli w programie Windows Media Player zostanie otwarta specjalnie spreparowana zawartość multimedialna umieszczona w złośliwej witrynie sieci Web. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184814">MS10-021</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach jądra systemu Windows umożliwiają podniesienie poziomu uprawnień (979683)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa kilka luk w zabezpieczeniach systemu Microsoft Windows, które zostały zgłoszone przez użytkowników. Najpoważniejsza z tych luk może umożliwić podniesienie uprawnień, jeśli osoba atakująca zaloguje się lokalnie i uruchomi specjalnie spreparowaną aplikację. Osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania oraz być w stanie zalogować się lokalnie, aby wykorzystać możliwości stwarzane przez luki. Nie jest możliwe wykorzystanie luk w sposób zdalny ani przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184779">MS10-022</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach VBScript może umożliwić zdalne wykonanie kodu (981169)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa zgłoszoną przez organizację publiczną lukę w zabezpieczeniach aparatu VBScript umożliwiająca zdalne wykonanie kodu. Niniejsza aktualizacja zabezpieczeń ma wskaźnik „ważny” dla systemów Microsoft Windows 2000, Windows XP i Windows Server 2003. W systemach Windows Server 2008, Windows Vista, Windows 7 i Windows Server 2008 R2 nie można wykorzystać kodu, którego dotyczy luka. Ponieważ kod ten jest obecny, niniejsza aktualizacja jest udostępniana jako dodatkowe wzmocnienie ochrony i nie ma dla niej wskaźnika ważności.<br />
<br />
Luka ta może pozwolić na zdalne wykonanie kodu, gdy złośliwa witryna sieci Web wyświetli specjalnie spreparowane okno dialogowe na stronie sieci Web, a użytkownik naciśnie klawisz F1, powodując uruchomienie systemu pomocy Windows z użyciem pliku pomocy systemu Windows dostarczonego przez osobę atakującą. Jeśli użytkownik jest zalogowany jako administrator, osoba atakująca, która pomyślnie wykorzysta tę lukę, może uzyskać pełną kontrolę nad systemem, którego ta luka dotyczy.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184751">MS10-023</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft Office Publisher umożliwia zdalne wykonanie kodu (981160)</strong><br />
<br />
Ta aktualizacja zabezpieczeń pozwala usunąć lukę w zabezpieczeniach programu Microsoft Office Publisher zgłoszoną przez osobę prywatną, która może pozwolić na zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik programu Publisher. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167307">MS10-024</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach programu Microsoft Exchange i usługi SMTP systemu Windows umożliwiają przeprowadzenie ataku typu „odmowa usługi” (981832)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach programu Microsoft Exchange i usługi SMTP systemu Windows, z których jedną zgłosiły organizacje publiczne, a drugą użytkownicy. Bardziej poważna z tych luk umożliwia przeprowadzenie ataku typu „odmowa usługi”, gdy osoba atakująca wyśle specjalnie spreparowaną odpowiedź DNS do komputera z uruchomioną usługą SMTP. Składnik SMTP nie jest domyślnie zainstalowany w systemie Windows Server 2003, Windows Server 2003 x64 Edition i Windows XP Professional x64 Edition.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Odmowa usługi</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Exchange</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182935">MS10-028</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach programu Microsoft Visio umożliwiają zdalne wykonanie kodu (980094)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach programu Microsoft Office Visio, które zostały zgłoszone przez użytkowników. Luki te mogą umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik programu Visio. Osoba atakująca, której uda się wykorzystać te luki, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179056">MS10-029</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach składnika ISATAP systemu Windows mogą umożliwić fałszowanie (978338)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows zgłoszoną przez użytkowników. Ta aktualizacja zabezpieczeń ma wskaźnik ważności „umiarkowany” dla systemu Windows XP, Windows Server 2003, Windows Vista i Windows Server 2008. Systemy Windows 7 i Windows Server 2008 R2 nie są zagrożone przez omawianą lukę, ponieważ zawierają funkcję wdrażaną przez niniejszą aktualizację.<br />
<br />
Luka ta może pozwolić osobie atakującej na sfałszowanie adresu IPv4, tak aby mógł on ominąć urządzenia filtrujące, które bazują na źródłowym adresie IPv4. Aktualizacja zabezpieczeń usuwa lukę, zmieniając sposób, w jaki stos TCP/IP systemu Windows sprawdza źródłowy adres IPv6 w tunelowanym pakiecie protokołu ISATAP.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Umiarkowany</a><br />
Fałszowanie</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Wskaźnik możliwości wykorzystania luki  
--------------------------------------
  
<span></span>
Poniższa tabela przedstawia ocenę możliwości wykorzystania luk dla każdej luki opisywanej w tym miesiącu. Luki są wymienione według malejącego poziomu oceny możliwości wykorzystania, a nie według identyfikatora CVE. Uwzględniono wyłącznie te luki, które w biuletynach mają nadany wskaźnik ważności „krytyczny” lub „ważny”.
  
**W jaki sposób korzystać z tej tabeli?**
  
Tabela ta pozwala sprawdzić prawdopodobieństwo, że w ciągu 30 dni od wydania biuletynu zabezpieczeń dla każdej z aktualizacji zabezpieczeń, których zainstalowanie może być potrzebne, opublikowany zostanie działający kod wykorzystujący lukę w zabezpieczeniach. Aby ustalić priorytety wdrażania, zapoznaj się z dostępnymi poniżej ocenami, rozpatrując je w kontekście posiadanej konfiguracji. Więcej informacji na temat znaczenia tych ocen oraz sposobu ich wyznaczania można znaleźć na stronie sieci Web [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

 
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184814">MS10-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach jądra systemu Windows związana z alokacją pamięci</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0236">CVE-2010-0236</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184814">MS10-021</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach jądra systemu Windows związana z tworzeniem łącza symbolicznego</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0237">CVE-2010-0237</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182935">MS10-028</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach procedury sprawdzania poprawności atrybutów programu Visio związana z uszkodzeniem pamięci</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0254">CVE-2010-0254</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184071">MS10-027</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Media Player umożliwiająca zdalne wykonanie kodu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0268">CVE-2010-0268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185146">MS10-025</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Media Services związana z przepełnieniem buforu opartego na stosie</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0478">CVE-2010-0478</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184751">MS10-023</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach programu Microsoft Office Publisher dotycząca konwersji pliku i związana z przepełnieniem buforu przetwarzania pola tekstowego</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0479">CVE-2010-0479</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184752">MS10-026</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach związana z przepełnieniem stosu dekodera audio MPEG Layer-3</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0480">CVE-2010-0480</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184779">MS10-022</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach systemu pomocy aparatu VBScript związana z naciśnięciem klawisza</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-0483</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - prawdopodobny spójny kod wykorzystujący lukę<br />
<br />
Windows Server 2008, Windows 7 i Windows Server 2008 R2:<br />
<a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie, opisano to w <a href="http://technet.microsoft.com/security/advisory/981169">poradniku zabezpieczeń firmy Microsoft 981169</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=182935">MS10-028</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach procedury obliczania indeksów programu Visio związana z uszkodzeniem pamięci</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0256">CVE-2010-0256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach klienta SMB związana z transakcją</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0270">CVE-2010-0270</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach klienta SMB związana z analizowaniem odpowiedzi</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0476">CVE-2010-0476</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184933">MS10-019</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach procedury sprawdzania poprawności podpisu funkcji WinVerifyTrust</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0486">CVE-2010-0486</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184933">MS10-019</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach procedury sprawdzania poprawności związana z uszkodzeniem składnika Cabview</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0487">CVE-2010-0487</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - prawdopodobny niespójny kod wykorzystujący lukę</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach klienta SMB związana z niepełną odpowiedzią</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3676">CVE-2009-3676</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Informacje o tej luce są znane publicznie, opisano to w <a href="http://technet.microsoft.com/security/advisory/977544">poradniku zabezpieczeń firmy Microsoft 977544</a><br />
<br />
Najbardziej prawdopodobny wynik to odmowa usługi.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167307">MS10-024</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach serwera SMTP związana z rekordem MX</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0024">CVE-2010-0024</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Najbardziej prawdopodobny wynik to odmowa usługi</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach klienta SMB związana z alokacją pamięci</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0269">CVE-2010-0269</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">(Brak)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184663">MS10-020</a></td>
<td style="border:1px solid black;">Luka w zabezpieczeniach klienta SMB związana z wielkością komunikatu</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0477">CVE-2010-0477</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - działający kod wykorzystujący lukę mało prawdopodobny</td>
<td style="border:1px solid black;">Najbardziej prawdopodobny wynik to odmowa usługi</td>
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
</tr>
<tr>
<th colspan="10">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 z dodatkiem Service Pack 4
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=d7538166-35ee-4c6b-be8c-e83a1fc6cd77)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=13846177-f25f-4dd4-9fe9-ac43e1d4d73d)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=67ccac04-e5c8-4381-9d1a-9b676dd516a6)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=73b3d681-26bb-49c1-849e-1f72484cb978)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=f6394fc2-b9d0-46cf-9265-a0d4aeb1448f)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Media Player Seria 9](http://www.microsoft.com/downloads/details.aspx?familyid=c0b8b362-a321-4ac9-be98-15c71bb7a043)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=c5f4577e-7546-40e9-8bcd-be11c1b260a6)  
(Ważny)
</td>
<td style="border:1px solid black;">
[VBScript 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073)<sup>[1]</sup>
(KB981350)  
(Ważny)  
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=421be318-f217-4d12-b7a5-833093189073)(KB981350)  
(Ważny)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=d5fc47a4-cecb-4817-aafb-45f335061be3)  
(KB981349)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=88a0e872-01de-495b-8eec-d105a970daa7)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<th colspan="10">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
Brak
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=2a01ddf0-f3ea-47c8-ada2-e69f6c1b5f96)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=6c3ac102-2107-4726-98be-4fbf6b858bfb)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=dec38c02-3d4a-41c5-8954-e57f56b8fa5b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=b1582a74-4a7b-4540-beb1-7c89c86eae87)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Program Windows Media Player Seria 9 w systemie Windows XP z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5c748c6d-84d1-45a9-8a33-9372eb5504d5)  
(Krytyczny)  
[Program Windows Media Player Seria 9 w systemie Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9e4277b4-2dc5-4163-a6aa-7e07dd32b721)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=142710fd-9cd4-4dd0-aaba-2aace03c008f)  
(Ważny)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=aa8ff157-a7b3-4787-80c9-5bc453f0f1c9) w systemie Windows XP z dodatkiem Service Pack 2  
(KB981350)  
(Ważny)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=cb21d276-65e9-4c8f-96e3-cf6dc36d0133)  
(KB981349)  
(Ważny)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ba7ef6e5-80ba-4281-a611-6e5be008c1b4)  
(KB981332)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=de447b76-ec89-426b-ac54-3ae3855d1159)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=9dc3e1c2-2e9d-4d86-9fce-446c409ad613)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=9bbff00c-f8f4-4a44-98f2-18a868986ae1)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e64e487e-2727-4396-b0c9-6eaf000214d2)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c5a21239-a9a3-4ec5-9de8-7d2fc16fc6b8)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=8afca317-a647-44aa-a771-5d85cd5d62ea)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3c0cb02e-3484-4cdf-8c64-c697ad3e2889)  
(Ważny)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=896c738d-4058-440f-8d4f-16c678610cd1)  
(KB981350)  
(Ważny)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=d7e8b930-8708-4f0b-b22b-961c2cbc2673)  
(KB981349)  
(Ważny)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=153fd9c1-0f8e-4492-87d1-f0381e7feb23)  
(KB981332)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4f9a696d-2712-4777-a642-e78a38336e8a)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d872bd77-f491-4706-8ff5-081ac0bf3d6f)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
Brak
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=0e7e3deb-f078-4953-9642-675ec69267f2)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ae9b1d0-0dbe-4abd-b315-10cea4ceccd7)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1189304f-d626-426d-960c-a86dc2d2b528)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=9f89746c-181e-4177-a851-ec1826e78b6d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0a7ea2d0-61ce-4b68-ad82-d917b1a56f9d)  
(Ważny)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=28b035b8-d56e-4e93-b811-9a82cf1d4ba9)  
(KB981350)  
(Ważny)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=a142a553-85fc-40e0-9426-8d58f6a4333c)  
(KB981349)  
(Ważny)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=72754e1b-3d09-4b9d-8794-689c45a37f66)  
(KB981332)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f781e9e4-87d4-4243-9d44-256424d75fec)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cd007a6c-04b3-490c-aff4-d5af3e69d477)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=99a3f6da-728f-421c-ab41-c4c4751934a4)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=1709fd4e-d7c6-4cbb-8b71-a96b8d6eee58)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=52e4f66b-b76c-46a1-aeff-74efa21fc743)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=b97e7ea1-a163-4ce4-8cbc-5f933773c4b2)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1fc66f54-260a-4219-a0b4-056ba9dd0abe)  
(Ważny)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=339ddf48-8949-4857-9ef6-1ddcc7c5f8b8)  
(KB981350)  
(Ważny)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=a489b4e3-78d2-411b-b27c-5987b8fc91d1)  
(KB981349)  
(Ważny)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=72c3013b-f72f-422b-8a89-2246dea4b378)  
(KB981332)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=644ff070-237b-4a73-b2e2-9fffdafa3927)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=19cfddfe-e8da-4564-9730-babfae4a3ebb)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=06832599-1e9b-4792-8c7b-7b5b3a3d6277)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=811a2b28-655d-4b5d-821e-5a90d556dba3)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b2b6d8b1-63cc-459c-b5fa-1355386273c8)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=8dcb8be8-fb78-4518-aa7e-f8b17f7dfb86)  
(Ważny)
</td>
<td style="border:1px solid black;">
[VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=9a8bee82-5f7f-490e-a1eb-481f6d4fc4f5)  
(KB981350)  
(Ważny)  
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=7d542ac6-8a5b-4dd7-8688-2b5feb563636)  
(KB981349)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=56c8238d-8b04-4aa5-8719-40550cd7325c)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=916f1b09-e79e-4347-9fbc-c0cf07de397d)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="10">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
Brak
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
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=a52225a7-6005-4f2b-8291-db20558f23f8)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=6145e2b2-36fd-4360-bd5b-2bd11890fc52)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=25eeaeb3-c0a3-4a02-9912-acd0342648ba)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=0e7140bb-42d3-48b3-9f4b-d55b17770de8)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista](http://www.microsoft.com/downloads/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
(Ważny)  
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=86d7b054-af4f-4d8a-9873-cb5246466374)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=ee5c42c6-16bb-48bf-95c2-c188bb17d04b)  
(KB981349)  
(Brak wskaźnika ważności<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=f2a37dbf-4a95-4e8d-a474-ecacd9aee690)  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=196055a6-15d1-4da8-b33d-501e69bf5176)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=9ba7468c-23a4-4994-9a5a-22e96ef586f3)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=5b7efa82-0feb-413a-9f8e-212e7432cd99)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=394c1caa-97e4-47a3-9aac-a4a88508bd31)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=b885aef4-3a5d-4c3e-bef6-5efef2965752)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
(Ważny)  
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7c84aa24-6331-427a-969c-27f7d39db3d7)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=ea5c5e9c-0ecd-47bc-912d-5adc00d1aa21)  
(KB981349)  
(Brak wskaźnika ważności<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=79093796-4ea9-4c6c-92cc-3fd63c5db918)  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7c1d1622-1b67-438d-aae4-1a3954974a36)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
Brak
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=97ffeec8-8b6d-4a30-97b0-4bff2ba5e91d)\*  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f111735b-68b0-4bcc-9dd8-818a5eca3400)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=51c9c420-4507-4911-a8f5-82331a696882)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=8e9c04c9-898f-4ed2-949d-f4343cc0d9f6)\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=25e3ce7f-53a0-4049-a65c-011d2143c4c2)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=dbe89813-0a45-463b-928c-1e58f7bb596a)\*\*  
(KB981349)  
(Brak wskaźnika ważności<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=527d6376-efc9-436b-835b-219d38bb28f0)\*\*  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=e29ead69-000a-4982-a25c-f3981eda381a)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=61ece7bc-e9fa-4ede-ba7d-9e5a4c64b9be)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=49f9f740-023a-4291-becf-838a1d282321)\*  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=91c08251-0085-44cb-9e9c-9a1a84374caf)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=61c26a1f-c885-4474-9843-204c41628889)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Kodery-dekodery MPEG Layer-3](http://www.microsoft.com/downloads/details.aspx?familyid=d6f2e1ae-48d3-4d2c-b329-32cff00afee5)\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=8b99e54d-955b-4a06-9a04-b2f4596efd72)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=9db62357-557d-40cd-9826-b7baa6c9de65)\*\*  
(KB981349)  
(Brak wskaźnika ważności<sup>[2]</sup>)  
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=0c384dbc-21b7-4cbc-b68f-ced971d9b791)\*\*  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=8f922e64-e3a6-46fe-9a81-b2813ea6a330)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=72e7c7ea-55ef-457b-a03a-49aa9dea2e84)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=bd60779a-8bb1-4107-a344-9b09a50e96ff)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=eb116688-1d6e-4e20-948e-1d347af5d985)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=bcf8b919-08a9-487f-8dfd-3ca24328c4f3)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b1f9746d-61a2-406f-b707-60646bd5b5bb)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=84c5aaae-9417-42a1-834f-22c1ad46a12f)  
(KB981349)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=8c48302c-a1d6-41bc-ad24-7ce7332d4842)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="10">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=8d4a6c65-e171-4570-8f3f-118f06910baf)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=f0dbac52-0f0e-40bc-9371-17fa594424d5)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=389184c5-9001-497d-bdf4-81f97ecb617f)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=ff58d80c-33ce-4d9e-aaa5-0b1841458931)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=c3f76835-0053-4e53-a451-14255e7a4fc0)  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
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
Windows 7 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=cf8c6721-05c2-4680-93b4-be36f09c6d15)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=b23efe7d-bca4-4d49-9104-6ae39dc5daa9)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=f3495dae-71f3-421d-a191-d26965f26ad1)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=7f1dc055-2ec9-407a-9e69-da12338587e3)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=998164b7-4b8c-468b-8d39-f242633c8838)  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<th colspan="10">
System Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-019**](http://go.microsoft.com/fwlink/?linkid=184933)
</td>
<td style="border:1px solid black;">
[**MS10-020**](http://go.microsoft.com/fwlink/?linkid=184663)
</td>
<td style="border:1px solid black;">
[**MS10-025**](http://go.microsoft.com/fwlink/?linkid=185146)
</td>
<td style="border:1px solid black;">
[**MS10-026**](http://go.microsoft.com/fwlink/?linkid=184752)
</td>
<td style="border:1px solid black;">
[**MS10-027**](http://go.microsoft.com/fwlink/?linkid=184071)
</td>
<td style="border:1px solid black;">
[**MS10-021**](http://go.microsoft.com/fwlink/?linkid=184814)
</td>
<td style="border:1px solid black;">
[**MS10-022**](http://go.microsoft.com/fwlink/?linkid=184779)
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
</td>
<td style="border:1px solid black;">
[**MS10-029**](http://go.microsoft.com/fwlink/?linkid=179056)
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
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
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
Windows Server 2008 R2 dla systemów opartych na procesorach x64
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=94dfdaae-8464-4de6-a401-7eb70b3bb34f)\*  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=a2979c02-2a80-4b84-bf6c-4798064bdf28)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=cd1a046e-915d-4904-b753-5a24be10c504)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=28389c1d-2a12-4bef-a59b-726bb6449c8b)\*  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=c4039d40-a0c7-4183-ab50-04f690d1c5dc)\*\*  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=eb27cd2b-d514-4405-8650-259a42e35155)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach Itanium
</td>
<td style="border:1px solid black;">
[Authenticode Signature Verification 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=40f622d2-48e7-4eb2-9430-bbd218cb5208)  
(KB978601)  
(Krytyczny)  
[Rozszerzenie zawartości powłoki plików cabinet 6.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e416d4b-5de7-4688-80c6-245de159e0ce)  
(KB979309)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=541e9e2f-ec1d-42b2-aae5-481c0d435169)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d4ea3984-5183-47f1-814e-29cb6c90ae06)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=8174463c-5c5e-4095-90c8-fd1e898d4ba5)  
(KB981332)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
</table>
 
**Uwagi dotyczące systemu Windows Server 2008 i Windows Server 2008 R2**

**\*Luka w zabezpieczeniach dotyczy instalacji Server Core.** Ta aktualizacja ma zastosowanie, z takim samym wskaźnikiem ważności, w przypadku obsługiwanych wersji systemu Windows Server 2008 lub Windows Server 2008 R2, niezależnie od tego, czy zostały zainstalowane przy użyciu opcji instalacji Server Core. Aby uzyskać więcej informacji na temat tej opcji instalacji, zobacz artykuły MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (j. ang.) i [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (j. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core.** Luki usuwane przez tę aktualizację zabezpieczeń nie dotyczą obsługiwanych wersji systemu Windows Server 2008 ani Windows Server 2008 R2, jeżeli systemy te zostały zainstalowane przy użyciu opcji instalacji Server Core. Aby uzyskać więcej informacji na temat tej opcji instalacji, zobacz artykuły MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (j. ang.) i [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (j. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Uwagi dotyczące biuletynu MS10-022**

<sup>[1]</sup>Ta aktualizacja zabezpieczeń powoduje uaktualnienie aparatu VBScript 5.1 do VBScript 5.6.

<sup>[2]</sup>Do tej aktualizacji nie stosuje się wskaźników ważności, ponieważ omawiana w biuletynie luka w zabezpieczeniach nie ma wpływu na to oprogramowanie. Jednak w ramach dodatkowego wzmocnienia ochrony przed ewentualnymi nowymi kierunkami ataku, które mogą zostać rozpoznane w przyszłości, firma Microsoft zaleca, aby użytkownicy tego oprogramowania zainstalowali omawianą aktualizację zabezpieczeń.

**Uwaga dotycząca biuletynu MS10-024**

Zobacz także pozostałe kategorie oprogramowania w sekcji **Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

#### Pakiety i oprogramowanie Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Pakiety Microsoft Office, systemy i ich składniki
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-023**](http://go.microsoft.com/fwlink/?linkid=184751)
</td>
<td style="border:1px solid black;">
[**MS10-028**](http://go.microsoft.com/fwlink/?linkid=182935)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2002 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=943b3830-70d5-46c5-bffc-1b494434b5f7)  
(KB980466)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2d563cbc-d8f7-486b-8c54-25d168085376)  
(KB979364)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7c2f4610-77bb-4d72-847b-1a06c523b137)  
(KB980469)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=803a7ea0-a9da-46dd-9548-0177d3774be7)  
(KB979356)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Pakiet Microsoft Office 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 z dodatkiem Service Pack 1 oraz Microsoft Office Publisher 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=10ca2f71-0ab2-4344-b7fd-bbbd6a783a96)  
(KB980470)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 z dodatkiem Service Pack 1 i Microsoft Office Visio 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=56fe020f-4444-4a43-aa98-e99a622f6a69)  
(KB979365)  
(Ważny)
</td>
</tr>
</table>
 

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
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-024**](http://go.microsoft.com/fwlink/?linkid=167307)
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
Microsoft Exchange Server 2000
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2000 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e47c90a0-c9c8-43b7-bec7-34107ddde294)  
(KB976703)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc8391f8-5335-496b-ad4c-bae38509be4a)  
(KB976702)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=6a894b4e-12b6-4a91-9555-d813956b6aac)  
(KB981407)  
(Brak wskaźnika ważności<sup>[1]</sup>)  
[Microsoft Exchange Server 2007 z dodatkiem Service Pack 2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=b8f7f872-16d5-49d6-9867-adc01351c06f)  
(KB981383)  
(Brak wskaźnika ważności<sup>[1]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=7dcf2390-dff7-4e3a-acca-03f4d43fb79a)  
(KB981401)  
(Brak wskaźnika ważności<sup>[1]</sup>)
</td>
</tr>
</table>
 
**Uwagi dotyczące biuletynu MS10-024**

<sup>[1]</sup>Do tej aktualizacji nie stosuje się wskaźników ważności, ponieważ omawiana w biuletynie luka w zabezpieczeniach nie ma wpływu na to oprogramowanie. Firma Microsoft zaleca jednak, aby użytkownicy tego oprogramowania zastosowali tę aktualizację, która obejmuje kompleksowe zabezpieczenie dodające dodatkową entropię portu źródłowego do transakcji DNS zainicjowanych przez usługę SMTP.

Zobacz także pozostałe kategorie oprogramowania w sekcji **Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

Narzędzia wykrywania i wdrażania oraz wskazówki
-----------------------------------------------

<span></span>
**Centrum zabezpieczeń**

Zarządzanie oprogramowaniem oraz aktualizacjami zabezpieczeń, które należy zainstalować na serwerach oraz komputerach stacjonarnych i przenośnych w organizacji. Więcej informacji można znaleźć w [Centrum TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Witryna [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) zawiera dodatkowe informacje na temat zabezpieczeń w produktach firmy Microsoft. Użytkownicy mogą także uzyskać dostęp do tych informacji w witrynie [Bezpieczeństwo w domu](http://go.microsoft.com/fwlink/?linkid=85102), klikając łącze „Najnowsze aktualizacje zabezpieczeń”.

Aktualizacje zabezpieczeń dostępne są w witrynach [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) i [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizacje zabezpieczeń są także dostępne w witrynie [Centrum pobierania Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.

Aktualizacje zabezpieczeń można także pobierać z [Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=96155). Wykaz usługi Microsoft Update zawiera katalog zawartości z możliwością przeszukiwania, który udostępniany jest poprzez usługi Windows Update i Microsoft Update i obejmuje aktualizacje zabezpieczeń, sterowniki i dodatki Service Pack. Wyszukiwanie przy użyciu numeru biuletynu zabezpieczeń (np. „MS07-036”) pozwala dodać do koszyka wszystkie odpowiednie aktualizacje (w tym różne wersje językowe aktualizacji) i pobrać pliki do wybranego folderu. Więcej informacji na temat Wykazu usługi Microsoft Update można znaleźć w [Często zadawanych pytaniach dotyczących Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=97900).

**Uwaga** Dnia 1 sierpnia 2009 r. firma Microsoft zakończyła świadczenie pomocy technicznej dla usługi Office Update oraz narzędzia Office Update Inventory Tool. Aby w dalszym ciągu otrzymywać najnowsze aktualizacje dla produktów Microsoft Office, skorzystaj z witryny [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Aby uzyskać więcej informacji, zobacz artykuł [Informacje o witrynie Microsoft Office Update: Często zadawane pytania](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Porady dotyczące wykrywania i wdrażania**

Firma Microsoft udziela porad dotyczących wykrywania i wdrażania aktualizacji zabezpieczeń. Porady takie zawierają zalecenia i informacje ułatwiające specjalistom IT poznanie obsługi różnych narzędzi do wykrywania i wdrażania aktualizacji zabezpieczeń. Więcej informacji na ten temat można znaleźć w [artykule 961747 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Narzędzie Microsoft Baseline Security Analyzer (MBSA)**

Narzędzie Microsoft Baseline Security Analyzer umożliwia administratorom skanowanie lokalnych i zdalnych systemów w poszukiwaniu brakujących aktualizacji zabezpieczeń oraz typowych błędów konfiguracji zabezpieczeń. Więcej informacji na temat narzędzia MBSA można znaleźć w witrynie sieci Web[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Korzystając z programu Windows Server Update Services (WSUS), administratorzy mogą szybko i niezawodnie wdrożyć najnowsze aktualizacje krytyczne i aktualizacje zabezpieczeń przeznaczone dla systemów operacyjnych Microsoft Windows 2000 i nowszych, pakietów Office XP i nowszych, programu Exchange Server 2003 oraz SQL Server 2000 w systemach operacyjnych Microsoft Windows 2000 i nowszych.

Więcej informacji na temat sposobu wdrażania tej aktualizacji zabezpieczeń za pomocą programu Windows Server Update Services można znaleźć w [witrynie sieci Web programu Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Program Systems Management Server**

Program Systems Management Server (SMS) jest przeznaczonym dla przedsiębiorstw i w znacznym stopniu konfigurowalnym rozwiązaniem służącym do zarządzania aktualizacjami. Program SMS umożliwia administratorom znalezienie komputerów z systemem Windows, na których należy zainstalować aktualizację zabezpieczeń, a także przeprowadzić kontrolowane wdrożenie tych aktualizacji w całym przedsiębiorstwie, w minimalnym stopniu zakłócając przy tym pracę użytkowników końcowych. Dostępne jest kolejne wydanie programu SMS, System Center Configuration Manager 2007. Zapoznaj się także z zawartością witryny [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Więcej informacji na temat możliwości wykorzystania przez administratorów programu SMS 2003 do wdrażania aktualizacji zabezpieczeń można znaleźć w [witrynie sieci Web zarządzania poprawkami zabezpieczeń programu SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Użytkownicy programu SMS 2.0 mogą także skorzystać z narzędzia Security Update Inventory Tool (SUIT) ułatwiającego wdrożenie aktualizacji zabezpieczeń. Więcej informacji na temat programu SMS można znaleźć w witrynie sieci Web [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Uwaga** Program SMS zapewnia obsługę rozwiązań zawartych w biuletynach zabezpieczeń dzięki narzędziu Microsoft Baseline Security Analyzer. Narzędzia te mogą nie wykrywać wszystkich aktualizacji oprogramowania. W takich przypadkach administratorzy mogą wykorzystywać dostępne w programie SMS funkcje zarządzania zasobami do przyporządkowania poszczególnych aktualizacji określonym systemom. Aby uzyskać więcej informacji dotyczących tej procedury, zobacz [Wdrażanie aktualizacji oprogramowania za pomocą funkcji Software Distribution programu SMS](http://go.microsoft.com/fwlink/?linkid=33341). Niektóre aktualizacje oprogramowania wymagają od użytkownika uprawnień administratora po ponownym uruchomieniu systemu. Do zainstalowania tych aktualizacji administratorzy mogą użyć narzędzia Elevated Rights Deployment Tool (dostępnego w dodatku [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Tester zgodności aktualizacji i zestaw narzędzi do sprawdzania zgodności aplikacji**

Często aktualizacje zapisują informacje w tych samych plikach i ustawieniach rejestru niezbędnych do działania określonych aplikacji użytkownika. Może to prowadzić do niezgodności i wydłużyć czas wdrażania aktualizacji zabezpieczeń. Dzięki składnikom narzędzia [Tester zgodności aplikacji](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) znajdującego się w [Zestawie narzędzi do sprawdzania zgodności aplikacji](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) można usprawnić proces testowania i sprawdzania poprawności aktualizacji systemu Windows.

W Zestawie narzędzi do sprawdzania zgodności aplikacji znajdują się niezbędne narzędzia i dokumentacja, które umożliwiają ocenę zgodności aplikacji przed wdrożeniem systemu Microsoft Windows Vista, aktualizacji dla systemu Windows, aktualizacji zabezpieczeń firmy Microsoft lub nowej wersji programu Windows Internet Explorer w środowisku użytkownika, oraz ograniczenie problemów ze zgodnością aplikacji.

### Inne informacje:

#### Narzędzie Microsoft Windows do usuwania złośliwego oprogramowania

Firma Microsoft opublikowała zaktualizowaną wersję narzędzia Microsoft Windows Malicious Software Removal Tool, która dostępna jest w witrynach sieci Web Windows Update i Microsoft Update, poprzez usługi Windows Server Update Services i w witrynie Centrum pobierania Microsoft.

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

-   Aktualizacje zabezpieczeń są dostępne w witrynie [Centrum pobierania Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.
-   Aktualizacje dla poszczególnych platform są dostępne w [witrynie sieci Web Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizacje zabezpieczeń dostępne w tym miesiącu w witrynie Windows Update można otrzymać w witrynie Centrum pobierania Microsoft w postaci plików obrazu dysku CD zawierającego zabezpieczenia i aktualizacje krytyczne. Więcej informacji na ten temat można znaleźć w [artykule 913086 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Społeczność IT Pro Security Community**

Dowiedz się, jak poprawić bezpieczeństwo i zoptymalizować infrastrukturę informatyczną oraz weź udział w dyskusjach dotyczących zabezpieczeń wraz z innymi specjalistami branży IT, odwiedzając witrynę sieci Web społeczności [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (jęz. ang.).

#### Podziękowania

Firma Microsoft [dziękuje](http://go.microsoft.com/fwlink/?linkid=21127) wymienionym poniżej organizacjom i osobom za współpracę w dziedzinie ochrony klientów:

-   Mark Rabinovich z firmy [Visuality Systems Ltd.](http://www.visualitynq.com/), za zgłoszenie problemu opisanego w biuletynie MS10-020
-   Laurent Gaffié z firmy [stratsec](http://www.stratsec.net/), za zgłoszenie trzech problemów opisanych w biuletynie MS10-020
-   Matthew „j00ru” Jurczyk i Gynvael Coldwind z firmy [Hispasec](http://www.hispasec.com/)[Virustotal](http://www.virustotal.com/), za zgłoszenie pięciu problemów opisanych w biuletynie MS10-021
-   Tavis Ormandy z firmy [Google Inc.](http://www.google.com/), za zgłoszenie dwóch problemów opisanych w biuletynie MS10-021
-   Martin Tofall z firmy [Obsidium Software](http://www.obsidium.de/), za zgłoszenie problemu opisanego w biuletynie MS10-021
-   Lionel d'Hauenens, we współpracy z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-023
-   Fabien Perigaud z firmy [CERT-LEXSI](http://cert.lexsi.com/), za zgłoszenie problemu opisanego w biuletynie MS10-025
-   Fabien Perigaud z firmy [CERT-LEXSI](http://cert.lexsi.com/), zespół [VUPEN Vulnerability Research Team](http://www.vupen.com/) oraz zespół Vulnerability Research Team, [TELUS Security Labs](http://telussecuritylabs.com/), [Core Security Technologies](http://www.coresecurity.com/) oraz [NSFOCUS Security Team](http://www.nsfocus.com/) za współpracę i przedstawianie szczegółowych informacji dotyczących problemów z jakością oryginalnej aktualizacji zabezpieczeń MS10-025
-   Yamata Li z firmy [Palo Alto Networks](http://www.paloaltonetworks.com/), za zgłoszenie problemu opisanego w biuletynie MS10-026
-   Anonimowemu analitykowi współpracującemu z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-027
-   Bing Liu z[FortiGuard Labs](http://www.fortiguard.com/) firmy Fortinet, za zgłoszenie dwóch problemów opisanych w biuletynie MS10-028
-   Gabi Nakibly z organizacji National EW Research & Simulation Center (w Rafael), za zgłoszenie problemu opisanego w biuletynie MS10-029

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pod numerem 0 801 802 000 (Opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne. Dodatkowe informacje dotyczące możliwości skorzystania z pomocy technicznej można znaleźć w witrynie [Pomoc i obsługa techniczna firmy Microsoft](http://support.microsoft.com/).
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (13 kwietnia 2010 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.
-   Wersja 1.1 (14 kwietnia 2010 r.): Poprawiono wymaganie dotyczące ponownego uruchomienia dla biuletynu zabezpieczeń MS10-025 w sekcji **Streszczenia**. Poprawiono także zapis o instalacji Server Core dla systemów Windows Server 2008 i Windows Server 2008 R2, aby odnosił się tylko do aktualizacji KB978601 z biuletynu MS10-019.
-   Wersja 2.0 (21 kwietnia 2010 r.): Zaktualizowano w celu poinformowania klientów, że oryginalna aktualizacja zabezpieczeń MS10-025 nie chroniła systemów przed luką opisaną w tym biuletynie. Firma Microsoft zaleca, aby klienci zastosowali jedno z obejść opisanych w biuletynie MS10-025, aby ograniczyć wpływ luki na podlegające jej systemy do momentu udostępnienia poprawionej aktualizacji zabezpieczeń.
-   Wersja 3.0 (27 kwietnia 2010 r.): Zaktualizowano, aby udostępnić ponowne wydanie aktualizacji zabezpieczeń MS10-025.
-   Wersja 4.0 (13 lipca 2010 r.): Zaktualizowano, aby udostępnić ponowne wydanie aktualizacji zabezpieczeń dla systemu Windows Server 2008 i Windows Server 2008 R2 dotyczące biuletynu MS10-024.

*Built at 2014-04-18T01:50:00Z-07:00*
