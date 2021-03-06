---
TOCTitle: 'MS10-DEC'
Title: 'Podsumowanie biuletynów zabezpieczeń firmy Microsoft za grudzień 2010 r.'
ms:assetid: 'ms10-dec'
ms:contentKeyID: 61233110
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms10-dec(v=Security.10)'
---
Podsumowanie biuletynów zabezpieczeń firmy Microsoft za grudzień 2010 r.
========================================================================

Opublikowano: 14 grudnia 2010 | Zaktualizowano: 15 grudnia 2010

**Wersja:** 1.1

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za grudzień 2010 r.

Z chwilą opublikowania biuletynów zabezpieczeń za grudzień 2010 r. niniejsze podsumowanie biuletynów zastępuje powiadomienie o biuletynach zabezpieczeń wydane 9 grudnia 2010 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j. ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

15 grudnia 2010 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępni emisję internetową, w której znajdą się odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). [Zarejestruj się, aby zobaczyć emisję internetową dotyczącą biuletynów zabezpieczeń za grudzień](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;"><strong>Zbiorcza aktualizacja zabezpieczeń dla programu Internet Explorer (2416400)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa cztery luki w zabezpieczeniach programu Internet Explorer zgłoszone przez użytkowników i trzy luki w zabezpieczeniach programu Internet Explorer zgłoszone przez organizacje publiczne. Najpoważniejsze z tych luk umożliwiają zdalne wykonanie kodu, jeśli użytkownik wyświetli specjalnie spreparowaną stronę sieci Web przy użyciu programu Internet Explorer. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach sterownika czcionek OpenType (OTF) umożliwiają zdalne wykonanie kodu (2296199)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa kilka luk w zabezpieczeniach sterownika czcionek OpenType (OTF) w systemie Windows, które zostały zgłoszone przez użytkowników. Osoba atakująca może udostępnić specjalnie spreparowaną czcionkę OpenType w udziale sieciowym. Ścieżka sterowania, której dotyczy luka, zostaje wyzwolona, kiedy użytkownik przejdzie do tego udziału w Eksploratorze Windows, umożliwiając uzyskanie pełnej kontroli nad zagrożonym systemem przez specjalnie spreparowaną czcionkę. Osoba taka mogłaby wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach Harmonogramu zadań może pozwolić na podniesienie uprawnień (2305420)</strong><br />
<br />
Ta aktualizacja zabezpieczeń ma na celu usunięcie zgłoszonej przez organizację publiczną luki w zabezpieczeniach Harmonogramu zadań systemu Windows. Luka ta może umożliwić podniesienie uprawnień, jeśli osoba atakująca zaloguje się do zagrożonego systemu i uruchomi specjalnie spreparowaną aplikację. Osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania oraz być w stanie zalogować się lokalnie, aby wykorzystać możliwości stwarzane przez lukę. Nie jest możliwe wykorzystanie luki w sposób zdalny lub przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Windows Movie Maker umożliwia zdalne wykonanie kodu (2424434)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach programu Windows Movie Maker, która została zgłoszona przez organizacje publiczne. Luka ta umożliwia zdalne wykonanie kodu, gdy osoba atakująca przekona użytkownika do otwarcia prawidłowego pliku programu Windows Movie Maker, który znajduje się w tym samym katalogu sieciowym, co specjalnie spreparowany plik biblioteki. Aby atak mógł się powieść, użytkownik musi odwiedzić niezaufaną zdalną lokalizację systemu plików lub udział WebDAV i otworzyć dokument z tej lokalizacji, który następnie zostanie załadowany przez aplikację, której dotyczy luka.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Windows Media Encoder może umożliwić zdalne wykonanie kodu (2447961)</strong><br />
<br />
Ta aktualizacja zabezpieczeń ma na celu usunięcie zgłoszonej przez organizację publiczną luki w zabezpieczeniach programu Windows Media Encoder. Luka ta umożliwia zdalne wykonanie kodu, gdy osoba atakująca przekona użytkownika do otwarcia prawidłowego pliku programu Windows Media Profile (.prx), który znajduje się w tym samym katalogu sieciowym, co specjalnie spreparowany plik biblioteki. Aby atak mógł się powieść, użytkownik musi odwiedzić niezaufaną zdalną lokalizację systemu plików lub udział WebDAV i otworzyć dokument z tej lokalizacji, który następnie zostanie załadowany przez aplikację, której dotyczy luka.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach systemu Microsoft Windows może pozwolić na zdalne wykonanie kodu (2385678)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows. Luka ta umożliwia zdalne wykonanie kodu, jeśli użytkownik otworzy plik programu Windows Live Mail (z rozszerzeniem .eml lub .rss) bądź programu Microsoft Live Writer (z rozszerzeniem .wpost) znajdujący się w tym samym folderze sieciowym co specjalnie spreparowany plik biblioteki. Aby atak mógł się powieść, użytkownik musi odwiedzić niezaufaną zdalną lokalizację systemu plików lub udział WebDAV i otworzyć dokument z tej lokalizacji, który następnie zostanie załadowany przez aplikację, której dotyczy luka.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach książki adresowej systemu Windows umożliwia zdalne wykonanie kodu (2423089)</strong><br />
<br />
Ta aktualizacja zabezpieczeń ma na celu usunięcie zgłoszonej przez organizację publiczną luki w zabezpieczeniach książki adresowej systemu Windows. Luka ta umożliwia zdalne wykonanie kodu, jeśli użytkownik otworzy plik Książki adresowej systemu Windows umieszczony w tym samym folderze sieciowym, co specjalnie spreparowany plik biblioteki. Aby atak mógł się powieść, użytkownik musi odwiedzić niezaufaną zdalną lokalizację systemu plików lub udział WebDAV i otworzyć dokument z tej lokalizacji, który następnie zostanie załadowany przez aplikację, której dotyczy luka.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach związana z niebezpiecznym ładowaniem bibliotek w Kreatorze rejestrowania połączenia internetowego może umożliwić zdalne wykonanie kodu (2443105)</strong><br />
<br />
Ta aktualizacja zabezpieczeń ma na celu usunięcie zgłoszonej przez organizację publiczną luki w zabezpieczeniach Kreatora rejestrowania połączenia internetowego systemu Microsoft Windows. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „ważny” dla wszystkich obsługiwanych wersji systemów Windows XP i Windows Server 2003. Luka nie dotyczy wszystkich obsługiwanych wersji systemów Windows Vista, Windows Server 2008, Windows 7 i Windows Server 2008 R2.<br />
<br />
Luka ta umożliwia zdalne wykonanie kodu, jeśli użytkownik otworzy plik .ins lub .isp znajdujący się w tym samym folderze sieciowym, co specjalnie spreparowany plik biblioteki. Aby atak mógł się powieść, użytkownik musi odwiedzić niezaufaną zdalną lokalizację systemu plików lub udział WebDAV i otworzyć dokument z tej lokalizacji, który następnie zostanie załadowany przez aplikację, której dotyczy luka.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach sterowników trybu jądra systemu Windows umożliwiają podniesienie uprawnień (2436673)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa jedną lukę zgłoszoną przez organizacje publiczne oraz kilka luk zgłoszonych przez użytkowników, które istnieją w systemie Microsoft Windows. Luki te mogą umożliwić podniesienie uprawnień, jeśli osoba atakująca zaloguje się lokalnie i uruchomi specjalnie spreparowaną aplikację. Osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania oraz być w stanie zalogować się lokalnie, aby wykorzystać możliwości stwarzane przez luki. Nie jest możliwe wykorzystanie luk w sposób zdalny ani przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach usługi routingu i dostępu zdalnego może pozwolić na podniesienie uprawnień (2440591)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w zabezpieczeniach składnika NDProxy usługi routingu i dostępu zdalnego w systemie Microsoft Windows. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „ważny” dla wszystkich obsługiwanych wersji systemów Windows XP i Windows Server 2003. Luka nie dotyczy wszystkich obsługiwanych wersji systemów Windows Vista, Windows Server 2008, Windows 7 i Windows Server 2008 R2.<br />
<br />
Luka ta może umożliwić podniesienie uprawnień, jeśli osoba atakująca zaloguje się do zagrożonego systemu i uruchomi specjalnie spreparowaną aplikację. Osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania oraz być w stanie zalogować się lokalnie, aby wykorzystać możliwości stwarzane przez lukę. Nie jest możliwe wykorzystanie luki w sposób zdalny lub przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach interfejsu użytkownika służącego do wyrażania zgody może pozwolić na podniesienie uprawnień (2442962)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach interfejsu użytkownika (UI) służącego do wyrażania zgody, zgłoszoną przez użytkowników. Luka umożliwia podniesienie poziomu uprawnień, jeśli osoba atakująca uruchomi specjalnie spreparowaną aplikację w systemie, którego dotyczy problem. Osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania i uprawnieniami SeImpersonatePrivilege oraz być w stanie zalogować się lokalnie, aby wykorzystać możliwości stwarzane przez lukę. Nie jest możliwe wykorzystanie luki w sposób zdalny lub przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td style="border:1px solid black;"><strong>Luka w usłudze Netlogon w systemie Windows umożliwia przeprowadzenie ataku typu „odmowa usługi” (2207559)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w usłudze Netlogon RPC w zagrożonych wersjach systemu Windows Server skonfigurowanych jako kontrolery domen. Luka umożliwia osobie atakującej przeprowadzenie ataku typu „odmowa usługi”, jeśli osoba atakująca wyśle specjalnie spreparowany pakiet RPC do interfejsu usługi Netlogon RPC w zagrożonym systemie. W celu wykorzystania tej luki, osoba atakująca musi dysponować uprawnieniami administratora na komputerze podłączonym do tej samej domeny co kontroler domen zawierający tę lukę.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Odmowa usługi</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach protokołu Hyper-V umożliwia przeprowadzenie ataku typu „odmowa usługi” (2345316)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach funkcji Hyper-V systemów Windows Server 2008 i Windows Server 2008 R2, która została zgłoszona przez użytkowników. Luka umożliwia przeprowadzenie ataku typu „odmowa usługi”, jeśli do magistrali VMBus zostanie wysłany specjalnie spreparowany pakiet przez użytkownika uwierzytelnionego na jednej z maszyn wirtualnych gościa obsługiwanych przez serwer funkcji Hyper-V. Aby wykorzystać tę lukę, osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania i być w stanie wysyłać specjalnie spreparowane treści z maszyny wirtualnej gościa. Nie jest możliwe wykorzystanie luki w sposób zdalny lub przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Odmowa usługi</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach programu Microsoft Publisher umożliwiają zdalne wykonanie kodu (2292970)</strong><br />
<br />
Ta aktualizacja zabezpieczeń pozwala usunąć pięć luk w zabezpieczeniach programu Microsoft Publisher zgłoszonych przez osobę prywatną, które mogą pozwolić na zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik programu Publisher. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać pełną kontrolę nad zagrożonym systemem. Osoba taka mogłaby wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft SharePoint umożliwia zdalne wykonanie kodu (2455005)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w programie Microsoft SharePoint, która została zgłoszona przez użytkowników. Luka ta może pozwolić na zdalne wykonanie kodu w kontekście zabezpieczeń użytkownika-gościa, jeśli osoba atakująca wyśle specjalnie spreparowane żądanie SOAP do Usługi uruchamiania konwersji dokumentów w środowisku serwera SharePoint, w którym jest używana Usługa równoważenia obciążenia konwersji dokumentów. Usługa równoważenia obciążenia konwersji dokumentów i Usługa uruchamiania konwersji dokumentów nie są domyślnie włączone w systemie Microsoft Office SharePoint Server 2007.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach filtrów graficznych pakietu Microsoft Office umożliwiają zdalne wykonanie kodu (968095)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa siedem luk w zabezpieczeniach pakietu Microsoft Office, które zostały zgłoszone przez użytkowników. Omawiane luki mogą pozwolić na zdalne wykonanie kodu, jeśli użytkownik wyświetli specjalnie spreparowany plik obrazu przy użyciu pakietu Microsoft Office. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft Exchange Server umożliwia przeprowadzenie ataku typu „odmowa usługi” (2407132)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach programu Microsoft Exchange Server, która została zgłoszona przez użytkowników. Omawiana luka umożliwia przeprowadzenie ataku typu „odmowa usługi”, jeśli uwierzytelniona osoba atakująca wyśle specjalnie spreparowany komunikat sieciowy do komputera, na którym uruchomiono usługę Exchange. Sprawdzone metody działania stosowane w zaporach oraz standardowe domyślne konfiguracje zapór mogą pomóc w zabezpieczeniu sieci przed atakami spoza obszaru działania przedsiębiorstwa. Zgodnie ze standardowymi zasadami działania zaleca się, aby w systemach połączonych z Internetem była otwarta jak najmniejsza liczba portów.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Umiarkowany</a><br />
Odmowa usługi</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
</tbody>
</table>
  
Wskaźnik możliwości wykorzystania luki  
--------------------------------------
  
<span></span>
Poniższa tabela przedstawia ocenę możliwości wykorzystania luk dla każdej luki opisywanej w tym miesiącu. Luki są wymienione według malejącego poziomu oceny możliwości wykorzystania, a nie według identyfikatora CVE. Uwzględniono wyłącznie te luki, które w biuletynach mają nadany wskaźnik ważności „krytyczny” lub „ważny”.
  
**W jaki sposób korzystać z tej tabeli?**
  
Tabela ta pozwala sprawdzić prawdopodobieństwo, że w ciągu 30 dni od wydania biuletynu zabezpieczeń dla każdej z aktualizacji zabezpieczeń, których zainstalowanie może być potrzebne, opublikowany zostanie działający kod wykorzystujący lukę w zabezpieczeniach. Aby ustalić priorytety wdrażania, zapoznaj się z dostępnymi poniżej ocenami, rozpatrując je w kontekście posiadanej konfiguracji. Więcej informacji na temat znaczenia tych ocen oraz sposobu ich wyznaczania można znaleźć na stronie sieci Web [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Identyfikator biuletynu                                   | Nazwa luki w zabezpieczeniach                                                                                                                | CVE ID                                                                           | Ocena wskaźnika możliwości wykorzystania luki                                                                              | Najważniejsze uwagi                                                       |  
|-----------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Luka w zabezpieczeniach związana z uszkodzeniem stosu wartości rozmiaru w pliku pubconv.dll                                                  | [CVE-2010-2569](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Luka w zabezpieczeniach związana z przepełnieniem stosu w pliku pubconv.dll                                                                  | [CVE-2010-2570](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-097](http://go.microsoft.com/fwlink/?linkid=206689) | Luka w zabezpieczeniach związana z niebezpiecznym ładowaniem bibliotek przez Kreatora rejestrowania połączenia internetowego                 | [CVE-2010-3144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | **Informacje o tej luce są znane publicznie**                             |  
| [MS10-096](http://go.microsoft.com/fwlink/?linkid=206738) | Luka w zabezpieczeniach związana z niebezpiecznym ładowaniem bibliotek                                                                       | [CVE-2010-3147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | **Informacje o tej luce są znane publicznie**                             |  
| [MS10-092](http://go.microsoft.com/fwlink/?linkid=203463) | Luka w zabezpieczeniach programu Harmonogram zadań                                                                                           | [CVE-2010-3338](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | **Ta luka w zabezpieczeniach jest wykorzystywana w Internecie**           |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | Luka w zabezpieczeniach związana z uszkodzeniem pamięci obiektu HTML                                                                         | [CVE-2010-3340](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | Luka w zabezpieczeniach związana z uszkodzeniem pamięci obiektu HTML                                                                         | [CVE-2010-3343](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | Luka w zabezpieczeniach związana z uszkodzeniem pamięci elementu HTML                                                                        | [CVE-2010-3345](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | Luka w zabezpieczeniach związana z uszkodzeniem pamięci elementu HTML                                                                        | [CVE-2010-3346](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Luka w zabezpieczeniach sterownika Win32k związana z przepełnieniem buforu                                                                   | [CVE-2010-3939](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | **Informacje o tej luce są znane publicznie**                             |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Luka w zabezpieczeniach sterownika Win32k związana z podwójnym zwolnieniem wskaźnika PFE                                                     | [CVE-2010-3940](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Luka w zabezpieczeniach sterownika Win32K związana z łączeniem kursorów                                                                      | [CVE-2010-3943](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Luka w zabezpieczeniach sterownika Win32K związana z uszkodzeniem pamięci                                                                    | [CVE-2010-3944](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | Luka w zabezpieczeniach konwertera obrazów FlashPix związana z przepełnieniem buforu                                                         | [CVE-2010-3951](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-091](http://go.microsoft.com/fwlink/?linkid=203895) | Luka w zabezpieczeniach związana z podwójnym zwolnieniem czcionek OpenType                                                                   | [CVE-2010-3957](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-091](http://go.microsoft.com/fwlink/?linkid=203895) | Luka w zabezpieczeniach związana z tabelą CMAP czcionek OpenType                                                                             | [CVE-2010-3959](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-100](http://go.microsoft.com/fwlink/?linkid=204906) | Luka w zabezpieczeniach interfejsu użytkownika służącego do wyrażania zgody związana z podszywaniem                                          | [CVE-2010-3961](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | Luka w zabezpieczeniach związana z uszkodzeniem niezainicjowanej pamięci                                                                     | [CVE-2010-3962](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | **Ta luka w zabezpieczeniach jest aktualnie wykorzystywana w Internecie** |  
| [MS10-099](http://go.microsoft.com/fwlink/?linkid=206365) | Luka w zabezpieczeniach składnika NDProxy jądra związana z przepełnieniem buforu                                                             | [CVE-2010-3963](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-104](http://go.microsoft.com/fwlink/?linkid=206469) | Luka w zabezpieczeniach związana z nieprawidłowo utworzonym żądaniem i pozwalająca na wykonanie kodu                                         | [CVE-2010-3964](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-094](http://go.microsoft.com/fwlink/?linkid=206699) | Luka w zabezpieczeniach związana z niebezpiecznym ładowaniem bibliotek                                                                       | [CVE-2010-3965](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | **Informacje o tej luce są znane publicznie**                             |  
| [MS10-095](http://go.microsoft.com/fwlink/?linkid=206683) | Luka w zabezpieczeniach związana z niebezpiecznym ładowaniem bibliotek przez usługę BranchCache                                              | [CVE-2010-3966](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                    |  
| [MS10-093](http://go.microsoft.com/fwlink/?linkid=206698) | Luka w zabezpieczeniach związana z niebezpiecznym ładowaniem bibliotek                                                                       | [CVE-2010-3967](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny spójny kod wykorzystujący lukę          | **Informacje o tej luce są znane publicznie**                             |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Luka w zabezpieczeniach związana z uszkodzeniem pamięci na skutek nieprawidłowego indeksu do tablicy w pliku Pubconv.dll                     | [CVE-2010-2571](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Luka w zabezpieczeniach sterownika Win32k związana z podwójnym zwolnieniem                                                                   | [CVE-2010-3941](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Luka w zabezpieczeniach sterownika Win32k związana z czcionkami WriteAV                                                                      | [CVE-2010-3942](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | Luka w zabezpieczeniach konwertera obrazów CGM związana z przepełnieniem buforu                                                              | [CVE-2010-3945](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | Luka w zabezpieczeniach konwertera obrazów PICT związana z przepełnieniem liczby całkowitej                                                  | [CVE-2010-3946](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | Luka w zabezpieczeniach konwertera obrazów TIFF związana z przepełnieniem stosu                                                              | [CVE-2010-3947](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | Luka w zabezpieczeniach konwertera obrazów TIFF związana z przepełnieniem buforu                                                             | [CVE-2010-3949](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | Luka w zabezpieczeniach konwertera obrazów TIFF związana z uszkodzeniem pamięci                                                              | [CVE-2010-3950](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | Luka w zabezpieczeniach konwertera obrazów FlashPix związana z uszkodzeniem stosu                                                            | [CVE-2010-3952](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Luka w zabezpieczeniach związana z uszkodzeniem pamięci podczas indeksowania tablicy                                                         | [CVE-2010-3955](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-091](http://go.microsoft.com/fwlink/?linkid=203895) | Luka w zabezpieczeniach związana z indeksowaniem czcionek OpenType                                                                           | [CVE-2010-3956](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobnie niespójny kod wykorzystujący lukę      | (Brak)                                                                    |  
| [MS10-101](http://go.microsoft.com/fwlink/?linkid=201319) | Luka w zabezpieczeniach usługi Netlogon RPC związana z odwołaniem odniesienia do wskaźnika pustego i umożliwiająca atak typu „odmowa usługi” | [CVE-2010-2742](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – działający kod wykorzystujący lukę mało prawdopodobny | Jest to luka umożliwiająca wyłącznie atak typu „odmowa usługi”            |  
| [MS10-106](http://go.microsoft.com/fwlink/?linkid=204624) | Luka w zabezpieczeniach programu Exchange Server związana z nieskończoną pętlą                                                               | [CVE-2010-3937](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – działający kod wykorzystujący lukę mało prawdopodobny | Jest to luka umożliwiająca wyłącznie atak typu „odmowa usługi”            |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Luka w zabezpieczeniach programu Microsoft Publisher związana z uszkodzeniem pamięci                                                         | [CVE-2010-3954](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – działający kod wykorzystujący lukę mało prawdopodobny | (Brak)                                                                    |  
| [MS10-102](http://go.microsoft.com/fwlink/?linkid=205309) | Luka w zabezpieczeniach magistrali Hyper-V VMBus                                                                                             | [CVE-2010-3960](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – działający kod wykorzystujący lukę mało prawdopodobny | Jest to luka umożliwiająca wyłącznie atak typu „odmowa usługi”            |
  
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
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
Brak
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
<td style="border:1px solid black;">
Brak
</td>
<td style="border:1px solid black;">
Brak
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55)  
(Krytyczny)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48)  
(Ważny)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8)  
(Krytyczny)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
(Ważny)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50)  
(Ważny)
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
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
Brak
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
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b)  
(Krytyczny)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47)  
(Krytyczny)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
(Ważny)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f)  
(Krytyczny)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de)  
(Ważny)
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
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
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
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5)<sup>[1]</sup>
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664)  
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
Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a)  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82)<sup>[1]</sup>
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408)  
(Ważny)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348)  
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
<th colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f)\*\*  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942)\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284)\*\*  
(Krytyczny)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729)\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126)\*\*  
(Ważny)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed)\*  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee)  
(Ważny)
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
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164)  
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
<th colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384)  
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
<th colspan="14">
System Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Brak
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach x64
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64)\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a)\*\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118)\*  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach Itanium
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90)  
(Ważny)
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

