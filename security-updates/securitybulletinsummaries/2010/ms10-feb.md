---
TOCTitle: 'MS10-FEB'
Title: 'Podsumowanie biuletynów zabezpieczeń firmy Microsoft za luty 2010 r.'
ms:assetid: 'ms10-feb'
ms:contentKeyID: 61233111
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms10-feb(v=Security.10)'
---
Podsumowanie biuletynów zabezpieczeń firmy Microsoft za luty 2010 r.
====================================================================

Opublikowano: 9 lutego 2010 | Zaktualizowano: 10 lutego 2010

**Wersja:** 1.1

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za luty 2010 r.

Z chwilą opublikowania biuletynów za luty 2010 r. niniejsze podsumowanie biuletynów zastępuje powiadomienie o biuletynach zabezpieczeń wydane 4 lutego 2010 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j. ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

10 lutego 2010 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępni emisję internetową, w której znajdą się odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). Zarejestruj się, aby zobaczyć [emisję internetową dotyczącą biuletynów zabezpieczeń za luty](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427679&culture=en-us). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178850">MS10-006</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach klienta SMB umożliwiają zdalne wykonanie kodu (978251)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach systemu Windows, które zostały zgłoszone przez użytkowników. Luki w zabezpieczeniach umożliwiają zdalne wykonanie kodu, jeśli osoba atakująca wyśle specjalnie spreparowaną odpowiedź SMB na żądanie SMB zainicjowane przez klienta. Aby wykorzystać te luki, osoba atakująca musi przekonać użytkownika do zainicjowania połączenia SMB z niebezpiecznym serwerem SMB.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179067">MS10-007</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach procedury obsługi powłoki systemu Windows umożliwia zdalne wykonanie kodu (975713)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w systemach Microsoft Windows 2000, Windows XP i Windows Server 2003, która została zgłoszona przez użytkowników. Nie dotyczy ona innych wersji systemu Windows. Luka ta może pozwolić na zdalne wykonanie kodu, jeśli aplikacja, taka jak przeglądarka sieci Web, przekaże specjalnie spreparowane dane do funkcji API ShellExecute za pośrednictwem procedury obsługi powłoki systemu Windows.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179106">MS10-008</a></td>
<td style="border:1px solid black;"><strong>Zbiorcza aktualizacja zabezpieczeń bitów „zabicia” dla formantów ActiveX (978262)</strong><br />
<br />
Ta aktualizacja usuwa lukę w zabezpieczeniach programów firmy Microsoft zgłoszoną przez użytkowników. Niniejsza aktualizacja zabezpieczeń ma wskaźnik ważności „krytyczny” dla wszystkich obsługiwanych wersji systemów Microsoft Windows 2000 i Windows XP, wskaźnik „ważny” dla wszystkich obsługiwanych wersji systemów Windows Vista i Windows 7, wskaźnik „umiarkowany” dla wszystkich obsługiwanych wersji systemu Windows Server 2003 oraz wskaźnik „niski” dla wszystkich obsługiwanych wersji systemów Windows Server 2008 i Windows Server 2008 R2.<br />
<br />
Luka ta może pozwolić na zdalne wykonanie kodu, jeśli użytkownik wyświetli za pomocą programu Internet Explorer specjalnie spreparowaną stronę sieci Web, która uruchamia formant ActiveX. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi. Niniejsza aktualizacja obejmuje także bity „zabicia” dla czterech formantów ActiveX innych producentów.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167190">MS10-009</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach protokołu TCP/IP systemu Windows umożliwiają zdalne wykonanie kodu (974145)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa cztery luki w zabezpieczeniach systemu Microsoft Windows, które zostały zgłoszone przez użytkowników. Najpoważniejsza z tych luk umożliwia zdalne wykonanie kodu, jeśli specjalnie spreparowane pakiety zostanę przesłane do komputera z włączoną obsługą protokołu IPv6. Osoba atakująca może próbować wykorzystać tę lukę, tworząc specjalnie spreparowane pakiety ICMPv6 i wysyłając je do systemu z włączoną obsługą protokołu IPv6. Wykorzystanie tej luki w zabezpieczeniach jest możliwe tylko w przypadku, gdy osoba atakująca jest uczestnikiem łącza.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167321">MS10-013</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft DirectShow może pozwolić na zdalne wykonanie kodu (977935)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w programie Microsoft DirectShow, która została zgłoszona przez użytkowników. Luka ta może umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik AVI. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać pełną kontrolę nad systemem, którego dotyczy luka. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178812">MS10-003</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach pakietu Microsoft Office (MSO) umożliwia zdalne wykonanie kodu (978214)</strong><br />
<br />
Ta aktualizacja zabezpieczeń pozwala usunąć lukę w zabezpieczeniach pakietu Microsoft Office zgłoszoną przez osobę prywatną, która może pozwolić na zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik pakietu Office. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać pełną kontrolę nad systemem, którego dotyczy luka. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach programu Microsoft Office PowerPoint umożliwiają zdalne wykonanie kodu (975416)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa sześć luk w zabezpieczeniach programu Microsoft Office PowerPoint, które zostały zgłoszone przez użytkowników. Luki te mogą umożliwić zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik programu PowerPoint. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179066">MS10-010</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach funkcji Hyper-V w systemie Windows Server 2008 umożliwia przeprowadzenie ataku typu „odmowa usługi” (977894)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach funkcji Hyper-V systemów Windows Server 2008 i Windows Server 2008 R2, która została zgłoszona przez użytkowników. Luka umożliwia przeprowadzenie ataku typu „odmowa usługi”, jeśli nieprawidłowa sekwencja instrukcji maszyny zostanie uruchomiona przez użytkownika uwierzytelnionego na jednej z maszyn wirtualnych gościa obsługiwanych przez serwer funkcji Hyper-V. Aby wykorzystać tę lukę, osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania i być w stanie zalogować się lokalnie do maszyny wirtualnej gościa. Nie jest możliwe wykorzystanie luki w sposób zdalny lub przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Odmowa usługi</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179798">MS10-011</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach Podsystemu wykonawczego serwera klienta w systemie Windows może pozwolić na podniesienie poziomu uprawnień (978037)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach Podsystemu wykonawczego serwera/klienta systemu Windows, która została zgłoszona przez użytkowników. Luka istnieje w systemach Microsoft Windows 2000, Windows XP oraz Windows Server 2003 i nie dotyczy innych wersji systemu Windows. Luka ta może umożliwić podniesienie uprawnień, jeśli osoba atakująca zaloguje się do systemu i uruchomi specjalnie spreparowaną aplikację, która działa także po wylogowaniu się osoby atakującej. Osoba atakująca musi dysponować prawidłowymi poświadczeniami logowania oraz być w stanie zalogować się lokalnie, aby wykorzystać możliwości stwarzane przez lukę. Nie jest możliwe wykorzystanie jej przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155976">MS10-012</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach serwera SMB umożliwiają zdalne wykonanie kodu (971468)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa kilka luk w zabezpieczeniach systemu Microsoft Windows, które zostały zgłoszone przez użytkowników. Najpoważniejsze z tych luk umożliwiają zdalne wykonanie kodu, jeśli osoba atakująca utworzy specjalnie spreparowany pakiet SMB i wyśle go do systemu, którego dotyczy problem. Stosowanie najlepszych rozwiązań dotyczących zapór oraz standardowych konfiguracji domyślnej zapory może uchronić sieci przed atakami mającymi wykorzystać omawiane luki, których źródło znajduje się poza granicami przedsiębiorstwa.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=181196">MS10-014</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach protokołu Kerberos umożliwia przeprowadzenie ataku typu „odmowa usługi” (977290)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach systemu Microsoft Windows. Luka w zabezpieczeniach umożliwia przeprowadzenie ataku typu „odmowa usługi”, gdy spreparowane żądanie odnowienia biletu zostanie wysłane do domeny Kerberos systemu Windows przez użytkownika uwierzytelnionego w zaufanym obszarze innym niż Kerberos systemu Windows. Atak typu „odmowa usługi” można będzie przeprowadzać aż do momentu ponownego uruchomienia kontrolera domeny.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Odmowa usługi</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179062">MS10-015</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach jądra systemu Windows umożliwiają podniesienie poziomu uprawnień (977165)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa jedną lukę zgłoszoną przez organizacje publiczne oraz jedną lukę zgłoszone przez użytkowników. Istnieją one w jądrze systemu Windows. Luki te mogą umożliwić podniesienie uprawnień, jeśli osoba atakująca zaloguje się do systemu i uruchomi specjalnie spreparowaną aplikację. Aby wykorzystać którąś z tych luk, osoba atakująca musi posiadać prawidłowe poświadczenia logowania i mieć możliwość zalogowania się lokalnie. Nie jest możliwe wykorzystanie luk w sposób zdalny ani przez użytkowników anonimowych.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=180620">MS10-005</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft Paint może pozwolić na zdalne wykonanie kodu (978706)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa lukę w programie Microsoft Paint, która została zgłoszona przez użytkowników. Omawiana luka może pozwolić na zdalne wykonanie kodu, jeśli użytkownik wyświetli specjalnie spreparowany plik obrazu JPEG przy użyciu programu Microsoft Paint. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Umiarkowany</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Wskaźnik możliwości wykorzystania luki  
--------------------------------------
  
