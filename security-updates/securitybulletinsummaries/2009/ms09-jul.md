---
TOCTitle: 'MS09-JUL'
Title: 'Podsumowanie biuletynów zabezpieczeń firmy Microsoft za lipiec 2009 r.'
ms:assetid: 'ms09-jul'
ms:contentKeyID: 61233101
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms09-jul(v=Security.10)'
---
Podsumowanie biuletynów zabezpieczeń firmy Microsoft za lipiec 2009 r.
======================================================================

Opublikowano: 14 lipca 2009 | Zaktualizowano: 9 marca 2010

**Wersja:** 8.0

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za lipiec 2009 r.

Z chwilą opublikowania biuletynów za lipiec 2009 r. niniejsze podsumowanie biuletynów zastępuje powiadomienie o biuletynach zabezpieczeń wydane 9 lipca 2009 r. oraz powiadomienie o biuletynach pozaplanowych wydane 24 lipca 2009 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j. ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

15 lipca 2009 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępniła emisję internetową, w której znalazły się odpowiedzi na pytania klientów dotyczące regularnie publikowanych biuletynów (USA i Kanada). Emisja ta jest obecnie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

W odniesieniu do pozaplanowych biuletynów zabezpieczeń, MS09-034 i MS09-035, dodanych do wersji 2.0 niniejszego podsumowania biuletynów, 28 lipca 2009 r. o godz. 13:00 czasu Pacyfiku (godz. 22:00 czasu środkowoeuropejskiego) oraz o godz. 16:00 czasu Pacyfiku (29 lipca 2009 r., godz. 01:00 czasu środkowoeuropejskiego) firma Microsoft udostępni dwie emisje internetowe, zawierające odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). Zarejestruj się, aby obejrzeć emisję internetową z dn. [28 lipca, godz. 13:00 czasu Pacyfiku (godz. 22:00 czasu środkowoeuropejskiego)](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us) oraz z dn. [28 lipca, godz. 16:00 czasu Pacyfiku (29 lipca 2009 r., godz. 01:00 czasu środkowoeuropejskiego)](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us). Emisje internetowe będą później dostępne na żądanie. Aby uzyskać więcej informacji, zobacz [Podsumowania biuletynów zabezpieczeń i emisje internetowe firmy Microsoft](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach aparatu osadzonych czcionek OpenType umożliwiają zdalne wykonanie kodu (961371)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa dwie luki w zabezpieczeniach aparatu osadzonych czcionek OpenType (EOT), które zostały zgłoszone przez użytkowników. Luki te mogą umożliwić zdalne wykonanie kodu. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może zdalnie uzyskać pełną kontrolę nad atakowanym systemem. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach programu Microsoft DirectShow umożliwiają zdalne wykonanie kodu (971633)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa jedną lukę zgłoszoną przez organizacje publiczne oraz dwie luki zgłoszone przez użytkowników, istniejące w programie Microsoft DirectShow. Luki te umożliwiają zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik multimedialny QuickTime. Osoba atakująca, której uda się wykorzystać jedną z tych luk, może uzyskać takie same uprawnienia, jak użytkownik lokalny. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td style="border:1px solid black;"><strong>Zbiorcza aktualizacja zabezpieczeń bitów „zabicia” dla formantów ActiveX (973346)</strong><br />
<br />
Ta aktualizacja zabezpieczeń pozwala usunąć zgłoszoną przez użytkowników lukę w zabezpieczeniach, która jest aktualnie wykorzystywana. Luka w zabezpieczeniach formantu ActiveX Microsoft Video może pozwolić na zdalne wykonanie kodu, jeśli użytkownik wyświetli przy użyciu programu Internet Explorer specjalnie spreparowaną stronę sieci Web, uruchamiając ten formant. Nigdy nie planowano tworzenia wystąpień tego formantu ActiveX w programie Internet Explorer. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Zbiorcza aktualizacja zabezpieczeń dla programu Internet Explorer (972260)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń została opublikowana poza harmonogramem w powiązaniu z biuletynem zabezpieczeń firmy Microsoft MS09-035 zawierającym opis luk w zabezpieczeniach w składnikach i formantach utworzonych przy użyciu wersji biblioteki Microsoft Active Template Library (ATL), w których występuje luka. W ramach dodatkowego wzmocnienia ochrony ta aktualizacja zabezpieczeń programu Internet Explorer przyczynia się również do zmniejszenia zagrożenia ze strony znanych kierunków ataków w ramach programu Internet Explorer w odniesieniu do tych składników i formantów, które zostały utworzone za pomocą podlegających luce wersji biblioteki ATL, opisanych w poradniku zabezpieczeń firmy Microsoft (973882) oraz w biuletynie zabezpieczeń firmy Microsoft MS09-035.<br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa także trzy luki w zabezpieczeniach programu Internet Explorer, które zostały zgłoszone przez użytkowników. Luki te mogą pozwolić na zdalne wykonanie kodu, jeśli użytkownik wyświetli specjalnie spreparowaną stronę sieci Web przy użyciu programu Internet Explorer. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Krytyczny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programów Virtual PC i Virtual Server umożliwia podniesienie poziomu uprawnień (969856)</strong><br />
<br />
Ta aktualizacja zabezpieczeń usuwa zgłoszoną przez użytkowników lukę w zabezpieczeniach programów Microsoft Virtual PC i Microsoft Virtual Server. Osoba atakująca, której uda się wykorzystać tę lukę, mogłaby wykonać dowolny kod i uzyskać pełną kontrolę nad systemem operacyjnym gościa, którego dotyczy luka. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Virtual PC, Virtual Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft ISA Server 2006 może spowodować podniesienie uprawnień (970953)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach programu Microsoft Internet Security and Acceleration (ISA) Server 2006 zgłoszoną przez użytkowników. Luka ta umożliwia podniesienie poziomu uprawnień, jeśli osoba atakująca pomyślnie podszyje się pod konto administratora serwera ISA skonfigurowane do uwierzytelniania Radius One Time Password (OTP) i delegacji uwierzytelniania przy użyciu funkcji Kerberos Constrained Delegation.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Podniesienie uprawnień</td>
<td style="border:1px solid black;">Wymaga ponownego uruchomienia komputera</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td style="border:1px solid black;"><strong>Luka w zabezpieczeniach programu Microsoft Office Publisher umożliwia zdalne wykonanie kodu (969516)</strong><br />
<br />
Ta aktualizacja zabezpieczeń pozwala usunąć lukę w zabezpieczeniach programu Microsoft Office Publisher zgłoszoną przez osobę prywatną, która może pozwolić na zdalne wykonanie kodu, jeśli użytkownik otworzy specjalnie spreparowany plik programu Publisher. Osoba atakująca, której uda się wykorzystać tę lukę, może uzyskać pełną kontrolę nad systemem, którego dotyczy luka. Osoba taka może wówczas instalować programy, przeglądać, zmieniać i usuwać dane oraz tworzyć nowe konta z pełnymi uprawnieniami. Użytkownicy, których konta zostały skonfigurowane w taki sposób, że mają niewielkie uprawnienia w systemie, ponoszą mniejsze ryzyko niż ci, którzy pracują z uprawnieniami administracyjnymi.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Ważny</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Luki w zabezpieczeniach biblioteki Active Template Library programu Visual Studio mogą umożliwić zdalne wykonanie kodu (969706)</strong><br />
<br />
Niniejsza aktualizacja zabezpieczeń usuwa kilka luk w publicznych wersjach biblioteki Active Template Library (ATL) firmy Microsoft, zawartej w programie Visual Studio, które zostały zgłoszone przez użytkowników. Ta aktualizacja zabezpieczeń przeznaczona jest dla deweloperów zajmujących się tworzeniem składników i formantów. Deweloperzy zajmujący się tworzeniem oraz dystrybucją składników oraz formantów wykorzystujących bibliotekę ATL powinni zainstalować aktualizację zabezpieczeń dostarczoną w ramach niniejszego biuletynu oraz skorzystać z porad w nim przedstawionych, by móc tworzyć i dystrybuować do swoich klientów składniki oraz formanty nie podlegające lukom opisanym w niniejszym biuletynie zabezpieczeń.<br />
<br />
Niniejszy biuletyn zabezpieczeń omawia luki, które umożliwiają zdalne wykonanie kodu, jeżeli użytkownik wczyta składnik lub formant stworzony za pomocą podlegających luce wersji biblioteki ATL.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Umiarkowany</a><br />
Zdalne wykonanie kodu</td>
<td style="border:1px solid black;">Może wymagać ponownego uruchomienia</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
</tbody>
</table>
  
Wskaźnik możliwości wykorzystania luki  
--------------------------------------
  
<span></span>
Poniższa tabela przedstawia ocenę możliwości wykorzystania luk dla każdej luki opisywanej w tym miesiącu. Luki są wymienione wg identyfikatora biuletynu i identyfikatora CVE.
  
**W jaki sposób korzystać z tej tabeli?**
  
Tabela ta pozwala sprawdzić prawdopodobieństwo, że w ciągu 30 dni od wydania biuletynu zabezpieczeń dla każdej z aktualizacji zabezpieczeń, których zainstalowanie może być potrzebne, opublikowany zostanie działający kod wykorzystujący lukę w zabezpieczeniach. Aby ustalić priorytety wdrażania, zapoznaj się z dostępnymi poniżej ocenami, rozpatrując je w kontekście posiadanej konfiguracji. Więcej informacji na temat znaczenia tych ocen oraz sposobu ich wyznaczania można znaleźć na stronie sieci Web [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Identyfikator biuletynu                                   | Tytuł biuletynu                                                                                                                 | CVE ID                                                                           | Ocena wskaźnika możliwości wykorzystania luki                                                                              | Najważniejsze uwagi                                                                             |  
|-----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Luka w zabezpieczeniach programu Microsoft DirectShow umożliwia zdalne wykonanie kodu (971633)                                  | [CVE-2009-1537](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | **Ta luka w zabezpieczeniach jest aktualnie wykorzystywana w Internecie.**                      |  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Luka w zabezpieczeniach programu Microsoft DirectShow umożliwia zdalne wykonanie kodu (971633)                                  | [CVE-2009-1538](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                          |  
| [MS09-028](http://go.microsoft.com/fwlink/?linkid=152887) | Luka w zabezpieczeniach programu Microsoft DirectShow umożliwia zdalne wykonanie kodu (971633)                                  | [CVE-2009-1539](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                          |  
| [MS09-029](http://go.microsoft.com/fwlink/?linkid=139788) | Luki w zabezpieczeniach aparatu osadzonych czcionek OpenType umożliwiają zdalne wykonanie kodu (961371)                         | [CVE-2009-0231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                          |  
| [MS09-029](http://go.microsoft.com/fwlink/?linkid=139788) | Luki w zabezpieczeniach aparatu osadzonych czcionek OpenType umożliwiają zdalne wykonanie kodu (961371)                         | [CVE-2009-0232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                          |  
| [MS09-030](http://go.microsoft.com/fwlink/?linkid=147424) | Luka w zabezpieczeniach programu Microsoft Office Publisher umożliwia zdalne wykonanie kodu (969516)                            | [CVE-2009-0566](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                          |  
| [MS09-031](http://go.microsoft.com/fwlink/?linkid=154993) | Luka w zabezpieczeniach programu Microsoft ISA Server 2006 może spowodować podniesienie uprawnień (970953)                      | [CVE-2009-1135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | (Brak)                                                                                          |  
| [MS09-032](http://go.microsoft.com/fwlink/?linkid=157386) | Zbiorcza aktualizacja zabezpieczeń bitów „zabicia” dla formantów ActiveX (973346)                                               | [CVE-2008-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | **Ta luka w zabezpieczeniach jest aktualnie wykorzystywana w Internecie.**                      |  
| [MS09-033](http://go.microsoft.com/fwlink/?linkid=153891) | Luka w zabezpieczeniach programów Virtual PC i Virtual Server umożliwia podniesienie poziomu uprawnień (969856)                 | [CVE-2009-1542](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | Funkcjonalne wykonanie kodu jest możliwe, ale skutkuje niespójnymi efektami wykorzystania luki. |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Zbiorcza aktualizacja zabezpieczeń dla programu Internet Explorer (972260)                                                      | [CVE-2009-1917](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | Funkcjonalne wykonanie kodu jest proste i niezawodne.                                           |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Zbiorcza aktualizacja zabezpieczeń dla programu Internet Explorer (972260)                                                      | [CVE-2009-1918](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | Funkcjonalne wykonanie kodu jest możliwe, ale skutkuje niespójnymi efektami wykorzystania luki. |  
| [MS09-034](http://go.microsoft.com/fwlink/?linkid=158199) | Zbiorcza aktualizacja zabezpieczeń dla programu Internet Explorer (972260)                                                      | [CVE-2009-1919](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny niespójny kod wykorzystujący lukę       | Funkcjonalne wykonanie kodu jest możliwe, ale skutkuje niespójnymi efektami wykorzystania luki. |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Luki w zabezpieczeniach biblioteki Active Template Library programu Visual Studio mogą umożliwić zdalne wykonanie kodu (969706) | [CVE-2009-0901](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | Funkcjonalne wykonanie kodu jest proste i niezawodne.                                           |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Luki w zabezpieczeniach biblioteki Active Template Library programu Visual Studio mogą umożliwić zdalne wykonanie kodu (969706) | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - prawdopodobny spójny kod wykorzystujący lukę          | Funkcjonalne wykonanie kodu jest proste i niezawodne.                                           |  
| [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) | Luki w zabezpieczeniach biblioteki Active Template Library programu Visual Studio mogą umożliwić zdalne wykonanie kodu (969706) | [CVE-2009-2495](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - działający kod wykorzystujący lukę mało prawdopodobny | Wyłącznie błąd pozwalający na ujawnienie informacji, bez ryzyka uruchomienia kodu.              |
  
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
</tr>
<tr>
<th colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 z dodatkiem Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[DirectX 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3)  
(Krytyczny)  
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d)\*\*\*  
(Krytyczny)  
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda)\*\*\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72)  
(Brak wskaźnika ważności\*\*)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 z dodatkiem Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd)  
(Krytyczny)  
[Microsoft Internet Explorer 6 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282)  
(Krytyczny)
</td>
</tr>
<tr>
<th colspan="5">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80)\*\*\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP z dodatkiem Service Pack 2 i Windows XP z dodatkiem Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a)  
(Krytyczny)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568)  
(Krytyczny)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00)  
(Krytyczny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4)\*\*\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350)  
(Krytyczny)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba)  
(Krytyczny)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab)  
(Krytyczny)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc)\*\*\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9)  
(Umiarkowany)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af)  
(Umiarkowany)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e)\*\*\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2)  
(Umiarkowany)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d)  
(Umiarkowany)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042)\*\*\*\*  
(Krytyczny)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5)  
(Umiarkowany)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc)  
(Umiarkowany)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071)  
(Umiarkowany)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
Brak
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista z dodatkiem Service Pack 1 i Windows Vista z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45)  
(Brak wskaźnika ważności\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573)  
(Krytyczny)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43)  
(Krytyczny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition z dodatkiem Service Pack 1 i Windows Vista x64 Edition z dodatkiem Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7)  
(Brak wskaźnika ważności\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6)  
(Krytyczny)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb)  
(Krytyczny)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://go.microsoft.com/fwlink/?linkid=139788)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://go.microsoft.com/fwlink/?linkid=152887)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://go.microsoft.com/fwlink/?linkid=157386)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://go.microsoft.com/fwlink/?linkid=158199)
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
Brak
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
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów 32-bitowych i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów 32-bitowych\*](http://www.microsoft.com/downloads/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995)  
(Brak wskaźnika ważności\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead)\*  
(Umiarkowany)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae)\*  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem x64 i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem x64\*](http://www.microsoft.com/downloads/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0)  
(Brak wskaźnika ważności\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516)\*  
(Umiarkowany)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93)\*  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d)  
(Krytyczny)
</td>
<td style="border:1px solid black;">
Nie dotyczy
</td>
<td style="border:1px solid black;">
[Windows Server 2008 dla systemów z procesorem Itanium i Windows Server 2008 z dodatkiem Service Pack 2 dla systemów z procesorem Itanium](http://www.microsoft.com/downloads/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a)  
(Brak wskaźnika ważności\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d)  
(Umiarkowany)
</td>
</tr>
</table>
 
**Uwagi dotyczące systemu Windows Server 2008**

**\*Luka w zabezpieczeniach nie dotyczy instalacji Server Core systemu operacyjnego Windows Server 2008.** Lukom usuwanym przez tę aktualizację zabezpieczeń nie podlegają obsługiwane wersje systemu Windows Server 2008, jeżeli system Windows Server 2008 został zainstalowany przy użyciu opcji instalacji Server Core. Aby uzyskać więcej informacji na temat tej opcji instalacji, zobacz [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). Należy pamiętać, że opcja instalacji Server Core nie dotyczy niektórych wersji systemu Windows Server 2008; zobacz [Porównanie opcji instalacji Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Uwaga dotycząca biuletynu MS09-032**

**Do tej aktualizacji nie stosuje się wskaźników ważności, ponieważ omawiana w biuletynie luka w zabezpieczeniach nie ma wpływu na to oprogramowanie. Jednak w ramach dodatkowego wzmocnienia ochrony przed ewentualnymi nowymi kierunkami ataku, które mogą zostać rozpoznane w przyszłości, firma Microsoft zaleca, aby użytkownicy tego oprogramowania zainstalowali omawianą aktualizację zabezpieczeń.

**Uwagi dotyczące biuletynu MS09-028**

***Aktualizacja programu DirectX 8.1 ma także zastosowanie do programu DirectX 8.1b.

****Aktualizacja dla programu DirectX 9.0 ma także zastosowanie do programów DirectX 9.0a, DirectX 9.0b oraz DirectX 9.0c.

#### Pakiety i oprogramowanie Office

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Pakiety Microsoft Office, systemy i ich składniki
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-030**](http://go.microsoft.com/fwlink/?linkid=147424)
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
Pakiet Microsoft Office 2007 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8)  
(KB969693)  
(Ważny)
</td>
</tr>
</table>
 

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
[**MS09-035**](http://go.microsoft.com/fwlink/?linkid=158131)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Umiarkowany**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e)  
(KB971089)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197)  
(KB971090)  
(Umiarkowany)  
[Microsoft Visual Studio 2005 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42)\*  
(KB973673)  
(Umiarkowany)  
[Microsoft Visual Studio 2005 Service Pack 1 64-bit Hosted Visual C++ Tools](http://www.microsoft.com/downloads/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2)  
(KB973830)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Embedded CE 6.0
</td>
<td style="border:1px solid black;">
[Windows Embedded CE 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8)\*\*  
(KB974616)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c)  
(KB971091)  
(Umiarkowany)  
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd)\*  
(KB973674)  
(Umiarkowany)  
[Microsoft Visual Studio 2008 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb)  
(KB971092)  
(Umiarkowany)  
[Microsoft Visual Studio 2008 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f)\*  
(KB973675)  
(Umiarkowany)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005
</td>
<td style="border:1px solid black;">
[Pakiet redystrybucyjny programu Microsoft Visual C++ 2005 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2)  
(KB973544)  
(Umiarkowany)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008
</td>
<td style="border:1px solid black;">
[Pakiet redystrybucyjny programu Microsoft Visual C++ 2008](http://www.microsoft.com/downloads/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93)  
(KB973551)  
(Umiarkowany)  
[Pakiet redystrybucyjny programu Microsoft Visual C++ 2008 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c)  
(KB973552)  
(Umiarkowany)
</td>
</tr>
</table>
 
**Uwagi dotyczące biuletynu MS09-035**

\*Dla aplikacji na urządzenia przenośne korzystających z biblioteki ATL for Smart Devices

\*\* Instaluje comiesięczną aktualizację systemu Windows Embedded CE 6.0 (grudzień 2009). Ten pakiet aktualizacji jest dostępny tylko w witrynie Microsoft Download Center.

#### Oprogramowanie serwerów i oprogramowanie zabezpieczające firmy Microsoft

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-031**](http://go.microsoft.com/fwlink/?linkid=154993)
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
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19)  
(KB970811)  
(Ważny)  
[Aktualizacja dotycząca możliwości obsługi programu Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476)  
(KB970811)  
(Ważny)  
[Microsoft Internet Security and Acceleration Server 2006 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5)  
(KB971143)  
(Ważny)
</td>
</tr>
</table>
 