**\*Luka w zabezpieczeniach dotyczy instalacji Server Core.** Ta aktualizacja ma zastosowanie, z takim samym wskaźnikiem ważności, w przypadku obsługiwanych wersji systemu Windows Server 2008 lub Windows Server 2008 R2, niezależnie od tego, czy zostały zainstalowane przy użyciu opcji instalacji Server Core. Więcej informacji na temat tej opcji instalacji można znaleźć w artykułach TechNet, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) i [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (jęz. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core.** Luki usuwane przez tę aktualizację zabezpieczeń nie dotyczą obsługiwanych wersji systemu Windows Server 2008 ani Windows Server 2008 R2, jeżeli systemy te zostały zainstalowane przy użyciu opcji instalacji Server Core. Więcej informacji na temat tej opcji instalacji można znaleźć w artykułach TechNet, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) i [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (jęz. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Uwaga dotycząca biuletynu MS10-093**

<sup>[1]</sup>Program Windows Movie Maker 2.6 jest dostępny jako opcja do pobrania i można go zainstalować we wskazanych systemach operacyjnych.

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
Pakiety Microsoft Office i ich składniki
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://go.microsoft.com/fwlink/?linkid=198156)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://go.microsoft.com/fwlink/?linkid=147425)
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
Microsoft Office XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2002 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5)  
(KB2284692)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b)<sup>[1]</sup>
(KB2289162)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e)  
(KB2284695)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd)<sup>[1]</sup>
(KB2289163)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35)  
(KB2284697)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290)  
(KB2288931)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (wersje 32-bitowe)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (wersje 32-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2)  
(KB2409055)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (wersje 32-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53)  
(KB2289078)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (wersje 64-bitowe)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (wersje 64-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966)  
(KB2409055)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (wersje 64-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082)  
(KB2289078)  
(Brak wskaźnika ważności<sup>[2]</sup>)
</td>
</tr>
<tr>
<th colspan="3">
Inne programy pakietu Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://go.microsoft.com/fwlink/?linkid=198156)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://go.microsoft.com/fwlink/?linkid=147425)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306)  
(KB2456849)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f)  
(KB2431831)  
(Ważny)
</td>
</tr>
</table>
 