<span></span>
Poniższa tabela przedstawia ocenę możliwości wykorzystania luk dla każdej luki opisywanej w tym miesiącu. Luki są wymienione według malejącego poziomu oceny możliwości wykorzystania, a nie według identyfikatora CVE.
  
**W jaki sposób korzystać z tej tabeli?**
  
Tabela ta pozwala sprawdzić prawdopodobieństwo, że w ciągu 30 dni od wydania biuletynu zabezpieczeń dla każdej z aktualizacji zabezpieczeń, których zainstalowanie może być potrzebne, opublikowany zostanie działający kod wykorzystujący lukę w zabezpieczeniach. Aby ustalić priorytety wdrażania, zapoznaj się z dostępnymi poniżej ocenami, rozpatrując je w kontekście posiadanej konfiguracji. Więcej informacji na temat znaczenia tych ocen oraz sposobu ich wyznaczania można znaleźć na stronie sieci Web [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Identyfikator biuletynu                                   | Nazwa luki w zabezpieczeniach                                                                                               | CVE ID                                                                           | Ocena wskaźnika możliwości wykorzystania luki                                                                              | Najważniejsze uwagi                                                                                                                              |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-006](http://go.microsoft.com/fwlink/?linkid=178850) | Luka w zabezpieczeniach klienta SMB związana z sytuacją wyścigu                                                             | [CVE-2010-0017](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0017) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | Zdalny kierunek ataku może umożliwić atak typu „odmowa usługi”; lokalny kierunek ataku może umożliwić atak w celu podniesienia poziomu uprawnień |  
| [MS10-011](http://go.microsoft.com/fwlink/?linkid=179798) | Luka w zabezpieczeniach CSRSS umożliwiająca lokalne podniesienie uprawnień                                                  | [CVE-2010-0023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0023) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | Osoba atakująca i ofiara muszą być zalogowane do tej samej konsoli                                                                               |  
| [MS10-007](http://go.microsoft.com/fwlink/?linkid=179067) | Luka związana ze sprawdzaniem poprawności adresu URL                                                                        | [CVE-2010-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639) | Luka w zabezpieczeniach programu PowerPoint związana z przepełnieniem stosu - LinkedSlideAtom                               | [CVE-2010-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0030) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639) | Luka w zabezpieczeniach programu PowerPoint związana z indeksowaniem nieprawidłowej tablicy OEPlaceholderAtom 'placementId' | [CVE-2010-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0031) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639) | Luka w zabezpieczeniach programu PowerPoint związana z użyciem OEPlaceholderAtom po zwolnieniu                              | [CVE-2010-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0032) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639) | Luka w zabezpieczeniach programu PowerPoint Viewer związana z przepełnieniem stosu rekordu TextBytesAtom                    | [CVE-2010-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0033) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | Luka w zabezpieczeniach dotyczy tylko programu PowerPoint Viewer 2003                                                                            |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639) | Luka w zabezpieczeniach programu Office PowerPoint Viewer związana z przepełnieniem stosu rekordu TextCharsAtom             | [CVE-2010-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0034) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | Luka w zabezpieczeniach dotyczy tylko programu PowerPoint Viewer 2003                                                                            |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976) | Luka w zabezpieczeniach protokołu SMB związana z brakiem entropii uwierzytelniania NTLM                                     | [CVE-2010-0231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0231) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-015](http://go.microsoft.com/fwlink/?linkid=179062) | Luka w zabezpieczeniach jądra systemu Windows związana z procedurą obsługi wyjątków                                         | [CVE-2010-0232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0232) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-003](http://go.microsoft.com/fwlink/?linkid=178812) | Luka w zabezpieczeniach związana z przepełnieniem buforu biblioteki MSO.DLL                                                 | [CVE-2010-0243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0243) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-013](http://go.microsoft.com/fwlink/?linkid=167321) | Luka w zabezpieczeniach programu DirectShow związana z przepełnieniem stosu                                                 | [CVE-2010-0250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0250) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                                                                           |  
| [MS10-006](http://go.microsoft.com/fwlink/?linkid=178850) | Luka w zabezpieczeniach klienta SMB związana z uszkodzeniem puli                                                            | [CVE-2010-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0016) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                                           |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976) | Luka w zabezpieczeniach protokołu SMB związana z przepełnieniem i nazwą ścieżki                                             | [CVE-2010-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0020) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                                           |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976) | Luka w zabezpieczeniach protokołu SMB związana z uszkodzeniem pamięci                                                       | [CVE-2010-0021](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0021) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                                           |  
| [MS10-005](http://go.microsoft.com/fwlink/?linkid=180620) | Luka w zabezpieczeniach programu MS Paint związana z przepełnieniem liczby całkowitej                                       | [CVE-2010-0028](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0028) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | Pomyślne wykorzystanie luki wymaga znacznej interakcji ze strony użytkownika                                                                     |  
| [MS10-004](http://go.microsoft.com/fwlink/?linkid=163639) | Luka w zabezpieczeniach programu PowerPoint związana z przepełnieniem buforu obsługi ścieżek plików                         | [CVE-2010-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0029) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                                           |  
| [MS10-015](http://go.microsoft.com/fwlink/?linkid=179062) | Luka w zabezpieczeniach jądra systemu Windows związana z podwójnym zwolnieniem                                              | [CVE-2010-0233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0233) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | (Brak)                                                                                                                                           |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190) | Luka w zabezpieczeniach związana z anonsem routera ICMPv6                                                                   | [CVE-2010-0239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0239) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | Aby możliwe było wykorzystanie luki, osoba atakująca musi być uczestnikiem łącza z hostem docelowym                                              |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190) | Luka w zabezpieczeniach związana z fragmentacją MDL nagłówka                                                                | [CVE-2010-0240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0240) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | Luka w zabezpieczeniach wymaga sterownika sieciowego innej firmy                                                                                 |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190) | Luka w zabezpieczeniach dotycząca informacji o routingu ICMPv6                                                              | [CVE-2010-0241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0241) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | Aby możliwe było wykorzystanie luki, osoba atakująca musi być uczestnikiem łącza z hostem docelowym                                              |  
| [MS10-012](http://go.microsoft.com/fwlink/?linkid=155976) | Luka w zabezpieczeniach protokołu SMB związana z pustym wskaźnikiem                                                         | [CVE-2010-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0022) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - działający kod wykorzystujący lukę mało prawdopodobny | (Brak)                                                                                                                                           |  
| [MS10-010](http://go.microsoft.com/fwlink/?linkid=179066) | Luka w zabezpieczeniach funkcji Hyper-V związana ze sprawdzaniem poprawności zestawu instrukcji                             | [CVE-2010-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0026) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - działający kod wykorzystujący lukę mało prawdopodobny | Luka umożliwia przeprowadzenie wyłącznie ataku typu „odmowa usługi”                                                                              |  
| [MS10-014](http://go.microsoft.com/fwlink/?linkid=181196) | Luka w zabezpieczeniach protokołu Kerberos związana z odwołaniem odniesienia do wskaźnika pustego                           | [CVE-2010-0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0035) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - działający kod wykorzystujący lukę mało prawdopodobny | Tylko atak typu „odmowa usługi”; wykorzystanie luki jest możliwe tylko w przypadku kontrolerów domeny z konfiguracją inną niż domyślna           |  
| [MS10-009](http://go.microsoft.com/fwlink/?linkid=167190) | Luka w zabezpieczeniach związana z selektywnym potwierdzaniem protokołu TCP/IP                                              | [CVE-2010-0242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0242) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - działający kod wykorzystujący lukę mało prawdopodobny | (Brak)                                                                                                                                           |
  
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
</tr>
<tr>
<th colspan="12">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 z dodatkiem Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=80b49bab-6c2f-48a8-a901-ca3f76e4fe6b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=92234237-a8eb-4ce4-bc5e-cd86feb7dbd3)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=543dc6a7-fa76-4ba9-81e4-25fdf2013548)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Filtr AVI](http://www.microsoft.com/downloads/details.aspx?familyid=ba110440-10ce-40a0-884a-8b9afd45a3e3)  
(KB977914)  
(Krytyczny)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=16787c93-2c95-4c13-8492-be1db9d18146)  
(KB975560)  
(Krytyczny)  
[Quartz w programie DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=59a8bc19-02bb-4800-bac1-464f59e1cb7b)<sup>[1]</sup>
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=456185b5-57d1-4fa5-a4a9-5b2006ede3ad)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=267ce982-54a0-418f-ad52-e4963610f714)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=56a9afba-a6ee-4fb9-ba85-e51d9f94de27)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=ed8ac6a5-c8bb-4ed4-8994-810e9a1863c3)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=e5861705-8f49-45cb-8a92-cf052ccf4134)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="12">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
Brak
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
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f6c4472e-385c-4412-bda9-c2e615e50713)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b8e7bf17-a037-4200-9ae2-2280b19766a4)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7bcf3945-0552-478e-b7f3-bbca97dd1b5d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Filtr AVI](http://www.microsoft.com/downloads/details.aspx?familyid=a9beb2bd-e5f6-43f9-bbcc-a2afee5e5ceb)  
(KB977914)  
(Krytyczny)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7ab53be3-3f42-4e61-a2bc-3ed41d8736ff)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b9234b40-1b1c-498b-90d4-0bff347b36ee)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8f7adee3-e68e-41b3-b835-d84691774f31)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e2b348f5-ec8d-4782-bb03-5de550adea77)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b2e70df6-7728-4fc3-8df7-8ddb9ba5202f)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=63e15ff0-73b3-46c9-96f8-c18977d35a10)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8d83f30-9cd7-4d6b-b2b9-65d0a483cb9c)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=25ef97e8-e76e-44c2-953c-f94cbac552cf)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Filtr AVI](http://www.microsoft.com/downloads/details.aspx?familyid=dedc3010-a989-45f7-b9d4-f7079db3e572)  
(KB977914)  
(Krytyczny)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7543e819-cd36-4e89-9850-60f00c50999d)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f83bf7a-e16c-404a-89bd-f65843938299)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=91ee57f2-81e5-49bd-bdfc-d3e385efc8a5)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e534d00c-6ddc-4eb3-9464-5db6e90afa3e)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8c4acc8-c2f4-41f7-9b32-e7bd791e0155)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=feb8c145-7c30-45fa-a6f0-8b6453ddd521)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5cb2e203-18fb-4887-a1c9-289d86b8ba11)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=29ff72f7-1663-4f35-a794-2dfe3c17b39c)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Filtr AVI](http://www.microsoft.com/downloads/details.aspx?familyid=cc5150d7-070e-4a87-9c02-d050a8cb2204)  
(KB977914)  
(Krytyczny)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=983c5484-6321-4765-97ec-8d42d42d1f70)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c8c4eec-255e-41d5-b1e6-f0204edcb46f)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d18cbc4-ac48-458c-8aa3-90708fd854ff)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=738e2fda-96fc-413d-a5c7-74b1fac1d6b3)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=defd8603-ed9b-42f9-a539-2b6a690e9575)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c1efbe73-fc87-4e6a-8b36-81f125a27aec)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=36d88c1b-814c-4371-9ed2-d4576f419fc3)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=90360537-9311-45e2-8047-9a971f90c3c3)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d4a97bb7-4f74-4884-9a6e-7a4df9c540fb)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Filtr AVI](http://www.microsoft.com/downloads/details.aspx?familyid=db13e99b-2f2a-4474-8d6e-271b025bd07f)  
(KB977914)  
(Krytyczny)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7dc20252-6091-407b-befc-c25e8f5d3fb0)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=de0186f6-27a2-4226-b8eb-f2912710f072)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d63c95e-311a-446f-8852-dffd217a89f6)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f8ad539d-8191-4864-977b-ad4e31c04ba0)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9873c962-9d3d-46ef-b54b-2a50696fb6b2)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9143e435-f0d6-464b-9273-4d1f38f8ff3a)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=622442b0-cffe-4fc2-94a8-edff9d71ecd3)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d695ca9f-a1db-4c0f-94b6-7112861c28da)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=b84f0be4-6d11-4b07-bb3c-2c76ae9ceea8)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Filtr AVI](http://www.microsoft.com/downloads/details.aspx?familyid=aec66173-e2c6-4c39-8d60-8fbef6d7b764)  
(KB977914)  
(Ważny)  
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=b1a7533a-913f-4054-b579-489a257bae5f)  
(KB975560)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=87732f7a-9339-43bc-a4e8-3da849f35b70)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ee7f8cc4-f7fd-4dc7-808c-436204ee80cb)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d549c927-add7-4d83-bfc7-15dc35663dfb)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=c3c21225-8534-4c7f-96b6-20a743dcea74)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=ee603435-26af-4ab9-9f22-92734346dc0a)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="12">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1902fc93-0f4b-4261-9da3-17d1931daf2e)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2c897ddd-f441-41d4-b5b4-d794cfc96e6b)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=71f03946-622c-4403-b94f-f6a3de18a8c3)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=7130ce0f-df38-4c96-ac54-cdbff35f03e7)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=16494dac-553a-4de9-b751-0d6b51cb43f0)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2761c7b4-d472-4f00-949b-af3ebafdc08d)  
(Ważny)
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
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7c2f89b5-a3b3-42cd-857d-923fe8b8f1da)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f349f7aa-d020-4e0d-a35f-518a63ec92df)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=519815fd-707d-476f-9e29-7b03b7a17af5)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=de7b7c8f-bd0a-4e13-bd58-d95507a6274b)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cec582b3-e37f-448e-a5c3-6abdcee9e57c)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=38b40dab-6b4d-434b-9997-12ef70d6bbcc)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<th colspan="12">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Niski**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=09e19263-18ba-495e-bcf7-719e957204a7)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=9a85b1bf-7427-47d0-9e1b-21dbe824a62c)\*\*  
(Niski)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=bc451228-3de4-427c-b42f-91f204c708b8)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=5ac0a948-0bdc-4c10-9b88-16a5d7092e47)\*\*  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=597b2310-2cd8-4d0f-8248-781eb8b7450a)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=75327470-0f14-4cdd-bcb7-64684c61c267)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=21e87558-9bd2-4aa9-aaa5-7fd26a5b60e6)  
(Ważny)
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
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=180c2313-5e3e-4d84-87cd-64048f51e0f6)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=fde218c3-90ab-4664-852d-25ca55835054)\*\*  
(Niski)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=3a889152-5d7c-4a3e-b4f1-c6507b739ca0)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=362fea40-649b-4471-aad7-db29edd0ac10)\*\*  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=3463a63c-e88a-4036-ab60-f84d4bf4191a)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=67119fb6-e517-46f4-ab0b-2351cdc3d670)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=7d0f8f81-fc10-450a-a653-06f89acba9fa)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=0b93047d-f2c6-403b-9200-c251898bc1e0)  
(Ważny)
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
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=614eaf7e-95aa-4f8f-910c-1980e1f14d11)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=5b6e9451-df38-4626-bb1d-4fc160d7a40e)  
(Niski)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=1cd1882b-8e55-47ea-a82a-68bb59a500a7)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=effa638b-cfc1-4777-8219-7b433ed5e717)  
(KB975560)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=f90fc0c8-babe-4224-be07-614ea7ddf102)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=cd6b234b-8e96-4128-a77a-645a0882996a)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
</tr>
<tr>
<th colspan="12">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 dla systemów 32-bitowych
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=a589431a-93dc-42cd-a74e-d9c1e3452fef)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=ec6d996f-dffa-45ad-9467-e96a4ac63e5f)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=4ec49aa2-81df-4e65-80da-6201394c4089)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=122fc003-0651-4ad2-a5c8-a21536defad8)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów 32-bitowych](http://www.microsoft.com/downloads/details.aspx?familyid=66f14bb4-40fc-4ae3-9baf-429b7106cd91)  
(Ważny)
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
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=3c1edcf8-d304-45c4-9818-1cd86383b3fe)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=b3265576-04c1-48b1-8ce9-128843c58cf5)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=a8a2519c-3b89-4987-9473-920adafc78cb)  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows 7 dla systemów z procesorem x64](http://www.microsoft.com/downloads/details.aspx?familyid=3e096468-db6c-45c6-bee5-eaeaa63500b5)  
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
<th colspan="12">
System Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-006**](http://go.microsoft.com/fwlink/?linkid=178850)
</td>
<td style="border:1px solid black;">
[**MS10-007**](http://go.microsoft.com/fwlink/?linkid=179067)
</td>
<td style="border:1px solid black;">
[**MS10-008**](http://go.microsoft.com/fwlink/?linkid=179106)
</td>
<td style="border:1px solid black;">
[**MS10-009**](http://go.microsoft.com/fwlink/?linkid=167190)
</td>
<td style="border:1px solid black;">
[**MS10-013**](http://go.microsoft.com/fwlink/?linkid=167321)
</td>
<td style="border:1px solid black;">
[**MS10-010**](http://go.microsoft.com/fwlink/?linkid=179066)
</td>
<td style="border:1px solid black;">
[**MS10-011**](http://go.microsoft.com/fwlink/?linkid=179798)
</td>
<td style="border:1px solid black;">
[**MS10-012**](http://go.microsoft.com/fwlink/?linkid=155976)
</td>
<td style="border:1px solid black;">
[**MS10-014**](http://go.microsoft.com/fwlink/?linkid=181196)
</td>
<td style="border:1px solid black;">
[**MS10-015**](http://go.microsoft.com/fwlink/?linkid=179062)
</td>
<td style="border:1px solid black;">
[**MS10-005**](http://go.microsoft.com/fwlink/?linkid=180620)
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
[**Niski**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Brak
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=ecb06350-47a7-48eb-825f-3e8f89c5ca8e)\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=cda31c54-8b81-4185-a623-64480ad4b73c)\*\*  
(Niski)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=a9811baa-1500-4c73-940b-57f8c5456891)\*\*  
(KB975560)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=3214b347-d901-4aac-85ce-676e4602de87)\*  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach x64](http://www.microsoft.com/downloads/details.aspx?familyid=dc757b6d-f0f8-4e71-ab6f-1417233eedf9)\*  
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
<td style="border:1px solid black;">
Windows Server 2008 R2 dla systemów opartych na procesorach Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=badd6cab-7738-4401-a68c-c15414388601)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=43fa4e26-160f-4aa3-a03d-b98a79666a18)  
(Niski)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Quartz](http://www.microsoft.com/downloads/details.aspx?familyid=2ed23bf5-6217-413c-a7ba-eccc82139d68)  
(KB975560)  
(Ważny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 dla systemów opartych na procesorach Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=d5b0b1eb-24f3-47ec-aba1-c1b95400189e)  
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
</table>
 
**Uwaga dotycząca aktualizacji MS10-013**

<sup>[1]</sup> Aktualizacja dla programu DirectX 9.0 ma także zastosowanie do programów DirectX 9.0a, DirectX 9.0b oraz DirectX 9.0c w systemie Microsoft Windows 2000.

**Uwagi dotyczące systemu Windows Server 2008 i Windows Server 2008 R2**

**\*Luka w zabezpieczeniach dotyczy instalacji Server Core.** Ta aktualizacja ma zastosowanie, z takim samym wskaźnikiem ważności, w przypadku obsługiwanych wersji systemu Windows Server 2008 lub Windows Server 2008 R2, niezależnie od tego, czy zostały zainstalowane przy użyciu opcji instalacji Server Core. Aby uzyskać więcej informacji na temat tej opcji instalacji, zobacz artykuły MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (j. ang.) i [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (j. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core.** Luki usuwane przez tę aktualizację zabezpieczeń nie dotyczą obsługiwanych wersji systemu Windows Server 2008 ani Windows Server 2008 R2, jeżeli systemy te zostały zainstalowane przy użyciu opcji instalacji Server Core. Aby uzyskać więcej informacji na temat tej opcji instalacji, zobacz artykuły MSDN, [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (j. ang.) i [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) (j. ang.). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008 i Windows Server 2008 R2. Zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
[**MS10-003**](http://go.microsoft.com/fwlink/?linkid=178812)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://go.microsoft.com/fwlink/?linkid=163639)
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
[Microsoft Office XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=47553f45-fa10-40e5-8267-9d42ff560a62)  
(KB977896)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2002 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cfc697b4-2ceb-4030-86c5-be9bc8bfd07c)  
(KB973143)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Microsoft Office PowerPoint 2003 z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2291ae24-fa39-4ad8-a7d0-12726b68ad96)  
(KB976881)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office dla komputerów Macintosh
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS10-003**](http://go.microsoft.com/fwlink/?linkid=178812)
</td>
<td style="border:1px solid black;">
[**MS10-004**](http://go.microsoft.com/fwlink/?linkid=163639)
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
Microsoft Office 2004 dla komputerów Macintosh
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>
(KB979674)  
(Ważny)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 dla komputerów Macintosh](http://www.microsoft.com/downloads/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8)<sup>[1]</sup>
(KB979674)  
(Ważny)
</td>
</tr>
</table>
 
**Uwaga dotycząca pakietu Microsoft Office dla komputerów Macintosh**

<sup>[1]</sup>Ze względu na zbiorczy model usług dla pakietu Microsoft Office 2004 dla komputerów Macintosh te aktualizacje są identyczne.

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

-   Damian Frizza z firmy [Core Security Technologies](http://www.coresecurity.com/) za zgłoszenie problemu opisanego w biuletynie MS10-003
-   Carsten Eiram z firmy [Secunia](http://secunia.com/) za zgłoszenie problemu opisanego w biuletynie MS10-004
-   Sean Larsson z firmy [VeriSign iDefense Labs](http://labs.idefense.com/) za zgłoszenie trzech problemów opisanych w biuletynie MS10-004
-   SkD, we współpracy z oddziałem [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy [TippingPoint](http://www.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-004
-   Cody Pierce z firmy [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/), za zgłoszenie problemu opisanego w biuletynie MS10-004
-   Tielei Wang z ośrodka ICST-ERCIS (Engineering Research Center of Info Security, Institute of Computer Science & Technology, Uniwersytet Pekiński, Chiny), we współpracy z firmą [Secunia](http://secunia.com/), za zgłoszenie problemu opisanego w biuletynie MS10-005
-   Laurent Gaffié z firmy [stratsec](http://www.stratsec.net/) za zgłoszenie dwóch problemów opisanych w biuletynie MS10-006
-   Brett Moore, we współpracy z firmami [TippingPoint](http://www.tippingpoint.com/) i [Zero Day Initiative](http://www.zerodayinitiative.com/), za zgłoszenie problemu opisanego w biuletynie MS10-007
-   [Lostmon Lords](http://lostmon.blogspot.com/) za zgłoszenie problemu opisanego w biuletynie MS10-007
-   Shaun Colley z firmy [NGS Software](http://www.ngssoftware.com/) za zgłoszenie problemu opisanego w biuletynie MS10-008
-   Sumit Gwalani, Drew Hintz i Neel Mehta z [Google Security Team](http://www.google.com/) za zgłoszenie trzech problemów opisanych w biuletynie MS10-009
-   Jan Bottorff za zgłoszenie problemu opisanego w biuletynie MS10-010
-   Matthew „j00ru” Jurczyk i Gynvael Coldwind z firmy [Hispasec](http://www.hispasec.com/) za zgłoszenie problemu opisanego w biuletynie MS10-011
-   Joshua Morin z firmy [Codenomicon](http://www.codenomicon.com/), za zgłoszenie problemu opisanego w biuletynie MS10-012
-   Florian Rienhardt z firmy [BSI](http://www.bsi.bund.de/) za zgłoszenie problemu opisanego w biuletynie MS10-012
-   Hernan Ochowa (niezależny konsultant/analityk zajmujący się bezpieczeństwem informacji) za zgłoszenie problemu opisanego w biuletynie MS10-012
-   Anonimowy analityk współpracujący z firmami [TippingPoint](http://www.tippingpoint.com/) i [Zero Day Initiative](http://www.zerodayinitiative.com/) za zgłoszenie problemu opisanego w biuletynie MS10-013
-   Tavis Ormandy z firmy [Google Inc.](http://www.google.com/) za zgłoszenie problemu opisanego w biuletynie MS10-015

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pod numerem 0 801 802 000 (Opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne. Dodatkowe informacje dotyczące możliwości skorzystania z pomocy technicznej można znaleźć w witrynie [Pomoc i obsługa techniczna firmy Microsoft](http://support.microsoft.com/).
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (9 lutego 2010 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.
-   Wersja 1.1 (10 lutego 2010 r.): Poprawiono wymagania dotyczące ponownego uruchomienia dla biuletynu MS10-005.

*Built at 2014-04-18T01:50:00Z-07:00*
