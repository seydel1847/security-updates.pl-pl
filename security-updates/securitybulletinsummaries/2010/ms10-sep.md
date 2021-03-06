---
TOCTitle: 'MS10-SEP'
Title: 'Podsumowanie biuletynów zabezpieczeń firmy Microsoft za wrzesień 2010 r.'
ms:assetid: 'ms10-sep'
ms:contentKeyID: 61233119
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms10-sep(v=Security.10)'
---
Podsumowanie biuletynów zabezpieczeń firmy Microsoft za wrzesień 2010 r.
========================================================================

Opublikowano: 14 września 2010 | Zaktualizowano: 26 października 2011

**Wersja:** 6.1

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za wrzesień 2010 r.

Z chwilą opublikowania biuletynów za wrzesień 2010 r. niniejsze podsumowanie biuletynów zastępuje powiadomienie o biuletynach zabezpieczeń wydane 9 września 2010 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j. ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

15 września 2010 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępni emisję internetową, w której znajdą się odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). [Zarejestruj się, aby zobaczyć emisję internetową dotyczącą biuletynów zabezpieczeń za wrzesień](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454433&eventcategory=4&culture=en-us&countrycode=us). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

W odniesieniu do pozaplanowych biuletynów zabezpieczeń, MS10-070, dodanych do wersji 3.0 niniejszego podsumowania biuletynów, 28 września 2010 r. o godz. 13:00 czasu Pacyfiku (godz. 22:00 czasu środkowoeuropejskiego) firma Microsoft udostępni transmisję internetową, zawierającą odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). [Zarejestruj się teraz, by wziąć udział w transmisji internetowej 28 września o godz. 22:00](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032464130&culture=en-us). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=200505">MS10-061</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach usługi buforu wydruku może pozwolić na zdalne wykonanie kodu (2347290)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach usługi buforu wydruku, która została zgłoszona przez organizację publiczną. Omawiana luka może umożliwić zdalne wykonanie kodu, jeśli osoba atakująca wyśle specjalnie spreparowane żądanie wydruku do systemu zagrożonego przez lukę, w którym interfejs buforu wydruku jest udostępniony za pośrednictwem RPC. W żadnym z obecnie obsługiwanych systemów operacyjnych Windows drukarki nie są domyślnie udostępnione.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190884">MS10-062</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach kodera-dekodera MPEG-4 może pozwolić na zdalne wykonanie kodu (975558)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach kodera-dekodera MPEG-4, która została zgłoszona przez użytkowników. Luka ta umożliwia zdalne wykonanie kodu, gdy użytkownik otworzy specjalnie spreparowany plik multimedialny lub odbierze specjalnie spreparowany strumień danych z witryny sieci Web lub dowolnej aplikacji dostarczającej treści z sieci Web. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=200378">MS10-063</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach procesora skryptów Unicode umożliwia zdalne wykonanie kodu (2320113)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w zabezpieczeniach procesora skryptów Unicode. Luka ta może pozwolić na zdalne wykonanie kodu, jeśli użytkownik wyświetli specjalnie spreparowany dokument lub stronę sieci Web przy użyciu aplikacji obsługującej osadzone czcionki OpenType. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=200727">MS10-064</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft Outlook może pozwolić na zdalne wykonanie kodu (2315011)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach zgłoszoną przez użytkowników. Luka ta może umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy lub wyświetli w trybie podglądu specjalnie spreparowaną wiadomość e-mail za pomocą zagrożonej wersji programu Microsoft Outlook połączonego z serwerem programu Exchange w trybie online. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=199537">MS10-065</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach</strong> <strong>programu Microsoft Internet Information Services (IIS) umożliwiają zdalne wykonanie kodu (2267960)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach programu Internet Information Services (IIS) zgłoszone przez użytkowników i jedną lukę w zabezpieczeniach tego programu zgłoszoną przez organizacje publiczne. Najpoważniejsza z tych luk umożliwia zdalne wykonanie kodu, jeśli klient wyśle do serwera specjalnie spreparowane żądanie HTTP. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać pełną kontrolę nad systemem, którego dotyczy luka.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=197105">MS10-066</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach w zdalnym wywołaniu procedury</strong> <strong>umożliwia zdalne wykonanie kodu (982802)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „ważny” dla wszystkich obsługiwanych wersji systemów Windows XP i Windows Server 2003. Luka nie dotyczy wszystkich obsługiwanych wersji systemów Windows Vista, Windows Server 2008, Windows 7 i Windows Server 2008 R2.<br />
<br />
Luka w zabezpieczeniach umożliwia zdalne wykonanie kodu, jeśli osoba atakująca wyśle specjalnie spreparowaną odpowiedź RPC na żądanie RPC zainicjowane przez klienta. Osoba atakująca, której uda się wykorzystać tę lukę, mogłaby wykonać dowolny kod i uzyskać pełną kontrolę nad systemem, którego dotyczy luka. Osoba atakująca musi przekonać użytkownika do zainicjowania połączenia RPC ze złośliwym serwerem znajdującym się pod jej kontrolą. Osoba atakująca nie może zdalnie wykorzystać tej luki bez udziału użytkownika.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=197102">MS10-067</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach konwerterów tekstu programu WordPad może umożliwić zdalne wykonanie kodu (2259922)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „ważny” dla wszystkich obsługiwanych wersji systemów Windows XP i Windows Server 2003. Luka nie dotyczy wszystkich obsługiwanych wersji systemów Windows Vista, Windows Server 2008, Windows 7 i Windows Server 2008 R2.<br />
<br />
Luka ta może umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik za pomocą programu WordPad. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190509">MS10-068</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach usługi podsystemu lokalnego uwierzytelniania zabezpieczeń może pozwolić na podniesienie uprawnień (983539)</strong><br />
<br />
Ta aktualizacja zabezpieczeń pozwala usunąć zgłoszoną przez użytkowników lukę w zabezpieczeniach usługi Active Directory, trybu aplikacji usługi Active Directory (ADAM) oraz usługi Active Directory Lightweight Directory Service (AD LDS). Luka umożliwia podniesienie poziomu uprawnień, jeśli uwierzytelniona osoba atakująca wyśle specjalnie spreparowaną wiadomość LDAP do nasłuchującego serwera LSASS. Aby pomyślnie wykorzystać tę lukę w zabezpieczeniach, osoba atakująca musi posiadać konto członka w docelowej domenie systemu Windows. Jednakże stacja robocza osoby atakującej nie musi być połączona z daną domeną systemu Windows.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=197093">MS10-069</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach Podsystemu wykonawczego serwera klienta w systemie Windows może pozwolić na podniesienie poziomu uprawnień (2121546)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „ważny” dla wszystkich obsługiwanych wersji systemów Windows XP i Windows Server 2003. Luka nie dotyczy wszystkich obsługiwanych wersji systemów Windows Vista, Windows Server 2008, Windows 7 i Windows Server 2008 R2.<br />
<br />
Luka ta mogłaby umożliwić podniesienie poziomu uprawnień, jeśli osoba atakująca zalogowałaby się na zagrożony luką system z chińskimi, japońskimi lub koreańskimi ustawieniami regionalnymi. Osoba atakująca, której udałoby się wykorzystać tę lukę, mogłaby wówczas instalować programy, przeglądać, zmieniać lub usuwać dane oraz tworzyć nowe konta z pełnymi prawami użytkownika.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=202409">MS10-070</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach usługi ASP.NET umożliwia ujawnienie informacji (2418042)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach usługi ASP.NET, która została zgłoszona przez organizację publiczną. Luka ta może zezwalać na ujawnienie informacji. Osoba atakująca, której udałoby się wykorzystać tę lukę w zabezpieczeniach, mogłaby odczytać dane, np. wyświetlić stan widoku, zaszyfrowane przez serwer. Lukę tę można również wykorzystać do naruszenia danych, a w konsekwencji do odszyfrowania i naruszenia danych zaszyfrowanych przez serwer. Związane z tą luką niebezpieczeństwo ujawnienia zawartości pliku nie dotyczy oprogramowania Microsoft .NET Framework w wersji starszej niż Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Ujawnienie informacji</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
Wskaźnik możliwości wykorzystania luki  
--------------------------------------
  
