\chapter{TECH}

\section{Principy počítačů (historický vývoj, předpoklady fungování, binární logika, modulace signálu).}

\section{2.       Architektura počítače (von Neumannovo a Harwardské schéma, Flynnova taxonomie, základní deska, procesor, mikroarchitektura procesoru, paměti, sběrnice, řadič, přídavné karty, ovladače).
}

\section{Paměťový systém počítače a ukládání dat (typy, principy fungování, frekvence, normy, logická a fyzická struktura disku, RAM, ROM, Cache, HDD, CD, DVD, FLASH…)}

\section{Architektura periferních zařízení (rozdělení, principy, funkce, typy, rozhraní, příklady)}

\section{Servery a pracovní stanice (rozdíly, kritéria výběru, role serverů, serverové technologie, zálohování dat včetně RAID)}

\section{Komunikační prostředky (principy komunikace, modulace signálu, rozdělení a porovnání, média, mobilní technologie)}

\section{ETHERNET (principy fungování, vývoj a topologie, přístupová metoda, síťová karta, strukturovaná kabeláž)}

\section{RM ISO/OSI, TCP/IP (popis a srovnání, funkce zásadních protokolů, IP adresy)}

\section{Internet (organizační struktura, vývoj, RFC dokumenty, domény, technické předpoklady pro připojení, hrozby)}

\subsection{RFC}

Specifikace RFC protokolu TCP/IP
Standardy platné pro protokol TCP/IP jsou postupně zveřejňovány v sadě dokumentů nazývaných RFC (Requests for Comments). Specifikace RFC tvoří stále doplňovaný soubor zpráv, návrhů protokolů a standardů, který popisuje vnitřní strukturu a funkci protokolu TCP/IP a sítě Internet.
Ačkoli jsou standardy protokolu TCP/IP vždy publikovány v podobě specifikací RFC, nejsou definice standardů obsaženy ve všech těchto specifikacích. Specifikace RFC jsou dílem jednotlivců, kteří na základě vlastního uvážení vytvářejí koncepty nových protokolů a specifikací a dávají je k dispozici sdružení IETF (Internet Engineering Task Force) a dalším pracovním skupinám. Odeslaný koncept nejprve okomentuje technik, skupina odborníků nebo redaktor specifikací RFC a potom je konceptu přiřazen status.
Pokud je koncept v této úvodní fázi schválen, je na určitou dobu zpřístupněn v síti Internet širší veřejnosti, která se k němu může dále vyjadřovat. Zároveň je mu přiřazeno číslo specifikace RFC. Toto číslo se již nemění.
Pokud dojde ke změnám navrhovaného standardu, je upravený nebo aktualizovaný koncept distribuován pod novým číslem specifikace RFC (vždy vyšším, než bylo číslo původního konceptu). Podle čísla specifikace RFC lze tedy snadno určit, která ze specifikací je aktuálnější.

\section{Směrování (základní principy, směrovací protokoly, směrovací algoritmy, směrovače)}

\section{Propojování a management sítí (přenosová média, technologie pro různé vrstvy, WIFI, VPN, systémy pro vzdálený přístup, řešení založená na SNMP)}

\subsection{SNMP}

Simple Network Management Protocol (SNMP) je součástí sady internetových protokolů. Slouží potřebám správy sítí. Umožňuje průběžný sběr nejrůznějších dat pro potřeby správy sítě, a jejich následné vyhodnocování. Na tomto protokolu je dnes založena většina prostředků a nástrojů pro správu sítě.

Má tři verze: druhá obsahuje navíc autentizaci a třetí šifrování. Nejvíce zařízení podporuje druhou verzi.

Rozlišuje se mezi stranou monitorovanou (hlídaný systém) a monitorovací (sběrna dat). Tyto strany mohou běžet buď odděleně na různých fyzických strojích, nebo v rámci jednoho stroje. Na monitorované straně je spuštěn agent a na straně monitorovací manager. Na straně monitorované jsou operativně shromažďovány informace o stavu systému (zařízení). Manager vznáší požadavky agentovi, zpravidla na zaslání požadovaných informací (zpráv). Agent zajišťuje realizaci reakcí na požadavky managera. Získaný obsah zpráv se na straně monitorovací může dále různým způsobem zpracovávat (tabulky, grafy, …). Komunikace mezi agentem a managerem se označuje jako SNMP operace.

Na straně monitorované může existovat možnost takové konfigurace, kdy agent zašle managerovi informace (SNMP MESSAGE) automaticky bez jeho požadavku. K tomu dojde zpravidla potom, kdy byla splněna předem definovaná podmínka (výpadek, kolize, dosažení hraniční hodnoty, …), agent nečeká na odpověď. Takové konfiguraci agenta se říká SNMP TRAP (tzv. past na události).

\section{Principy operačních systémů (základní rozdělení, druhy operačních systémů, procesy, správa procesů a systémových zdrojů, uživatelská rozhraní).}

\section{Souborové systémy a logická struktura dat (principy, porovnání, příklady).}

\section{Operační systémy Windows (principy MS DOS, MS Windows, architektura, verze, funkce, rozdíly).}

\section{ Operační systémy Unix, Linux, BSD, MacOS (základní myšlenky, výhody a nevýhody, open-source, vznik a vývoj, licence, distribuce, základy ovládání - shell, rozdíly, historie a vývoj)}

\section{Serverové operační systémy (specifika serverových operačních systémů, rozdíly mezi OS pro osobní počítač a pro server, serverové služby, správa uživatelů)}
	