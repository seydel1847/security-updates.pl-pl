---
TOCTitle: 'MS07-NOV'
Title: Microsoft Security Bulletin Summary for listopad 2007
ms:assetid: 'ms07-nov'
ms:contentKeyID: 61233081
ms:mtpsurl: 'https://technet.microsoft.com/pl-PL/library/ms07-nov(v=Security.10)'
---


Microsoft Security Bulletin Summary for listopad 2007
=====================================================

Opublikowano: 13 listopada 2007

**Wersja:** 1.0

Niniejsze podsumowanie biuletynów zabezpieczeń zawiera spis biuletynów za listopad 2007 r.

Z chwilą opublikowania biuletynów za listopad 2007 r. niniejsze podsumowanie biuletynów zastępuje powiadomienie o biuletynach zabezpieczeń wydane 8 listopada 2007 r. Aby uzyskać więcej informacji na temat usługi powiadamiania o biuletynach, zobacz [Powiadomienia o biuletynach zabezpieczeń firmy Microsoft (j.ang.)](http://technet.microsoft.com/security/bulletin/advance).

Aby dowiedzieć się, jak otrzymywać automatyczne powiadomienia o publikacji biuletynów zabezpieczeń firmy Microsoft, odwiedź stronę [Microsoft Technical Security Notifications (j.ang.)](http://go.microsoft.com/fwlink/?linkid=21163).

14 listopada 2007 r. o godz. 11:00 czasu Pacyfiku (godz. 20:00 czasu środkowoeuropejskiego) firma Microsoft udostępni emisję internetową, w której znajdą się odpowiedzi na pytania klientów dotyczące tych biuletynów (USA i Kanada). [Zarejestruj się, aby zobaczyć emisję internetową dotyczącą biuletynów zabezpieczeń za listopad (j.ang.)](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us). Po tym dniu emisja internetowa będzie dostępna na żądanie. Aby uzyskać więcej informacji, zobacz [podsumowania biuletynów zabezpieczeń](http://technet.microsoft.com/security/bulletin/summary) i [emisje internetowe firmy Microsoft (j.ang.)](http://technet.microsoft.com/security/bulletin/summary).

Firma Microsoft udostępnia także informacje, dzięki którym klienci mogą ustalić priorytety dla aktualizacji zabezpieczeń w związku z niezwiązanymi z zabezpieczeniami aktualizacjami o wysokim priorytecie, które publikowane są w tym samym dniu, co comiesięczne aktualizacje zabezpieczeń. Zapoznaj się z sekcją **Inne informacje**.

### Informacje o biuletynie

#### Streszczenia

W bieżącym miesiącu opublikowano następujące biuletyny (w kolejności wskaźnika ważności):

Krytyczny (1)
-------------


| Identyfikator biuletynu           | Biuletyn zabezpieczeń firmy Microsoft MS07-061                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Tytuł biuletynu**               | [**Luka w zabezpieczeniach mechanizmu obsługi identyfikatorów URI w systemie Windows potencjalnie umożliwia zdalne wykonanie kodu (943460)**](http://technet.microsoft.com/security/bulletin/ms07-061)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Streszczenie**                  | Ta aktualizacja ma na celu usunięcie luki w zabezpieczeniach zgłoszonej przez organizację publiczną. W sposobie, w jaki powłoka Windows obsługuje przekazywane do niej specjalnie spreparowane identyfikatory URI, występuje luka. Gdyby powłoka systemu Windows niewystarczająco sprawdzała poprawność identyfikatorów URI, osoba atakująca mogłaby wykorzystać lukę w zabezpieczeniach i uruchomić dowolny kod. Firma Microsoft znalazła sposoby na wykorzystanie tej luki tylko w systemach korzystających z programu Internet Explorer 7. Luka ta istnieje jednak w pliku systemu Windows, shell32.dll, który znajduje się we wszystkich obsługiwanych wersjach systemów Windows XP i Windows Server 2003. |
| **Maksymalny wskaźnik ważności:** | [Krytyczny](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Wpływ luki**                    | Zdalne wykonanie kodu                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Wykrywanie**                    | Narzędzie Microsoft Baseline Security Analyzer może wykryć, czy komputer wymaga zainstalowania tej aktualizacji. Aktualizacja będzie wymagać ponownego uruchomienia komputera.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Podlegające oprogramowanie**    | **Windows.** Więcej informacji można znaleźć w częściach: Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

Ważny (1)
---------


| Identyfikator biuletynu           | Biuletyn zabezpieczeń firmy Microsoft MS07-062                                                                                                                                                                                                                                                                                         |
|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Tytuł biuletynu**               | [**Luka w zabezpieczeniach DNS może pozwolić na fałszowanie (941672)**](http://technet.microsoft.com/security/bulletin/ms07-062)                                                                                                                                                                                                       |
| **Streszczenie**                  | Ta ważna aktualizacja zabezpieczeń usuwa lukę w zabezpieczeniach zgłoszoną przez użytkowników. Luka ta występuje w serwerach DNS systemu Windows i może pozwolić osobie atakującej na wysyłanie specjalnie spreparowanych odpowiedzi na żądania DNS i fałszowanie lub przekierowywanie ruchu internetowego z uprawnionych lokalizacji. |
| **Maksymalny wskaźnik ważności:** | [Ważny](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                         |
| **Wpływ luki**                    | Fałszowanie                                                                                                                                                                                                                                                                                                                            |
| **Wykrywanie**                    | Narzędzie Microsoft Baseline Security Analyzer może wykryć, czy komputer wymaga zainstalowania tej aktualizacji. Z wyjątkiem niektórych sytuacji aktualizacja będzie wymagać ponownego uruchomienia komputera.                                                                                                                         |
| **Podlegające oprogramowanie**    | **Windows.** Więcej informacji można znaleźć w częściach: Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki.                                                                                                                                                                                           |

Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki
---------------------------------------------------------------------------------


**How do I use this table?**

Tabela ta pozwala odczytać informacje o aktualizacjach zabezpieczeń, których zainstalowanie może być konieczne. Należy przejrzeć informacje dla każdego wymienionego programu lub składnika oprogramowania w celu sprawdzenia, czy są wymagane aktualizacje zabezpieczeń. Dla każdego programu lub składnika oprogramowania wymienionego na liście podany jest wpływ luki oraz hiperłącze do dostępnej aktualizacji oprogramowania.

**Note** You may have to install several security updates for a single vulnerability. Przejrzyj całą kolumnę dla każdego wymienionego identyfikatora biuletynu, aby sprawdzić, jakie aktualizacje musisz zainstalować, w oparciu o programy bądź składniki zainstalowane w systemie.

**Programy, których dotyczy problem, i lokalizacje, z których można pobrać poprawki**

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
Szczegóły
</th>
<th style="border:1px solid black;" >
Szczegóły
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Identyfikator biuletynu**
</td>
<td style="border:1px solid black;">
[**MS07-061**](http://technet.microsoft.com/security/bulletin/ms07-061)
</td>
<td style="border:1px solid black;">
[**MS07-062**](http://technet.microsoft.com/security/bulletin/ms07-062)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Maksymalny wskaźnik ważności:**
</td>
<td style="border:1px solid black;">
[**Krytyczny**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**Ważny**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="3">
System operacyjny Windows
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Server z dodatkiem Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Ważny](http://www.microsoft.com/downloads/details.aspx?familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4&displaylang=pl)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows XP z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Krytyczny](http://www.microsoft.com/downloads/details.aspx?familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104&displaylang=pl)
</td>
<td style="border:1px solid black;">

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
[Krytyczny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Krytyczny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f)
</td>
<td style="border:1px solid black;">

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem Service Pack 1
</td>
<td style="border:1px solid black;">
[Krytyczny](http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b&displaylang=pl)
</td>
<td style="border:1px solid black;">
[Ważny](http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d&displaylang=pl)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Krytyczny](http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b&displaylang=pl)
</td>
<td style="border:1px solid black;">
[Ważny](http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d&displaylang=pl)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
[Krytyczny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Ważny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition z dodatkiem Service Pack 2
</td>
<td style="border:1px solid black;">
[Krytyczny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326)
</td>
<td style="border:1px solid black;">
[Ważny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP1 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Krytyczny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Ważny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 z dodatkiem SP2 dla systemów z procesorem Itanium
</td>
<td style="border:1px solid black;">
[Krytyczny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5)
</td>
<td style="border:1px solid black;">
[Ważny (j.ang.)](http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6)
</td>
</tr>
</table>
 

Narzędzia wykrywania i wdrażania oraz wskazówki
-----------------------------------------------


**Centrum zabezpieczeń**

Zarządzanie oprogramowaniem oraz aktualizacjami zabezpieczeń, które należy zainstalować na serwerach oraz komputerach stacjonarnych i przenośnych w organizacji. Więcej informacji można znaleźć w [Centrum TechNet Update Management Center (j.ang.)](http://go.microsoft.com/fwlink/?linkid=69903). Witryna [TechNet Security Center](http://www.microsoft.com/poland/technet/security/) zawiera dodatkowe informacje na temat zabezpieczeń w produktach firmy Microsoft. Użytkownicy mogą także uzyskać dostęp do tych informacji w witrynie [Bezpieczeństwo w domu](http://www.microsoft.com/poland/athome/security/default.mspx), klikając łącze „Najnowsze aktualizacje zabezpieczeń”.

Aktualizacje zabezpieczeń dostępne są w witrynach [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) i [Office Update](http://office.microsoft.com/pl-pl/officeupdate/default.aspx). Aktualizacje zabezpieczeń są także dostępne w witrynie [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?freetext=poprawka+zabezpiecze%c5%84&productid=&displaylang=pl). Najłatwiej je znaleźć, przeprowadzając wyszukiwanie wyrażenia „poprawka zabezpieczeń”.

Aktualizacje zabezpieczeń można także pobierać z [Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=96155). Wykaz usługi Microsoft Update zawiera katalog zawartości z możliwością przeszukiwania, który udostępniany jest poprzez usługi Windows Update i Microsoft Update i obejmuje aktualizacje zabezpieczeń, sterowniki i dodatki Service Pack. Wyszukiwanie przy użyciu numeru biuletynu zabezpieczeń (np. „MS07-036”) pozwala dodać do koszyka wszystkie odpowiednie aktualizacje (w tym różne wersje językowe aktualizacji) i pobrać pliki do wybranego folderu. Więcej informacji na temat Wykazu usługi Microsoft Update można znaleźć w [Często zadawanych pytaniach dotyczących Wykazu usługi Microsoft Update](http://go.microsoft.com/fwlink/?linkid=97900).

**Porady dotyczące wykrywania i wdrażania**

Firma Microsoft opublikowała porady dotyczące wykrywania i wdrażania, odnoszące się do aktualizacji zabezpieczeń udostępnionych w tym miesiącu. Porady te będą również pomocne dla informatyków, wyjaśniając jak mogą oni wdrażać aktualizacje za pomocą różnych narzędzi, takich jak Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool i Enterprise Update Scan Tool (EST). Więcej informacji na ten temat można znaleźć w [artykule 910723 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/910723).

**Narzędzie Microsoft Baseline Security Analyzer (MBSA)**

Narzędzie Microsoft Baseline Security Analyzer umożliwia administratorom skanowanie lokalnych i zdalnych systemów w poszukiwaniu brakujących aktualizacji zabezpieczeń oraz typowych błędów konfiguracji zabezpieczeń. Więcej informacji na temat narzędzia MBSA można znaleźć w witrynie sieci Web[Microsoft Baseline Security Analyzer](http://www.microsoft.com/poland/technet/security/tools/mbsa.mspx).

**Uwaga** Po 9 października 2007 r. używany przez narzędzie MBSA 1.2.1 plik MSSecure.XML nie będzie już aktualizowany. Po upływie tej daty do pliku MSSecure.XML używanego przez narzędzie MBSA 1.2.1 nie będą dodawane nowe aktualizacje zabezpieczeń. Nie będą również publikowane nowe wersje narzędzia Enterprise Scan Tool. Nie dotyczy to narzędzi Security Update Inventory Tool (SUIT) ani Extended Security Update Inventory Tool (ESUIT) dla programów SMS 2.0 i SMS 2003. Więcej informacji można znaleźć w witrynie sieci Web [Microsoft Baseline Security Analyzer](http://www.microsoft.com/poland/technet/security/tools/mbsa.mspx).

**Windows Server Update Services**

Korzystając z programu Windows Server Update Services (WSUS), administratorzy mogą szybko i niezawodnie wdrożyć najnowsze aktualizacje krytyczne i aktualizacje zabezpieczeń przeznaczonych dla systemu operacyjnego Windows 2000 i nowszych, pakietu Office XP i nowszych, programu Exchange Server 2003 oraz SQL Server 2000 w systemie operacyjnym Windows 2000 i nowszych.

Więcej informacji na temat sposobu wdrażania tej aktualizacji zabezpieczeń za pomocą programu Windows Server Update Services można znaleźć w [witrynie sieci Web programu Windows Server Update Services (j.ang.)](http://go.microsoft.com/fwlink/?linkid=50120).

**Program Systems Management Server**

Program Systems Management Server (SMS) jest przeznaczonym dla przedsiębiorstw i w znacznym stopniu konfigurowalnym rozwiązaniem służącym do zarządzania aktualizacjami. Program SMS umożliwia administratorom znalezienie komputerów z systemem Windows, na których należy zainstalować aktualizację zabezpieczeń, a także przeprowadzić kontrolowane wdrożenie tych aktualizacji w całym przedsiębiorstwie, w minimalnym stopniu zakłócając przy tym pracę użytkowników końcowych. Więcej informacji na temat możliwości wykorzystania przez administratorów programu SMS 2003 do wdrażania aktualizacji zabezpieczeń można znaleźć [w witrynie sieci Web zarządzania poprawkami zabezpieczeń programu SMS 2003 (j.ang.)](http://go.microsoft.com/fwlink/?linkid=22939). Użytkownicy programu SMS 2.0 mogą także skorzystać z dodatku [Software Updates Services Feature Pack (j.ang.)](http://go.microsoft.com/fwlink/?linkid=33340) ułatwiającego wdrożenie aktualizacji zabezpieczeń. Więcej informacji na temat programu SMS można znaleźć w witrynie sieci Web [Microsoft Systems Management Server (j.ang.)](http://go.microsoft.com/fwlink/?linkid=21158).

**Uwaga** Program SMS zapewnia obsługę rozwiązań zawartych w biuletynach zabezpieczeń dzięki narzędziom Microsoft Baseline Security Analyzer oraz Microsoft Office Detection Tool. Narzędzia te mogą nie wykrywać wszystkich aktualizacji oprogramowania. W takich przypadkach administratorzy mogą wykorzystywać dostępne w programie SMS funkcje zarządzania zasobami do przyporządkowania poszczególnych aktualizacji określonym systemom. Aby uzyskać więcej informacji dotyczących tej procedury, zobacz [Wdrażanie aktualizacji oprogramowania za pomocą funkcji Software Distribution programu SMS (j.ang.)](http://go.microsoft.com/fwlink/?linkid=33341). Niektóre aktualizacje oprogramowania wymagają od użytkownika uprawnień administratora po ponownym uruchomieniu systemu. Do zainstalowania tych aktualizacji administratorzy mogą użyć narzędzia Elevated Rights Deployment Tool (dostępnego w dodatkach [SMS 2003 Administration Feature Pack (j.ang.)](http://go.microsoft.com/fwlink/?linkid=33387) oraz [SMS 2.0 Administration Feature Pack (j.ang.)](http://go.microsoft.com/fwlink/?linkid=21161).

### Inne informacje:

#### Narzędzie Microsoft Windows do usuwania złośliwego oprogramowania

Firma Microsoft opublikowała zaktualizowaną wersję narzędzia Microsoft Windows Malicious Software Removal Tool, która dostępna jest w witrynach sieci Web Windows Update i Microsoft Update, poprzez usługi Windows Server Update Services i w witrynie Microsoft Download Center.

#### Aktualizacje o wysokim priorytecie niezwiązane z zabezpieczeniami, dostępne w witrynach MU, WU oraz usługach WSUS

W tym miesiącu:

-   Firma Microsoft opublikowała trzy **niezwiązane z zabezpieczeniami** aktualizacje o wysokim priorytecie, które dostępne są w witrynie Microsoft Update (MU) i za pośrednictwem usługi Windows Server Update Services (WSUS).
-   Firma Microsoft nie opublikowała żadnych **niezwiązanych z zabezpieczeniami** aktualizacji o wysokim priorytecie dla systemu Windows, które byłyby udostępnione w witrynie Windows Update (WU).

Należy pamiętać, że informacje te dotyczą **wyłącznie** aktualizacji o wysokim priorytecie **niezwiązanych z zabezpieczeniami**, które dostępne są w witrynach Microsoft Update i Windows Update oraz poprzez usługi Windows Server Update Services i zostały opublikowane jednocześnie z podsumowaniem biuletynów zabezpieczeń. Informacje na temat aktualizacji **niezwiązanych z zabezpieczeniami**, które zostały opublikowane w innych dniach, **nie** są podawane.

#### Strategie i społeczność związane z zabezpieczeniami

**Strategie zarządzania aktualizacjami**

Na stronie [Security Guidance for Patch Management (j.ang.)](http://go.microsoft.com/fwlink/?linkid=21168) (Wskazówki z zakresu bezpieczeństwa dotyczące zarządzania poprawkami) znajdują się dodatkowe informacje o zalecanych przez firmę Microsoft najlepszych sposobach stosowania aktualizacji zabezpieczeń.

**Uzyskiwanie innych aktualizacji zabezpieczeń**

Aktualizacje dotyczące innych problemów związanych z zabezpieczeniami można uzyskać w następujących lokalizacjach:

-   Aktualizacje zabezpieczeń są dostępne w witrynie [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?freetext=poprawka+zabezpiecze%c5%84&productid=&displaylang=pl). Najłatwiej je znaleźć, wyszukując wyrażenie „aktualizacja zabezpieczeń”.
-   Aktualizacje dla poszczególnych platform są dostępne w [witrynie sieci Web Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   Aktualizacje zabezpieczeń dostępne w tym miesiącu w witrynie Windows Update można otrzymać w witrynie Microsoft Download Center w postaci plików obrazu dysku CD zawierającego zabezpieczenia i aktualizacje krytyczne. Więcej informacji na ten temat można znaleźć w [artykule 913086 bazy wiedzy Microsoft Knowledge Base](http://support.microsoft.com/kb/913086).

**Społeczność IT Pro Security Community**

Dowiedz się, jak poprawić bezpieczeństwo i zoptymalizować infrastrukturę informatyczną oraz weź udział w dyskusjach dotyczących zabezpieczeń wraz z innymi specjalistami branży IT, odwiedzając witrynę sieci Web społeczności [IT Pro Security Community (j.ang.)](http://go.microsoft.com/fwlink/?linkid=21164).

#### Podziękowania

Firma Microsoft [dziękuje (j.ang.)](http://go.microsoft.com/fwlink/?linkid=21127) wymienionym poniżej organizacjom i osobom za współpracę w dziedzinie ochrony klientów:

-   Jesperowi Johanssonowi za współpracę z firmą Microsoft przy rozwiązywaniu problemu opisanego w biuletynie MS07-61.
-   Carstenowi H. Eiram z firmy [Secunia](http://corporate.secunia.com/) za współpracę z firmą Microsoft przy rozwiązywaniu problemu opisanego w biuletynie MS07-61
-   Aviv Raff z firmy [Finjan](http://www.finjan.com/) za współpracę z firmą Microsoft przy rozwiązywaniu problemu opisanego w biuletynie MS07-61
-   Petko Petkowowi z firmy [GNUCITIZEN](http://www.gnucitizen.org/) za współpracę z firmą Microsoft przy rozwiązywaniu problemu opisanego w biuletynie MS07-61
-   Alli Berzroutchko z firmy [Scanit](http://www.scanit.be/) za zgłoszenie problemu opisanego w biuletynie MS07-062
-   Amitowi Kleinowi z firmy [Trusteer](http://www.trusteer.com/) za zgłoszenie problemu opisanego w biuletynie MS07-062

#### Pomoc techniczna

-   Wymienione oprogramowanie zostało przetestowane w celu ustalenia, których wersji dotyczy problem. Dla pozostałych wersji upłynął okres pomocy technicznej. Aby zapoznać się z zasadami cyklu pomocy technicznej dotyczącymi używanej wersji oprogramowania, odwiedź [witrynę zasad cyklu pomocy technicznej firmy Microsoft](http://go.microsoft.com/fwlink/?linkid=21742).
-   Klienci mogą uzyskać pomoc techniczną w [Biurze Obsługi Klienta Microsoft](http://support.microsoft.com/contactus/?ws=support) pod numerem 0 801 802 000 (Opłata według stawek Twojego operatora) lub (0-22) 594 19 99 w godzinach od 9:00 do 17:00, od poniedziałku do piątku. Połączenia z działem pomocy technicznej związane z aktualizacjami zabezpieczeń są bezpłatne.
-   Klienci międzynarodowi mogą uzyskać pomoc w lokalnych przedstawicielstwach firmy Microsoft. Pomoc techniczna związana z aktualizacjami zabezpieczeń jest bezpłatna. Informacje o sposobie kontaktowania się z pomocą techniczną firmy Microsoft są dostępne w [międzynarodowej witrynie sieci Web pomocy i obsługi technicznej](http://go.microsoft.com/fwlink/?linkid=21155).

#### Zrzeczenie odpowiedzialności

Informacje w bazie wiedzy Microsoft Knowledge Base są dostarczane „tak jak są” bez jakiejkolwiek gwarancji. Firma Microsoft odrzuca wszelkie gwarancje, wyraźne i dorozumiane, w tym gwarancje dotyczące wartości handlowej i przydatności do określonego celu. Firma Microsoft Corporation ani jej dostawcy w żadnym wypadku nie ponoszą odpowiedzialności za jakiekolwiek szkody, w tym bezpośrednie, pośrednie, przypadkowe, wynikowe, utratę zysków handlowych lub szkody specjalne, nawet jeżeli firmę Microsoft Corporation lub jej dostawców powiadomiono o możliwości zaistnienia takich szkód. W niektórych stanach wyłączenie lub ograniczenie odpowiedzialności za straty wynikowe lub przypadkowe, a więc i powyższe ograniczenia, nie mają zastosowania.

#### Wersje

-   Wersja 1.0 (13 listopada 2007 r.): Opublikowane podsumowanie biuletynów zabezpieczeń.

*Built at 2014-04-18T01:50:00Z-07:00*