<span></span>
Poniższa tabela przedstawia ocenę możliwości wykorzystania luk dla każdej luki opisywanej w tym miesiącu. Luki są wymienione według malejącego poziomu oceny możliwości wykorzystania, a nie według identyfikatora CVE. Uwzględniono wyłącznie te luki, które w biuletynach mają nadany wskaźnik ważności „krytyczny” lub „ważny”.
  
**W jaki sposób** **korzystać z tej tabeli?**
  
Tabela ta pozwala sprawdzić prawdopodobieństwo, że w ciągu 30 dni od wydania biuletynu zabezpieczeń dla każdej z aktualizacji zabezpieczeń, których zainstalowanie może być potrzebne, opublikowany zostanie działający kod wykorzystujący lukę w zabezpieczeniach. Aby ustalić priorytety wdrażania, zapoznaj się z dostępnymi poniżej ocenami, rozpatrując je w kontekście posiadanej konfiguracji. Więcej informacji na temat znaczenia tych ocen oraz sposobu ich dokonywania można znaleźć na stronie sieci Web [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Identyfikator biuletynu                                   | Nazwa luki w zabezpieczeniach                                                                                             | CVE ID                                                                           | Ocena wskaźnika możliwości wykorzystania luki                                                                              | Najważniejsze uwagi                                                                                                                   |  
|-----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-062](http://go.microsoft.com/fwlink/?linkid=190884) | Luka w zabezpieczeniach kodera-dekodera MPEG-4                                                                            | [CVE-2010-0818](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0818) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | Wykonanie kodu jest mniej prawdopodobne w systemach Windows Vista ze względu na dodatkowe ograniczenia zagrożeń związanych ze stosem. |  
| [MS10-068](http://go.microsoft.com/fwlink/?linkid=190509) | Luka w zabezpieczeniach usługi LSASS związana z przepełnieniem stosu                                                      | [CVE-2010-0820](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0820) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                |  
| [MS10-069](http://go.microsoft.com/fwlink/?linkid=197093) | Luka w zabezpieczeniach podsystemu CSRSS umożliwiająca lokalne podniesienie poziomu uprawnień                             | [CVE-2010-1891](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1891) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                |  
| [MS10-067](http://go.microsoft.com/fwlink/?linkid=197102) | Luka w zabezpieczeniach związana z uszkodzeniem pamięci konwertera tekstu programu WordPad Word 97                        | [CVE-2010-2563](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2563) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                |  
| [MS10-066](http://go.microsoft.com/fwlink/?linkid=197105) | Luka w zabezpieczeniach zdalnego wywołania procedury RPC związana z uszkodzeniem pamięci                                  | [CVE-2010-2567](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2567) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                |  
| [MS10-061](http://go.microsoft.com/fwlink/?linkid=200505) | Luka w zabezpieczeniach usługi buforu wydruku związana z podszywaniem                                                     | [CVE-2010-2729](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2729) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | **Ta luka w zabezpieczeniach jest aktualnie** **wykorzystywana w Internecie.**                                                        |  
| [MS10-070](http://go.microsoft.com/fwlink/?linkid=202409) | Luka w zabezpieczeniach usługi ASP.NET związana z atakiem typu „padding oracle”                                           | [CVE-2010-3332](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3332) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | **Ta luka w zabezpieczeniach jest aktualnie wykorzystywana w Internecie**                                                             |  
| [MS10-065](http://go.microsoft.com/fwlink/?linkid=199537) | Luka w zabezpieczeniach związana z obejściem uwierzytelniania katalogu                                                    | [CVE-2010-2731](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2731) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | **Informacje o tej luce są znane publicznie.**                                                                                        |  
| [MS10-063](http://go.microsoft.com/fwlink/?linkid=200378) | Luka w zabezpieczeniach aparatu analizy czcionki Uniscribe związana z uszkodzeniem pamięci                                | [CVE-2010-2738](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2738) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                |  
| [MS10-064](http://go.microsoft.com/fwlink/?linkid=200727) | Luka w zabezpieczeniach programu Outlook związana z przepełnieniem buforu opartego na stosie                              | [CVE-2010-2728](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2728) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                                |  
| [MS10-065](http://go.microsoft.com/fwlink/?linkid=199537) | Luka w zabezpieczeniach związana z nagłówkiem żądania i przepełnieniem buforu                                             | [CVE-2010-2730](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2730) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) — prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                                |  
| [MS10-065](http://go.microsoft.com/fwlink/?linkid=199537) | Luka w zabezpieczeniach programu IIS związana z powtórzonym żądaniem parametrów i umożliwiająca atak typu „odmowa usługi” | [CVE-2010-1899](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1899) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - działający kod wykorzystujący lukę mało prawdopodobny | Jest to luka umożliwiająca wyłącznie atak typu „odmowa usługi”                                                                        |
  
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
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator** **biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-061**](http://go.microsoft.com/fwlink/?linkid=200505)
</td>
<td style="border:1px solid black;">
[**MS10-062**](http://go.microsoft.com/fwlink/?linkid=190884)
</td>
<td style="border:1px solid black;">
[**MS10-063**](http://go.microsoft.com/fwlink/?linkid=200378)
</td>
<td style="border:1px solid black;">
[**MS10-065**](http://go.microsoft.com/fwlink/?linkid=199537)
</td>
<td style="border:1px solid black;">
[**MS10-066**](http://go.microsoft.com/fwlink/?linkid=197105)
</td>
<td style="border:1px solid black;">
[**MS10-067**](http://go.microsoft.com/fwlink/?linkid=197102)
</td>
<td style="border:1px solid black;">
[**MS10-068**](http://go.microsoft.com/fwlink/?linkid=190509)
</td>
<td style="border:1px solid black;">
[**MS10-069**](http://go.microsoft.com/fwlink/?linkid=197093)
</td>
<td style="border:1px solid black;">
[**MS10-070**](http://go.microsoft.com/fwlink/?linkid=202409)
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
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=93faba6b-0a85-4acc-b527-a012bbf56b13)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2084a01c-2a91-4650-8665-7053015f2083)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a1d47f30-c1fc-4b9d-8829-3bad1224006a)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=555864c3-9114-4988-8526-7bf545a27706)  
(KB2124261)  
(Ważny)  
IIS Authentication:  
[Internet Information Services 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=ae55787e-4a5c-48d5-aedf-0abada514938)  
(KB2290570)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7ad0f2cf-03dc-49a0-a16e-17fed0c01cc6)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fc4369ec-864a-42ae-a850-b006872241fe)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Tryb aplikacji usługi Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=6554f98f-4dc5-4784-b92c-b0aae1fa22ca)  
(KB982000)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=20091358-7127-4ace-bf96-4319461ad305)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46)  
(KB2418241)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780)  
(KB2416468)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9f7f3737-056d-44bd-b644-51093b5b501b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b27f310f-6ecc-4abb-8944-9fc24c66e077)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0b28bfac-783d-4c89-988b-4123c0343855)  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3349b12b-621e-48bc-9c57-489c7a56920d)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7567986a-261d-4def-9fa5-c667994c7844)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Tryb aplikacji usługi Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=5bc00f9a-3028-4c9d-be06-f2b78fa444c4)  
(KB982000)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=107eb958-b60f-40ae-a785-5d5b4d13d8c6)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46)  
(KB2418241)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780)  
(KB2416468)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-061**](http://go.microsoft.com/fwlink/?linkid=200505)
</td>
<td style="border:1px solid black;">
[**MS10-062**](http://go.microsoft.com/fwlink/?linkid=190884)
</td>
<td style="border:1px solid black;">
[**MS10-063**](http://go.microsoft.com/fwlink/?linkid=200378)
</td>
<td style="border:1px solid black;">
[**MS10-065**](http://go.microsoft.com/fwlink/?linkid=199537)
</td>
<td style="border:1px solid black;">
[**MS10-066**](http://go.microsoft.com/fwlink/?linkid=197105)
</td>
<td style="border:1px solid black;">
[**MS10-067**](http://go.microsoft.com/fwlink/?linkid=197102)
</td>
<td style="border:1px solid black;">
[**MS10-068**](http://go.microsoft.com/fwlink/?linkid=190509)
</td>
<td style="border:1px solid black;">
[**MS10-069**](http://go.microsoft.com/fwlink/?linkid=197093)
</td>
<td style="border:1px solid black;">
[**MS10-070**](http://go.microsoft.com/fwlink/?linkid=202409)
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
Windows Server 2003 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d79680b-c071-462f-9cea-551fbd42edf0)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0a942985-081f-455c-bf9d-4345392c91b0)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7ff7de2f-3e37-4aff-a8e4-5ed21b83575c)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=29e6cf4f-446b-461c-82f7-cfa8478cf739)  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8b3004b-07db-4638-a9b7-224ff829081c)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3290e7ee-1e4a-464c-abfd-17fc4108601e)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=3fe6e78c-c60a-4903-9273-27b37e129f0a)  
(KB981550)  
(Ważny)  
[Tryb aplikacji usługi Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=c42731f1-6393-42ed-b59f-5310c832fdc4)  
(KB982000)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fd46ba66-8ca1-4aa2-b91b-9e5861a173f7)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=71f0daad-e2df-421c-9818-58e1e40cdb65)  
(KB2416451)  
(Ważny)  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46)  
(KB2418241)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780)  
(KB2416468)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=073b3305-4a81-4ef8-b6aa-e53b31a936b4)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8382c1f2-e16d-475c-a8a0-e378696808f1)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=750e4a79-11bf-4726-9eb4-5dd3d029a717)  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=612b2096-bd82-47ca-8b99-454c2f158d39)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b21570cc-4f90-4ed8-b901-a34584d44a63)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=22412eed-33cd-4dfc-8ef7-b74dcd7c5faf)  
(KB981550)  
(Ważny)  
[Tryb aplikacji usługi Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=79fb639d-2cc1-4bea-9df6-c67ed95890e3)  
(KB982000)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ff5976e0-579c-4e6e-a225-c0d3913cdc85)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46)  
(KB2418241)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780)  
(KB2416468)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ca35a520-c4da-41bb-abcc-d5bc534ff19a)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=be7b3310-ffb7-4528-9c9e-aebe14d264d6)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f6841057-1745-44e9-a16a-c180dd941ddf)  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1f04f151-330a-4b6c-826e-76def35daa73)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c9c4427d-54c8-4f3c-9a94-818196cd5180)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=cab75c8a-0d12-4a91-82b2-9f9b70610f67)  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=e450ca08-1d75-4419-ad9f-c5e5efb55cd5)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46)  
(KB2418241)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780)  
(KB2416468)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="10">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-061**](http://go.microsoft.com/fwlink/?linkid=200505)
</td>
<td style="border:1px solid black;">
[**MS10-062**](http://go.microsoft.com/fwlink/?linkid=190884)
</td>
<td style="border:1px solid black;">
[**MS10-063**](http://go.microsoft.com/fwlink/?linkid=200378)
</td>
<td style="border:1px solid black;">
[**MS10-065**](http://go.microsoft.com/fwlink/?linkid=199537)
</td>
<td style="border:1px solid black;">
[**MS10-066**](http://go.microsoft.com/fwlink/?linkid=197105)
</td>
<td style="border:1px solid black;">
[**MS10-067**](http://go.microsoft.com/fwlink/?linkid=197102)
</td>
<td style="border:1px solid black;">
[**MS10-068**](http://go.microsoft.com/fwlink/?linkid=190509)
</td>
<td style="border:1px solid black;">
[**MS10-069**](http://go.microsoft.com/fwlink/?linkid=197093)
</td>
<td style="border:1px solid black;">
[**MS10-070**](http://go.microsoft.com/fwlink/?linkid=202409)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=028977fd-0f39-42d4-9fee-0d90a2931cfd)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=84629c25-7827-40c1-86fb-7ffa247202a0)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ac1b0260-3802-45d4-985e-ac827d784e4f)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Microsoft Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=75059175-9c59-45d5-81ce-09b964640e5f)  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Tylko Windows Vista z dodatkiem Service Pack 2:  
[Usługa Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=853a71f3-fb0d-43af-a2b8-45bf8ca1a588)  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)  
Tylko Windows Vista z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 1 oraz Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)  
(KB2416469)  
(Ważny)  
Tylko Windows Vista z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)  
(KB2416474)  
(Ważny)  
Tylko Windows Vista z dodatkiem Service Pack 2:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2, Microsoft .NET Framework 3.5 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)  
(KB2416470)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c68b9337-883d-4e98-ba0a-90b5cad46184)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=36e2a74b-e5c6-47d5-9cd9-b9171be63c7d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ebfdcd6d-413e-4359-8863-e992327a607f)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Microsoft Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=9864c590-10a7-4971-a717-924ed0d6cace)  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Tylko Windows Vista x64 Edition z dodatkiem Service Pack 2:  
[Usługa Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=566f468b-22b6-400a-a656-ae64cfcb52df)  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)  
Tylko Windows Vista x64 Edition z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 1 oraz Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)  
(KB2416469)  
(Ważny)  
Tylko Windows Vista x64 Edition z dodatkiem Service Pack 1:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)  
(KB2416474)  
(Ważny)  
Tylko Windows Vista x64 Edition z dodatkiem Service Pack 2:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2, Microsoft .NET Framework 3.5 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)  
(KB2416470)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="10">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-061**](http://go.microsoft.com/fwlink/?linkid=200505)
</td>
<td style="border:1px solid black;">
[**MS10-062**](http://go.microsoft.com/fwlink/?linkid=190884)
</td>
<td style="border:1px solid black;">
[**MS10-063**](http://go.microsoft.com/fwlink/?linkid=200378)
</td>
<td style="border:1px solid black;">
[**MS10-065**](http://go.microsoft.com/fwlink/?linkid=199537)
</td>
<td style="border:1px solid black;">
[**MS10-066**](http://go.microsoft.com/fwlink/?linkid=197105)
</td>
<td style="border:1px solid black;">
[**MS10-067**](http://go.microsoft.com/fwlink/?linkid=197102)
</td>
<td style="border:1px solid black;">
[**MS10-068**](http://go.microsoft.com/fwlink/?linkid=190509)
</td>
<td style="border:1px solid black;">
[**MS10-069**](http://go.microsoft.com/fwlink/?linkid=197093)
</td>
<td style="border:1px solid black;">
[**MS10-070**](http://go.microsoft.com/fwlink/?linkid=202409)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=e2e788de-8400-4bf6-b96b-a915154aa20a)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=fdfc393e-a54d-44dd-ba45-c2a550ffd2a1)\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=b679fe0c-5498-4fc5-84c8-0cd24b625907)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=d798dc8e-ae64-4a1d-abda-f58cf69779d8)\*  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Usługa Active Directory i usługa Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=1452befe-b7b8-4131-b36f-dded2bd16d5e)\*  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)\*\*  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)\*\*  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)\*\*  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)\*\*<sup>[1]</sup>
(KB2416472)  
(Ważny)  
Tylko Windows Server 2008 dla systemów 32-bitowych:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 1 oraz Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)\*\*  
(KB2416469)  
(Ważny)  
Tylko Windows Server 2008 dla systemów 32-bitowych:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)\*\*  
(KB2416474)  
(Ważny)  
Tylko Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2, Microsoft .NET Framework 3.5 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)\*\*  
(KB2416470)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=e08d4f49-5a13-4e1d-b0a7-27b314c2edb5)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=1b7af424-6286-4a80-827c-c4df4f92fe43)\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=e1b38b87-24f6-4aaa-afa9-40f4015d6694)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e29f01dc-b00d-4c12-a13e-63aa0b09d919)\*  
(KB2124261)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Usługa Active Directory i usługa Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=38eb875f-1869-401b-b7d3-9f18f4ba4f24)\*  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)\*\*  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)\*\*  
(KB2418240)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)\*\*  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)\*\*<sup>[1]</sup>
(KB2416472)  
(Ważny)  
Tylko Windows Server 2008 dla systemów opartych na procesorach x64:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 1 oraz Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)\*\*  
(KB2416469)  
(Ważny)  
Tylko Windows Server 2008 dla systemów opartych na procesorach x64:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)\*\*  
(KB2416474)  
(Ważny)  
Tylko Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2, Microsoft .NET Framework 3.5 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)\*\*  
(KB2416470)  
(Ważny)  
Tylko Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64:  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae)\*\*  
(KB2418240)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=098537d5-bf6e-4e04-ad33-1cde697e062f)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ceb856e8-f4a6-4229-bd26-b1a763d7d443)  
(KB981322)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Microsoft Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=d595c8d2-90b1-46e4-bb9f-60efd0bf3a02)  
(KB2124261)  
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
[Microsoft .NET Framework 1.1 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282)  
(KB2416447)  
(Ważny)  
[Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a)  
(KB2416473)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)  
Tylko Windows Server 2008 dla systemów z procesorem Itanium:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 1 oraz Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a)  
(KB2416469)  
(Ważny)  
Tylko Windows Server 2008 dla systemów z procesorem Itanium:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2 oraz Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93)  
(KB2416474)  
(Ważny)  
Tylko Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium:  
[Microsoft .NET Framework 2.0 z dodatkiem Service Pack 2, Microsoft .NET Framework 3.5 i Microsoft .NET Framework 3.5 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04)  
(KB2416470)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="10">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-061**](http://go.microsoft.com/fwlink/?linkid=200505)
</td>
<td style="border:1px solid black;">
[**MS10-062**](http://go.microsoft.com/fwlink/?linkid=190884)
</td>
<td style="border:1px solid black;">
[**MS10-063**](http://go.microsoft.com/fwlink/?linkid=200378)
</td>
<td style="border:1px solid black;">
[**MS10-065**](http://go.microsoft.com/fwlink/?linkid=199537)
</td>
<td style="border:1px solid black;">
[**MS10-066**](http://go.microsoft.com/fwlink/?linkid=197105)
</td>
<td style="border:1px solid black;">
[**MS10-067**](http://go.microsoft.com/fwlink/?linkid=197102)
</td>
<td style="border:1px solid black;">
[**MS10-068**](http://go.microsoft.com/fwlink/?linkid=190509)
</td>
<td style="border:1px solid black;">
[**MS10-069**](http://go.microsoft.com/fwlink/?linkid=197093)
</td>
<td style="border:1px solid black;">
[**MS10-070**](http://go.microsoft.com/fwlink/?linkid=202409)
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
Windows 7 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=34619e9e-1f00-40e4-be6f-5bbf5e3c801b)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=5b2d42da-4dbc-4fbb-be22-09ca7dec5aa3)  
(KB2124261)  
(Ważny)  
IIS FastCGI:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=c843afd9-b6f2-48de-91cc-1c0d481c2be4)  
(KB2271195)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Usługa Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=454fc025-bfa2-4552-9522-3585f523ecb2)  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7)  
(KB2416471)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=dbb747a5-658d-44cf-bd49-425d1700157f)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=66b64374-95e4-4b99-80e6-98dc63cd272b)  
(KB2124261)  
(Ważny)  
IIS FastCGI:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=5f0c0454-cbb6-47ed-9227-98aa45b8cbdb)  
(KB2271195)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Usługa Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=b15ad533-3cf1-4dcf-847c-05ebffb84e26)  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7)  
(KB2416471)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472) (Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472) (Ważny)
</td>
</tr>
<tr>
<th colspan="10">
System Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-061**](http://go.microsoft.com/fwlink/?linkid=200505)
</td>
<td style="border:1px solid black;">
[**MS10-062**](http://go.microsoft.com/fwlink/?linkid=190884)
</td>
<td style="border:1px solid black;">
[**MS10-063**](http://go.microsoft.com/fwlink/?linkid=200378)
</td>
<td style="border:1px solid black;">
[**MS10-065**](http://go.microsoft.com/fwlink/?linkid=199537)
</td>
<td style="border:1px solid black;">
[**MS10-066**](http://go.microsoft.com/fwlink/?linkid=197105)
</td>
<td style="border:1px solid black;">
[**MS10-067**](http://go.microsoft.com/fwlink/?linkid=197102)
</td>
<td style="border:1px solid black;">
[**MS10-068**](http://go.microsoft.com/fwlink/?linkid=190509)
</td>
<td style="border:1px solid black;">
[**MS10-069**](http://go.microsoft.com/fwlink/?linkid=197093)
</td>
<td style="border:1px solid black;">
[**MS10-070**](http://go.microsoft.com/fwlink/?linkid=202409)
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
Windows Server 2008 R2 dla systemów opartych na procesorach x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=11e20088-1be2-4166-9c97-234b7e9f1c4f)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=21458cce-f67e-4e95-a067-8311afefc261)\*  
(KB2124261)  
(Ważny)  
IIS FastCGI:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=9578b1de-f2c1-4b37-9d82-69e929cab6f3)\*  
(KB2271195)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Usługa Active Directory i usługa Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=54f36389-8be4-4a0c-9640-dc32addac9d7)\*  
(KB981550)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7)\*  
(KB2416471)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)\*<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d8c635f8-8978-44bf-b457-e07368f08ef4)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
IIS ASP:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=3b8f3fd1-1ef4-4e9f-9bce-0c68f10519d1)  
(KB2124261)  
(Ważny)  
IIS FastCGI:  
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=21adf80d-267f-47cd-9c03-4b4854ba159f)  
(KB2271195)  
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
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7)  
(KB2416471)  
(Ważny)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium
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
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6)<sup>[1]</sup>
(KB2416472)  
(Ważny)
</td>
</tr>
</table>
 