**Uwagi dotyczące biuletynu MS10-105**

<sup>[1]</sup>Użytkownicy wskazanego oprogramowania również muszą zainstalować aktualizację pakietu Microsoft Office z biuletynu MS10-087 w celu ochrony przed lukami w zabezpieczeniach opisanymi w biuletynie MS10-105.

<sup>[2]</sup>Do tej aktualizacji nie stosuje się wskaźników ważności, ponieważ omawiane w biuletynie luki w zabezpieczeniach nie mają wpływu na to oprogramowanie. Jednak w ramach dodatkowego wzmocnienia ochrony przed ewentualnymi nowymi kierunkami ataku, które mogą zostać rozpoznane w przyszłości, firma Microsoft zaleca, aby użytkownicy tego oprogramowania zainstalowali omawianą aktualizację zabezpieczeń.

#### Oprogramowanie serwerów firmy Microsoft

 
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
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-104**](http://go.microsoft.com/fwlink/?linkid=206469)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://go.microsoft.com/fwlink/?linkid=204624)
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
Brak
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 z dodatkiem Service Pack 2 (wersje 32-bitowe)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 z dodatkiem Service Pack 2 (wersje 32-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60)  
(KB2433089)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 z dodatkiem Service Pack 2 (wersje 64-bitowe)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 z dodatkiem Service Pack 2 (wersje 64-bitowe)](http://www.microsoft.com/downloads/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3)  
(KB2433089)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-104**](http://go.microsoft.com/fwlink/?linkid=206469)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://go.microsoft.com/fwlink/?linkid=204624)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
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
Microsoft Exchange Server 2007 z dodatkiem Service Pack 2 dla systemów opartych na procesorach x64
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 z dodatkiem Service Pack 2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62)  
(KB2407132)  
(Umiarkowany)
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