#### Oprogramowanie firmy Microsoft do wirtualizacji

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Narzędzie Microsoft Virtual PC
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://go.microsoft.com/fwlink/?linkid=153891)
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
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2004 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad)  
(KB969856)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2007
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(Ważny)  
[Microsoft Virtual PC 2007 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2007 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a)  
(KB969856)  
(Ważny)  
[Microsoft Virtual PC 2007 x64 Edition z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0)  
(KB969856)  
(Ważny)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Virtual Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://go.microsoft.com/fwlink/?linkid=153891)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Zbiorczy wskaźnik ważności**
</td>
<td style="border:1px solid black;">
[**Ważny**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005](http://www.microsoft.com/downloads/details.aspx?familyid=092a389a-2296-4c3b-a160-2523154ec764)  
(KB969856)  
(Ważny)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(Ważny)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition z dodatkiem Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57)  
(KB969856)  
(Ważny)
</td>
</tr>
</table>
 

Narzędzia wykrywania i wdrażania oraz wskazówki
-----------------------------------------------

<span></span>
**Centrum zabezpieczeń**

Zarządzanie oprogramowaniem oraz aktualizacjami zabezpieczeń, które należy zainstalować na serwerach oraz komputerach stacjonarnych i przenośnych w organizacji. Więcej informacji można znaleźć w [Centrum TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Witryna [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) zawiera dodatkowe informacje na temat zabezpieczeń w produktach firmy Microsoft. Użytkownicy mogą także uzyskać dostęp do tych informacji w witrynie [Bezpieczeństwo w domu](http://go.microsoft.com/fwlink/?linkid=85102), klikając łącze „Najnowsze aktualizacje zabezpieczeń”.

Aktualizacje zabezpieczeń dostępne są w witrynach [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) i [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Aktualizacje zabezpieczeń są także dostępne w witrynie [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.

Aktualizacje zabezpieczeń można także pobierać z [Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=96155). Wykaz usługi Microsoft Update zawiera katalog zawartości z możliwością przeszukiwania, który udostępniany jest poprzez usługi Windows Update i Microsoft Update i obejmuje aktualizacje zabezpieczeń, sterowniki i dodatki Service Pack. Wyszukiwanie przy użyciu numeru biuletynu zabezpieczeń (np. „MS07-036”) pozwala dodać do koszyka wszystkie odpowiednie aktualizacje (w tym różne wersje językowe aktualizacji) i pobrać pliki do wybranego folderu. Więcej informacji na temat Wykazu usługi Microsoft Update można znaleźć w [Często zadawanych pytaniach dotyczących Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=97900).

**Uwaga** Dnia 1 sierpnia 2009 r. firma Microsoft zakończy świadczenie pomocy technicznej dla usługi Office Update oraz narzędzia Office Update Inventory Tool. Aby w dalszym ciągu otrzymywać najnowsze aktualizacje dla produktów Microsoft Office, skorzystaj z witryny [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Aby uzyskać więcej informacji, zobacz artykuł [Informacje o witrynie Microsoft Office Update: Często zadawane pytania](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Porady dotyczące wykrywania i wdrażania**

Firma Microsoft opublikowała porady dotyczące wykrywania i wdrażania, odnoszące się do aktualizacji zabezpieczeń udostępnionych w tym miesiącu. Porady te będą również pomocne dla informatyków, wyjaśniając, jak mogą oni wdrażać aktualizacje za pomocą różnych narzędzi, takich jak Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS) i Extended Security Update Inventory Tool (ESUIT). Więcej informacji na ten temat można znaleźć w [artykule 910723 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/910723).

**Narzędzie Microsoft Baseline Security Analyzer (MBSA)**

Narzędzie Microsoft Baseline Security Analyzer umożliwia administratorom skanowanie lokalnych i zdalnych systemów w poszukiwaniu brakujących aktualizacji zabezpieczeń oraz typowych błędów konfiguracji zabezpieczeń. Więcej informacji na temat narzędzia MBSA można znaleźć w witrynie sieci Web[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Korzystając z programu Windows Server Update Services (WSUS), administratorzy mogą szybko i niezawodnie wdrożyć najnowsze aktualizacje krytyczne i aktualizacje zabezpieczeń przeznaczonych dla systemu operacyjnego Windows 2000 i nowszych, pakietu Office XP i nowszych, programu Exchange Server 2003 oraz SQL Server 2000 w systemie operacyjnym Windows 2000 i nowszych.

Więcej informacji na temat sposobu wdrażania tej aktualizacji zabezpieczeń za pomocą programu Windows Server Update Services można znaleźć w [witrynie sieci Web programu Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Program Systems Management Server**

Program Systems Management Server (SMS) jest przeznaczonym dla przedsiębiorstw i w znacznym stopniu konfigurowalnym rozwiązaniem służącym do zarządzania aktualizacjami. Program SMS umożliwia administratorom znalezienie komputerów z systemem Windows, na których należy zainstalować aktualizację zabezpieczeń, a także przeprowadzić kontrolowane wdrożenie tych aktualizacji w całym przedsiębiorstwie, w minimalnym stopniu zakłócając przy tym pracę użytkowników końcowych. Dostępne jest kolejne wydanie programu SMS, System Center Configuration Manager 2007. Zapoznaj się także z zawartością witryny [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Więcej informacji na temat możliwości wykorzystania przez administratorów programu SMS 2003 do wdrażania aktualizacji zabezpieczeń można znaleźć w [witrynie sieci Web zarządzania poprawkami zabezpieczeń programu SMS 2003](http://go.microsoft.com/fwlink/?linkid=22939). Użytkownicy programu SMS 2.0 mogą także skorzystać z dodatku [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) ułatwiającego wdrożenie aktualizacji zabezpieczeń. Więcej informacji na temat programu SMS można znaleźć w witrynie sieci Web [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Uwaga** Program SMS zapewnia obsługę rozwiązań zawartych w biuletynach zabezpieczeń dzięki narzędziom Microsoft Baseline Security Analyzer oraz Microsoft Office Detection Tool. Narzędzia te mogą nie wykrywać wszystkich aktualizacji oprogramowania. W takich przypadkach administratorzy mogą wykorzystywać dostępne w programie SMS funkcje zarządzania zasobami do przyporządkowania poszczególnych aktualizacji określonym systemom. Aby uzyskać więcej informacji dotyczących tej procedury, zobacz [Wdrażanie aktualizacji oprogramowania za pomocą funkcji Software Distribution programu SMS](http://go.microsoft.com/fwlink/?linkid=33341). Niektóre aktualizacje oprogramowania wymagają od użytkownika uprawnień administratora po ponownym uruchomieniu systemu. Do zainstalowania tych aktualizacji administratorzy mogą użyć narzędzia Elevated Rights Deployment Tool (dostępnego w dodatkach [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) oraz [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)).

**Tester zgodności aktualizacji i zestaw narzędzi do sprawdzania zgodności aplikacji**

Często aktualizacje zapisują informacje w tych samych plikach i ustawieniach rejestru niezbędnych do działania określonych aplikacji użytkownika. Może to prowadzić do niezgodności i wydłużyć czas wdrażania aktualizacji zabezpieczeń. Dzięki składnikom narzędzia [Tester zgodności aplikacji](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) znajdującego się w [Zestawie narzędzi do sprawdzania zgodności aplikacji 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) można usprawnić proces testowania i sprawdzania poprawności aktualizacji systemu Windows.

W Zestawie narzędzi do sprawdzania zgodności aplikacji znajdują się niezbędne narzędzia i dokumentacja, które umożliwiają ocenę zgodności aplikacji przed wdrożeniem systemu Microsoft Windows Vista, aktualizacji dla systemu Windows, aktualizacji zabezpieczeń firmy Microsoft lub nowej wersji programu Windows Internet Explorer w środowisku użytkownika, oraz ograniczenie problemów ze zgodnością aplikacji.

### Inne informacje:

#### Narzędzie Microsoft Windows do usuwania złośliwego oprogramowania

Firma Microsoft opublikowała zaktualizowaną wersję narzędzia Microsoft Windows Malicious Software Removal Tool, która dostępna jest w witrynach sieci Web Windows Update i Microsoft Update, poprzez usługi Windows Server Update Services i w witrynie Microsoft Download Center.

#### Aktualizacje o wysokim priorytecie niezwiązane z zabezpieczeniami, dostępne w witrynach MU, WU oraz usługach WSUS

Aby uzyskać informacje na temat publikacji niezwiązanych z zabezpieczeniami, dostępnych w witrynach Windows Update i Microsoft Update, zobacz:

-   [Artykuł 894199 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/894199): Opis zmian zawartości Usług aktualizacji oprogramowania i usług Windows Server Update Services. Zawiera wszystkie treści dotyczące systemu Windows.
-   [Nowe, zmienione i opublikowane aktualizacje dla produktów firmy Microsoft innych niż Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

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

-   Thomasowi Garnier z firmy [SkyRecon](http://www.skyrecon.com/) i Zheng Wenbin, Liu Qi oraz Song Shenlei z firmy [Qihoo 360 Security Center](http://www.360.cn/) za zgłoszenie problemu opisanego w biuletynie MS09-028
-   Yamata Li z firmy [Palo Alto Networks](http://www.paloaltonetworks.com/), za zgłoszenie problemu opisanego w biuletynie MS09-028
-   Aaronowi Portnoy z firmy [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) oraz anonimowemu analitykowi współpracującemu z [Zero Day Initiative](http://www.zerodayinitiative.com/) firmy TippingPoint, Thomasowi Garnier z firmy [SkyRecon](http://www.skyrecon.com/) oraz Yamata Li z firmy [Palo Alto Networks](http://www.paloaltonetworks.com/), za zgłoszenie problemu opisanego w biuletynie MS09-028
-   Firmie [VeriSign iDefense Labs](http://labs.idefense.com/) za zgłoszenie problemu opisanego w biuletynie MS09-029
-   Tavis Ormandy z firmy [Google Inc.](http://www.google.com) za zgłoszenie problemu opisanego w biuletynie MS09-029
-   Thomasowi Garnier, za zgłoszenie problemu opisanego w biuletynie MS09-029
-   Lionelowi d'Hauenens z firmy [Labo Skopia](http://www.laboskopia.com/), we współpracy z firmą [VeriSign iDefense Labs](http://www.idefense.com/), za zgłoszenie problemu opisanego w biuletynie MS09-030
-   Ryanowi Smith i Alexowi Wheeler z firmy [IBM ISS X-Force](http://www.iss.net/) za początkowe zgłoszenie problemu opisanego w biuletynie MS09-032
-   Julienowi Tinnes i Tavisowi Ormandy z firmy [Google Inc.](http://www.google.com/), za zgłoszenie problemu opisanego w biuletynie MS09-033
-   Peterowi Vreugdenhil z firmy [VeriSign iDefense Labs](http://labs.idefense.com/) za zgłoszenie problemu opisanego w biuletynie MS09-034
-   Wushi i Ling z firmy [team509](http://www.team509.com/), we współpracy z firmami [TippingPoint](http://www.tippingpoint.com/) i [Zero Day Initiative](http://www.zerodayinitiative.com/), za zgłoszenie problemu opisanego w biuletynie MS09-034
-   Peterowi Vreugdenhil, współpracownik firm [TippingPoint](http://www.tippingpoint.com/) i [Zero Day Initiative,](http://www.zerodayinitiative.com/) za zgłoszenie problemu opisanego w biuletynie MS09-034
-   Davidowi Dewey z firmy [IBM ISS X-Force](http://www.iss.net/), za zgłoszenie problemu opisanego w biuletynie MS09-035
-   Ryanowi Smith z firmy [VeriSign iDefense Labs](http://labs.idefense.com/), za zgłoszenie dwóch problemów opisanych w biuletynie MS09-035

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://go.microsoft.com/fwlink/?linkid=21131) pod numerem 0 801 802 000 (Opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne. Dodatkowe informacje dotyczące możliwości skorzystania z pomocy technicznej można znaleźć w witrynie [Pomoc i obsługa techniczna firmy Microsoft](http://support.microsoft.com/).
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (14 lipca 2009 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.
-   Wersja 1.1 (15 lipca 2009 r.): Zaktualizowano streszczenie dla biuletynu MS09-032, poprawiono wymagania dotyczące ponownego uruchomienia dla MS09-029 oraz wprowadzono różne zmiany.
-   Wersja 2.0 (28 lipca 2009 r.): Dodano biuletyn zabezpieczeń firmy Microsoft MS09-034, Zbiorcza aktualizacja zabezpieczeń dla programu Internet Explorer (972260), oraz MS09-035, Luki w zabezpieczeniach biblioteki Active Template Library programu Visual Studio mogą umożliwić zdalne wykonanie kodu (969706). Dodano także łącza do emisji internetowej odnoszące się do tych opublikowanych poza cyklem standardowym biuletynów zabezpieczeń.
-   Wersja 3.0 (4 sierpnia 2009 r.): Zaktualizowano w celu poinformowania o ponownym wydaniu aktualizacji dla programu Microsoft Internet Explorer 6 z dodatkiem Service Pack 1 w systemie Microsoft Windows 2000 z dodatkiem Service Pack 4. Wszyscy użytkownicy, którzy zainstalowali oryginalną aktualizację programu Internet Explorer 6 z dodatkiem Service Pack 1 w systemie Microsoft Windows 2000 z dodatkiem Service Pack 4, są już zabezpieczeni. Jednak użytkownicy programu Internet Explorer 6 z dodatkiem Service Pack 1 w koreańskiej wersji językowej mogą ponownie zainstalować aktualizację programu Internet Explorer 6 z dodatkiem Service Pack 1 w systemie Windows 2000 w celu uzyskania identycznych zabezpieczeń, a także rozwiązania problemu z drukowaniem. Zobacz biuletyn zabezpieczeń firmy Microsoft MS09-034.
-   V4.0 (11 sierpnia 2009 r.): Zaktualizowano w celu poinformowania o ponownym wydaniu biuletynu MS09-035. Biuletyn MS09-035 został opublikowany ponownie, aby udostępnić nowe aktualizacje deweloperom, którzy korzystają z programu Visual Studio i biblioteki ATL for Smart Devices do tworzenia składników i formantów dla aplikacji na urządzenia przenośne. Są to aktualizacje dla programów Microsoft Visual Studio 2005 z dodatkiem Service Pack 1 (KB973673), Microsoft Visual Studio 2008 (KB973674) i Microsoft Visual Studio 2008 z dodatkiem Service Pack 1 (KB973675).
-   Wersja 4.1 (13 sierpnia 2009 r.): Poprawiono wymaganie dotyczące ponownego uruchomienia dla MS09-035.
-   Wersja 5.0 (19 sierpnia 2009 r.): Dodano przypis dolny dla biuletynu MS09-028 w celu wyjaśnienia kwestii programów, których dotyczy problem, w odniesieniu do programu DirectX 8.1.
-   Wersja 6.0 (25 sierpnia 2009 r.): Zaktualizowano w celu poinformowania o ponownym wydaniu aktualizacji japońskiej wersji językowej dla systemów Windows XP z dodatkiem Service Pack 2, Windows XP z dodatkiem Service Pack 3 oraz Windows XP Professional x64 Edition z dodatkiem Service Pack 2. Wszyscy użytkownicy, którzy zainstalowali oryginalną aktualizację, są już zabezpieczeni. Jednakże klienci posiadający japońską wersję językową systemu Windows XP z dodatkiem Service Pack 2, Windows XP z dodatkiem Service Pack 3 lub Windows XP Professional x64 Edition z dodatkiem Service Pack 2 powinni zainstalować aktualizację ponownie w celu uzyskania identycznych zabezpieczeń, a także rozwiązania problemu z drukowaniem. Zobacz biuletyn zabezpieczeń firmy Microsoft MS09-029.
-   Wer. 7.0 (12 stycznia 2010 r.): Wprowadzono zmiany, aby w biuletynie MS09-035 dodać system Windows Embedded CE 6.0 do listy programów, których dotyczy problem. Aktualizacja systemu Windows Embedded CE 6.0 (KB974616) jest aktualizacją zbiorczą dostępną tylko w witrynie Microsoft Download Center. Użytkownicy platformy Windows Embedded CE 6.0 powinni rozważyć zastosowanie tej aktualizacji zbiorczej.
-   Wer. 8.0 (9 marca 2010 r.): Zaktualizowano w celu dodania programu Microsoft Virtual Server 2005 do listy programów, których dotyczy problem, dla biuletynu MS09-033.

*Built at 2014-04-18T01:50:00Z-07:00*
