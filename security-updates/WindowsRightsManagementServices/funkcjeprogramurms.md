---
TOCTitle: Funkcje programu RMS
Title: Funkcje programu RMS
ms:assetid: '4a147e77-8df0-4b12-a3a0-8eb31f5b22dc'
ms:contentKeyID: 18123252
ms:mtpsurl: 'https://technet.microsoft.com/pl-pl/library/Cc720265(v=WS.10)'
---

Funkcje programu RMS
====================

Program RMS jest zunifikowanym rozwiązaniem, którego można używać do ochrony zawartości. W programie tym są również dostępne narzędzia służące do instalacji i konfiguracji serwerów, klientów oraz kont użytkowników dla zaufanych jednostek w systemie RM. Ta konfiguracja obejmuje następujące funkcje:

-   **Rejestracja serwera**. Organizacja konfiguruje serwer głównej certyfikacji w każdym lesie, który będzie częścią systemu RMS, poprzez rejestrację każdego serwera tego typu w usłudze rejestracji firmy Microsoft. Proces rejestracji może przebiegać automatycznie, jeśli serwer jest podłączony do Internetu. Jeśli serwer nie jest podłączony do Internetu, można wykorzystać proces rejestracji w trybie offline i zarejestrować serwer ręcznie, przesyłając żądanie rejestracji do firmy Microsoft z innego komputera, który jest podłączony do Internetu. Po zarejestrowaniu serwerowi jest przypisywany główny certyfikat licencjodawcy serwera, dzięki któremu serwer ten jest rozpoznawany w hierarchii zaufania programu RMS w organizacji. Następnie organizacja konfiguruje pozostałe serwery, które będą stanowić część systemu, poprzez dołączenie ich do klastra głównej certyfikacji serwera w danym lesie lub poprzez podrejestrowanie co najmniej jednego serwera licencji na serwerze głównej certyfikacji. W ramach procesu rejestrowania serwera tworzone są certyfikaty umożliwiające serwerom wystawianie licencji, którym ufa program RMS. Aby uzyskać więcej informacji, zobacz „Rejestrowanie w programie RMS” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Instalacja oprogramowania klienckiego**. Organizacja musi zainstalować oprogramowanie klienckie RMS na wszystkich komputerach klienckich, które będą używane do tworzenia lub wykorzystywania informacji chronionych za pomocą programu RMS. Po zainstalowaniu oprogramowania należy włączyć komputer. Komputer włącza się po utworzeniu certyfikatu komputera dla zalogowanego użytkownika. Certyfikat komputera zawiera klucz publiczny komputera. Aktywacja jest procesem wewnętrznym wykonywanym na komputerze i widocznym dla użytkownika.
-   **Certyfikacja użytkownika**. Organizacje muszą określić użytkowników, którzy są zaufanymi jednostkami w danej instalacji programu RMS. W tym celu program RMS wystawia certyfikaty kont praw dostępu, które kojarzą konta użytkowników z odpowiednimi parami kluczy chronionymi na komputerze użytkownika. Certyfikaty te umożliwiają użytkownikom publikowanie i używanie zawartości chronionej technologią RMS. Każdy certyfikat zawiera klucz publiczny, który jest wykorzystywany do licencjonowania informacji przeznaczonych do wykorzystania przez użytkownika. Aby uzyskać więcej informacji, zobacz „Certyfikacja kont programu RMS” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Rejestracja klienta**. Jeśli komputery klienckie będą używane do publikowania zawartości chronionej za pomocą programu RMS, gdy nie będą podłączone do sieci firmowej, wymagana jest rejestracja klienta. Komputery klienckie zarejestrowane w programie RMS otrzymują certyfikaty licencjodawcy klienta, które umożliwiają użytkownikom publikowanie zawartości chronionej za pomocą programu RMS, gdy komputery nie są podłączone do sieci firmowej. Aby uzyskać więcej informacji, zobacz „Rejestrowanie klienta w programie RMS” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Definicje standardowych warunków i praw użytkowania**. Do określania warunków i praw użytkowania program RMS używa nazewnictwa XML w postaci języka eXtensible rights Markup Language (XrML) w wersji 1.2.1. Aby uzyskać więcej informacji, zobacz „Język XrML” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Licencje publikacji, które definiują prawa i warunki użytkowania**. Autorzy mogą korzystać z prostych narzędzi w aplikacjach obsługujących RMS w celu przypisywania do zawartości określonych praw i warunków użytkowania zgodnych z zasadami biznesowymi organizacji. Prawa i warunki użytkowania są definiowane w licencjach publikacji, które określają autoryzowanych użytkowników mogących korzystać z zawartości oraz definiują zakres wykorzystania i zawartości. Aby uzyskać więcej informacji, zobacz „Publikowanie licencji” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Licencje użytkowania, które wymuszają prawa i warunki użytkowania**. Użytkownik, który otrzyma zawartość chronioną za pomocą programu RMS, musi zażądać licencji użytkowania i otrzymać ją z programu RMS, aby wyświetlić tę zawartość. Licencja użytkowania jest udzielana indywidualnemu użytkownikowi i określa prawa oraz warunki użytkowania podczas korzystania z zawartości. Aplikacje obsługujące technologię RMS mogą korzystać z funkcji technologii RMS do odczytywania, interpretowania i egzekwowania praw oraz warunków użytkowania. Aby uzyskać więcej informacji, zobacz „Licencje użytkowania” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Szyfrowanie i klucze**. Zawartość chroniona technologią RMS jest zawsze zaszyfrowana. Aplikacje obsługujące technologię RMS korzystają z kluczy symetrycznych do szyfrowania zawartości. Wszystkie serwery, komputery klienckie i konta użytkowników RMS z dodatkiem SP1 mają odpowiednią parę kluczy 1024-bitowych RSA. Program RMS używa tych par kluczy do szyfrowania klucza zawartości w licencjach publikacji i użytkowania oraz do podpisywania certyfikatów i licencji RMS w celu zapewnienia, że dostęp zostanie udzielony tylko użytkownikom i komputerom posiadającym odpowiednie uprawnienia. W szczególności klucz zawartości jest szyfrowany za pomocą klucza publicznego serwera w licencji publikacji, gdy użytkownik usiłuje użyć chronionej zawartości; klucz zawartości jest szyfrowany za pomocą klucza publicznego certyfikatu kont praw dostępu użytkownika w licencji użytkowania, dzięki czemu może określać i egzekwować prawa przypisywane do określonego konta użytkownika. Aby uzyskać więcej informacji, zobacz „Szyfrowanie i klucze w programie RMS” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Szablony zasad praw dostępu**. Administratorzy mogą tworzyć i rozpowszechniać oficjalne szablony zasad praw dostępu, które definiują prawa i warunki użytkowania dla wstępnie określonego zbioru użytkowników. Te szablony stanowią wygodny w zarządzaniu model, który może być wykorzystany przez organizacje do tworzenia hierarchii klasyfikacji dokumentów według ich zawartości. Na przykład organizacja może stworzyć szablony zasad praw dostępu dla swoich pracowników, które przypiszą osobne prawa i warunki użytkowania dla poufnej zawartości firmowej, zawartości zastrzeżonej i prywatnej. Aplikacje obsługujące system RMS mogą korzystać z tych szablonów, oferujących prosty i spójny sposób stosowania zasad użytkowania dla zawartości. Aby uzyskać więcej informacji, zobacz „Szablony zasad praw dostępu” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Listy odwołania**. Administratorzy mogą tworzyć i rozpowszechniać listy odwołania zawierające złamane podmioty, które zostaną unieważnione i usunięte z systemu RMS. Lista odwołania w organizacji może unieważniać certyfikaty dla określonych komputerów lub kont użytkowników. Na przykład certyfikat konta praw zwolnionego pracownika może zostać dodany do listy odwołania, tak aby nie mógł już być wykorzystywany do żadnych operacji, takich jak pozyskiwanie nowych licencji publikacji i użytkowania. Aby uzyskać więcej informacji, zobacz „Odwoływanie w programie RMS” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Zasady wykluczania**. Administratorzy mogą implementować zasady wykluczania po stronie serwerów w celu odmowy żądań licencji na podstawie identyfikatora użytkownika żądającego (poświadczenia logowania systemu Windows lub identyfikatora usługi Microsoft® .NET Passport), certyfikatu konta praw dostępu lub wersji skrytki. Zasady wykluczania powodują odmowę nowych żądań licencji zgłoszonych przez złamane podmioty, ale w odróżnieniu od odwołania, zasady wykluczania nie unieważniają obiektów głównych. Administratorzy mogą także wykluczać aplikacje potencjalnie szkodliwe lub o naruszonym bezpieczeństwie, skutkiem czego nie mogą one odszyfrowywać zawartości chronionej za pomocą programu RMS. Aby uzyskać więcej informacji, zobacz „Wykluczanie w programie RMS” w części „Informacje techniczne dotyczące programu RMS” w tym zestawie dokumentacji.
-   **Rejestrowanie**. Administratorzy mogą śledzić i przeprowadzać inspekcje wykorzystania zawartości chronionej technologią RMS w organizacji. Program RMS instaluje obsługę rejestrowania, tak aby organizacje posiadały zapis czynności programu RMS, w tym wystawionych lub nie licencji publikowania i użytkowania. Aby uzyskać więcej informacji, zobacz „Zarządzanie rejestrowaniem” w części „Obsługa serwerów programu RMS” w tym zestawie dokumentacji.
-   **Wszechstronne i elastyczne rozwiązanie**. Za pomocą pakietu SDK Windows Rights Management Services do programu RMS można dodać nowe funkcje.