**Narzędzie Microsoft Baseline Security Analyzer**

Narzędzie Microsoft Baseline Security Analyzer umożliwia administratorom skanowanie lokalnych i zdalnych systemów w poszukiwaniu brakujących aktualizacji zabezpieczeń oraz typowych błędów konfiguracji zabezpieczeń. Więcej informacji na temat narzędzia MBSA można znaleźć w witrynie sieci Web[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Korzystając z programu Windows Server Update Services (WSUS), administratorzy mogą szybko i niezawodnie wdrożyć najnowsze aktualizacje krytyczne i aktualizacje zabezpieczeń przeznaczone dla systemów operacyjnych Microsoft Windows 2000 i nowszych, pakietów Office XP i nowszych, programu Exchange Server 2003 oraz SQL Server 2000 w systemach operacyjnych Microsoft Windows 2000 i nowszych.

Więcej informacji na temat sposobu wdrażania tej aktualizacji zabezpieczeń za pomocą programu Windows Server Update Services można znaleźć w [witrynie sieci Web programu Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**SystemCenter Configuration Manager 2007**

Program Configuration Manager 2007 Software Update Management ułatwia realizację złożonych zadań dostarczania aktualizacji do systemów IT w firmie i zarządzania nimi. Dzięki programowi Configuration Manager 2007 administratorzy mogą dostarczać aktualizacje produktów firmy Microsoft do całej gamy urządzeń, takich jak komputery stacjonarne, laptopy, serwery i urządzenia mobilne.

System zautomatyzowanej oceny zagrożeń w programie Configuration Manager 2007 wykrywa potrzebne aktualizacje i sporządza raporty dotyczące zalecanych czynności. Funkcja Software Update Management w programie Configuration Manager 2007 powstała w oparciu o usługi Microsoft Windows Software Update Services (WSUS) — dobrze sprawdzoną infrastrukturę aktualizacji znaną administratorom na całym świecie. Więcej informacji na temat możliwości wykorzystania przez administratorów programu Configuration Manager 2007 do wdrażania aktualizacji zawiera dokument [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Więcej informacji dotyczących programu Configuration Manager znajduje się na stronie [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Program Systems Management Server (SMS) jest przeznaczonym dla przedsiębiorstw i w znacznym stopniu konfigurowalnym rozwiązaniem służącym do zarządzania aktualizacjami. Program SMS umożliwia administratorom znalezienie komputerów z systemem Windows, na których należy zainstalować aktualizację zabezpieczeń, a także przeprowadzić kontrolowane wdrożenie tych aktualizacji w całym przedsiębiorstwie, w minimalnym stopniu zakłócając przy tym pracę użytkowników końcowych.

**Uwaga** Program System Management Server 2003 od 12 stycznia 2010 roku nie jest objęty podstawową pomocą techniczną. Więcej informacji na temat cyklu pomocy technicznej dla produktów można znaleźć na stronie . Obecnie dostępna jest kolejna wersja programu SMS — System Center Configuration Manager 2007; zapoznaj się z wcześniejszą sekcją **SystemCenter Configuration Manager 2007**.

Więcej informacji na temat możliwości wykorzystania przez administratorów programu SMS 2003 do wdrażania aktualizacji zabezpieczeń można znaleźć w artykule [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Więcej informacji na temat programu SMS można znaleźć w witrynie sieci Web [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Uwaga** Program SMS zapewnia obsługę rozwiązań zawartych w biuletynach zabezpieczeń dzięki narzędziu Microsoft Baseline Security Analyzer. Narzędzia te mogą nie wykrywać wszystkich aktualizacji oprogramowania. W takich przypadkach administratorzy mogą wykorzystywać dostępne w programie SMS funkcje zarządzania zasobami do przyporządkowania poszczególnych aktualizacji określonym systemom. Aby uzyskać więcej informacji dotyczących tej procedury, zobacz [Wdrażanie aktualizacji oprogramowania za pomocą funkcji Software Distribution programu SMS](http://go.microsoft.com/fwlink/?linkid=33341). Niektóre aktualizacje oprogramowania wymagają od użytkownika uprawnień administratora po ponownym uruchomieniu systemu. Do zainstalowania tych aktualizacji administratorzy mogą użyć narzędzia Elevated Rights Deployment Tool (dostępnego w dodatku [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)).

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

-   Aniway z firmy [VeriSign iDefense Labs](http://labs.idefense.com/) za zgłoszenie problemu opisanego w biuletynie MS10-090
-   Nicolas Joly z firmy [VUPEN Vulnerability Research Team](http://www.vupen.com/), za zgłoszenie problemu opisanego w biuletynie MS10-090
-   Stephen Fewer, współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-090
-   [Peter Vreugdenhil](http://vreugdenhilresearch.nl/), współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-090
-   [Yosuke Hasegawa](http://utf-8.jp/), za współpracę nad problemem opisanym w biuletynie MS10-090
-   Jose Antonio Vazquez Gonzalez z firmy [VeriSign iDefense Labs](http://labs.idefense.com/) za zgłoszenie problemu opisanego w biuletynie MS10-090
-   Marc Schoenefeld z zespołu [Red Hat Security Response Team](https://www.redhat.com/security/team/), we współpracy z zespołem [Opera Security Team](http://www.opera.com/security/), za zgłoszenie problemu opisanego w biuletynie MS10-091
-   Marc Schoenefeld z zespołu [Red Hat Security Response Team](https://www.redhat.com/security/team/), za zgłoszenie problemu opisanego w biuletynie MS10-091
-   Paul-Kenji Cahier Furuya, za zgłoszenie problemu opisanego w biuletynie MS10-091
-   Sergey Golovanov, Alexander Gostev, Maxim Golovkin i Alexey Monastyrsky z firmy [Kaspersky Lab](http://usa.kaspersky.com/), a także Vitaly Kiktenko i Alexander Saprykin z firmy [Design and Test Lab](http://www.dnt-lab.com/), za zgłoszenie problemu opisanego w biuletynie MS10-092
-   Liam O Murchu z firmy [Symantec](http://www.symantec.com/index.jsp), za zgłoszenie problemu opisanego w biuletynie MS10-092
-   Alexandr Matrosov, Eugene Rodionov, Juraj Malcho i David Harley z firmy [ESET](http://www.eset.com/), za zgłoszenie problemu opisanego w biuletynie MS10-092
-   Haifei Li z [FortiGuard Labs firmy Fortinet](http://www.fortiguard.com/), za zgłoszenie problemu opisanego w biuletynie MS10-095
-   Simon Raner z firmy [ACROS Security](http://www.acrossecurity.com/), za zgłoszenie problemu opisanego w biuletynie MS10-096
-   HD Moore z firmy [Rapid7](http://www.rapid7.com/), za zgłoszenie problemu opisanego w biuletynie MS10-096
-   Muhaimin Dzulfakar z firmy [NGS Software](http://www.ngssoftware.com/) za zgłoszenie problemu opisanego w biuletynie MS10-096
-   Muhaimin Dzulfakar z firmy [NGS Software](http://www.ngssoftware.com/) za zgłoszenie problemu opisanego w biuletynie MS10-097
-   Tarjei Mandt z firmy [Norman](http://www.norman.com/), za zgłoszenie czterech problemów opisanych w biuletynie MS10-098
-   Stéfan Le Berre z firmy [Sysdream](http://www.sysdream.com/), za zgłoszenie problemu opisanego w biuletynie MS10-098
-   Honggang Ren z firmy [Fortinet's FortiGuard Labs](http://www.fortiguard.com/), za zgłoszenie problemu opisanego w biuletynie MS10-099
-   Cesar Cerrudo z firmy [Argeniss](http://www.argeniss.com/), za zgłoszenie problemu opisanego w biuletynie MS10-100
-   Matthias Dieter Wallnöfer i Andrew Bartlett z firmy The Samba Team, za zgłoszenie problemu opisanego w biuletynie MS10-101
-   [HP](http://www.hp.com/) i [techit](http://www.techit.de/), za zgłoszenie problemu opisanego w biuletynie MS10-102
-   Chaouki Bekrar z firmy [VUPEN Vulnerability Research Team](http://www.vupen.com/), za zgłoszenie pięciu problemów opisanych w biuletynie MS10-103
-   Oleksandr Mirosh, współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-104
-   Yamata Li z firmy [Palo Alto Networks](http://www.paloaltonetworks.com/) za zgłoszenie dwóch problemów opisanych w biuletynie MS10-105
-   Alin Rad Pop z firmy [Secunia Research](http://secunia.com/), za zgłoszenie problemu opisanego w biuletynie MS10-105
-   Carsten Eiram z firmy [Secunia Research](http://secunia.com/), za zgłoszenie trzech problemów opisanych w biuletynie MS10-105
-   Dyon Balding z firmy [Secunia Research](http://secunia.com/) za zgłoszenie dwóch problemów opisanych w biuletynie MS10-105
-   Oleksandr Mirosh, współpracujący z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-106

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pod numerem 0 801 802 000 (opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne. Dodatkowe informacje dotyczące możliwości skorzystania z pomocy technicznej można znaleźć w witrynie [Pomoc i obsługa techniczna firmy Microsoft](http://support.microsoft.com/).
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (14 grudnia 2010 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.
-   V1.1 (15 grudnia 2010 r.): Dodano wyjaśnienie, że użytkownicy pakietów Microsoft Office XP i Microsoft Office 2003 muszą zainstalować aktualizację z biuletynu MS10-087 w celu ochrony przed lukami w zabezpieczeniach opisanymi w biuletynie MS10-105.

*Built at 2014-04-18T01:50:00Z-07:00*