**Uwagi dotyczące systemu Windows Server 2008 i Windows Server 2008 R2**

**\*Luka w zabezpieczeniach dotyczy instalacji** **Server Core.** Ta aktualizacja ma zastosowanie, z takim samym wskaźnikiem ważności, w przypadku obsługiwanych wersji systemu Windows Server 2008 lub Windows Server 2008 R2, niezależnie od tego, czy zostały zainstalowane przy użyciu opcji instalacji Server Core. Więcej informacji na temat tej opcji instalacji można znaleźć w artykułach TechNet, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) i [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (jęz. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core.** Luki usuwane przez tę aktualizację zabezpieczeń nie dotyczą obsługiwanych wersji systemu Windows Server 2008 zainstalowanych przy użyciu opcji instalacji Server Core. Więcej informacji na temat tej opcji instalacji można znaleźć w artykułach TechNet, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx) i [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) (jęz. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Uwaga dotycząca biuletynu MS10-063**

Zobacz także pozostałe kategorie oprogramowania w sekcji Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

**Uwaga dotycząca biuletynu MS10-070**

<sup>[1]</sup>**Problem nie dotyczy aplikacji .NET Framework 4.0 Client Profile.** Pakiety redystrybucyjne systemu .NET Framework w wersji 4 są dostępne w dwóch profilach: .NET Framework 4.0 i .NET Framework 4.0 Client Profile. .NET Framework 4.0 Client Profile to podzbiór oprogramowania .NET Framework 4.0. Luka w zabezpieczeniach usuwana przez tę aktualizację dotyczy wyłącznie programu wersji .NET Framework 4.0. Nie wpływa w żaden sposób na aplikację .NET Framework 4.0 Client Profile. Aby uzyskać więcej informacji, zobacz artykuł: [Instalowanie systemu .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx) (j. ang.)

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
[**MS10-063**](http://go.microsoft.com/fwlink/?linkid=200378)
</td>
<td style="border:1px solid black;">
[**MS10-064**](http://go.microsoft.com/fwlink/?linkid=200727)
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
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0b56f85f-d39b-410a-857a-799a5d714de7)  
(KB2288608)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2002 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d5e85841-9dea-4776-9e0e-3cd272066f37)  
(KB2293422)  
(Krytyczny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=bb7783b1-b396-4254-b317-f2292b305cfc)  
(KB2288613)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ec8ed81e-05d0-4c20-b5fb-ebc72230a8bd)  
(KB2293428)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=44c5bccf-66dd-4796-9089-e6171d8c9785)  
(KB2288621)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2007 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6009d507-135c-4ce8-a830-925134f214dc)  
(KB2288953)  
(Ważny)
</td>
</tr>
</table>
 
**Uwaga dotycząca biuletynu MS10-063**

Zobacz także pozostałe kategorie oprogramowania w sekcji Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki, aby uzyskać więcej plików aktualizacji w ramach tego samego identyfikatora biuletynu. Ten biuletyn obejmuje więcej niż jedną kategorię oprogramowania.

Narzędzia wykrywania i wdrażania oraz wskazówki
-----------------------------------------------

<span></span>
**Centrum zabezpieczeń**

Zarządzanie oprogramowaniem oraz aktualizacjami zabezpieczeń, które należy zainstalować na serwerach oraz komputerach stacjonarnych i przenośnych w organizacji. Więcej informacji można znaleźć w [Centrum TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Witryna [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) zawiera dodatkowe informacje na temat zabezpieczeń w produktach firmy Microsoft. Użytkownicy mogą także uzyskać dostęp do tych informacji w witrynie [Bezpieczeństwo w domu](http://go.microsoft.com/fwlink/?linkid=85102), klikając łącze „Najnowsze aktualizacje zabezpieczeń”.

Aktualizacje zabezpieczeń dostępne są w witrynach [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) i [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizacje zabezpieczeń są także dostępne w witrynie [Centrum pobierania Microsoft](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.

Aktualizacje zabezpieczeń można także pobierać z [Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=96155). Wykaz usługi Microsoft Update zawiera katalog zawartości z możliwością przeszukiwania, który udostępniany jest poprzez usługi Windows Update i Microsoft Update i obejmuje aktualizacje zabezpieczeń, sterowniki i dodatki Service Pack. Wyszukiwanie przy użyciu numeru biuletynu zabezpieczeń (np. „MS07-036”) pozwala dodać do koszyka wszystkie odpowiednie aktualizacje (w tym różne wersje językowe aktualizacji) i pobrać pliki do wybranego folderu. Więcej informacji na temat Wykazu usługi Microsoft Update można znaleźć w [Często zadawanych pytaniach dotyczących Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=97900).

**Porady dotyczące wykrywania i wdrażania**

Firma Microsoft udziela porad dotyczących wykrywania i wdrażania aktualizacji zabezpieczeń. Porady takie zawierają zalecenia i informacje ułatwiające specjalistom IT poznanie obsługi różnych narzędzi do wykrywania i wdrażania aktualizacji zabezpieczeń. Więcej informacji na ten temat można znaleźć w [artykule 961747 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/961747).

**Narzędzie Microsoft Baseline Security Analyzer (MBSA)**

Narzędzie Microsoft Baseline Security Analyzer umożliwia administratorom skanowanie lokalnych i zdalnych systemów w poszukiwaniu brakujących aktualizacji zabezpieczeń oraz typowych błędów konfiguracji zabezpieczeń. Więcej informacji na temat narzędzia MBSA można znaleźć w witrynie sieci Web [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

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

Dowiedz się, jak poprawić bezpieczeństwo i zoptymalizować infrastrukturę informatyczną oraz weź udział w dyskusjach dotyczących zabezpieczeń wraz z innymi specjalistami z branży IT, odwiedzając witrynę sieci Web społeczności [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (jęz. ang.).

#### Podziękowania

Firma Microsoft [dziękuje](http://go.microsoft.com/fwlink/?linkid=21127) wymienionym poniżej organizacjom i osobom za współpracę w dziedzinie ochrony klientów:

-   Sergey Golovanov, Alexander Gostev, Maxim Golovkin i Alexey Monastyrsky z firmy [Kaspersky Lab](http://www.kaspersky.com/), a także Vitaly Kiktenko i Alexander Saprykin z firmy [Design and Test Lab](http://www.dnt-lab.com/), za zgłoszenie problemu opisanego w biuletynie MS10-061
-   Liam O Morchu z firmy [Symantec](http://www.symantec.com/index.jsp), za zgłoszenie problemu opisanego w biuletynie MS10-061
-   Matthew Watchinski z firmy [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html), za zgłoszenie problemu opisanego w biuletynie MS10-062
-   Carsten Book z firmy za zgłoszenie problemu opisanego w biuletynie MS10-063
-   Marc Schoenefeld z zespołu Red Hat Security Response Team za zgłoszenie problemu opisanego w biuletynie MS10-063
-   Carsten H. Eiram z firmy [Secunia](http://secunia.com/) za zgłoszenie informacji, na podstawie których zmieniono wskaźnik możliwości wykorzystania luki CVE-2010-2738 opisanej w biuletynie MS10-063.
-   Dyon Balding z firmy [Secunia](http://secunia.com/), za zgłoszenie problemu opisanego w biuletynie MS10-064
-   Jinsik Shim, za zgłoszenie problemu opisanego w biuletynie MS10-065
-   Travis Raybold z firmy Rubicon West, za zgłoszenie problemu opisanego w biuletynie MS10-065
-   Yamata Li z firmy [Palo Alto Networks](http://www.paloaltonetworks.com/), za zgłoszenie problemu opisanego w biuletynie MS10-066
-   S0lute z firmy [iDefense Labs](http://labs.idefense.com/), za zgłoszenie problemu opisanego w biuletynie MS10-067
-   [IBM Japan](http://www.ibm.com/jp/ja/), za zgłoszenie problemu opisanego w biuletynie MS10-069

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pod numerem 0 801 802 000 (opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne. Dodatkowe informacje dotyczące możliwości skorzystania z pomocy technicznej można znaleźć w witrynie [Pomoc i obsługa techniczna firmy Microsoft](http://support.microsoft.com/).
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (14 września 2010 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.
-   Wersja 2.0 (22 września 2010 r.): Podniesiono wskaźnik możliwości wykorzystania luki CVE-2010-2738, obniżono wskaźnik możliwości wykorzystania luki CVE-2010-2730 i zaktualizowano ważną uwagę dotyczącą wskaźnika możliwości wykorzystania luki CVE-2010-0818.
-   V3.0 (28 września 2010 r.): Dodano Biuletyn zabezpieczeń firmy Microsoft MS10-070, Luka w zabezpieczeniach usługi ASP.NET umożliwia ujawnienie informacji (2418042). Dodano także łącze do emisji internetowej, odnoszące się do tego opublikowanego poza cyklem standardowym biuletynu zabezpieczeń.
-   Wersja 4.0 (30 września 2010 r.): Niniejsze podsumowanie biuletynów zaktualizowano w celu poinformowania, że aktualizacje omówione w biuletynie zabezpieczeń MS10-070 są teraz dostępne za pośrednictwem wszystkich kanałów dystrybucji, w tym Windows Update i Microsoft Update. Zaktualizowano również informacje o aktualizacjach KB2418240, KB2418241, KB2416470 i KB2416474 omówionych w biuletynie zabezpieczeń MS10-070.
-   Wersja 4.1 (3 listopada 2010 r.): W biuletynie zabezpieczeń dodano uwagę do tabeli „Programy, których dotyczy problem” z wyjaśnieniem, że problem nie wpływa na aplikację .NET Framework 4.0 Client Profile.
-   Wersja 5.0 (14 grudnia 2010 r.): Niniejsze podsumowanie biuletynów zaktualizowano w celu poinformowania, że dla biuletynu MS10-070 dostępne są nowe pakiety aktualizacji zabezpieczeń oprogramowania .NET Framework 4.0 (KB2416472), które rozwiązują problem z konfiguracją mogący zakłócać proces instalowania innych aktualizacji i/lub produktów. Klienci, którym udało się zaktualizować swoje systemy, nie muszą podejmować żadnej czynności.
-   Wer. 6.0 (22 lutego 2011 r.): W przypadku biuletynu MS10-070 zmieniono sposób wykrywania w celu zaoferowania pakietów aktualizacji oprogramowania Microsoft .NET Framework 4.0 (KB2416472) klientom instalującym oprogramowanie Microsoft .NET Framework 4.0 po zainstalowaniu systemu Windows 7 z dodatkiem Service Pack 1 dla systemów 32-bitowych, Windows 7 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64, Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach x64 lub Windows Server 2008 R2 z dodatkiem Service Pack 1 dla systemów opartych na procesorach Itanium. Klienci, którym udało się zaktualizować swoje systemy, nie muszą podejmować dalszych czynności.
-   Wersja 6.1 (26 października 2011 r.): W biuletynie MS10-070 poprawiono zastosowanie instalacji Server Core dla oprogramowania .NET Framework 4 w systemie Windows Server 2008 R2 dla systemów opartych na procesorze x64.

*Built at 2014-04-18T01:50:00Z-07:00*
