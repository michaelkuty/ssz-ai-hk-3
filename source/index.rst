
Otázky na státnice AI3 ver. 2014!
==============================================

PROG
===========


1. :doc:`Logický program - struktura, základní pojmy, datová struktura seznam, práce s databází Prologu. Hlavní odlišnosti oproti procedurálnímu programování, možnosti použití neprocedurálního programovacího jazyka. <prog/1>`

2. :doc:`Databáze, databázový systém. Hlavní funkce DBS. Historický vývoj DBS. Modely dat. Relační algebra: projekce, selekce, spojení. SQL. <prog/2>`

3. :doc:`Konceptuální modelování. E-R model a jeho grafické znázornění. Relační model. Typy vztahů mezi entitami a jejich reprezentace v relačním modelu. Vlastnosti relační tabulky. Normální formy relačního schématu. <prog/3>`

4. :doc:`Ontologické inženýrství: pojem ontologie v kontextu informatiky, základní stavební prvky ontologií, typy ontologií, jazyky ontologického modelování, návrhové vzory, normalizace ontologie. Odvozování nad ontologií (kontrola konzistence, klasifikace), nástroje, použití ontologií.<prog/4>`

5. :doc:`Sémantický web: technologie sémantického webu, metadata, RDF, RDFS, OWL, dotazování se na sémantický web (význam, jazyky), sémantický web a odvozování (význam, jazyky), aplikace sémantického webu. <prog/5>`

6. :doc:`Námětové mapy: standard Topic Maps a jeho součásti, základní stavební prvky námětové mapy, postup tvorby námětové mapy, implementace námětových map (prostředí, syntaxe), dotazování se na námětové mapy, odvozování s námětovými mapami, aplikace námětových map.<prog/6>`

7. :doc:`Objektové modelování a programování - základní pojmy, podstata, využití. Softwarový proces. UML. Událostmi řízené programování. Architektura MVC.<prog/7>`

8. :doc:`Práce s kolekcemi – typy kolekcí, příklady použití, algoritmy pracující nad kolekcemi (řazení, vyhledávání), základní principy implementace ve zvoleném programovacím jazyce.<prog/8>`

9. :doc:`Problematika perzistentního (trvalého) ukládání dat ve vybraném programovacím jazyce.<prog/9>`

10. :doc:`Webové aplikace – principy, nástroje. Vícevrstvé aplikace. Zabezpečení aplikace.<prog/10>`

11. :doc:`Základní algoritmy a principy počítačové grafiky  – metody vizualizace, určení viditelnosti a osvětlení, reprezentace grafické informace, OPENGL.<prog/11>`

12. :doc:`Základy zpracování obrazu a počítačového rozpoznávání – metody snímání, předzpracování, segmentace a klasifikace obrazu, formáty pro ukládání rastrového obrazu, komprese, barva a barevné modely.<prog/12>`

13. :doc:`Algoritmy pracující s grafy. Prohledávání grafů do hloubky a do šířky, využití prohledávání grafů v dalších úlohách. <prog/13>`


TECH
===========

1. :doc:`Principy počítačů (historický vývoj, předpoklady fungování, binární logika, modulace signálu).<tech/1>`
2. :doc:`Architektura počítače (von Neumannovo a Harwardské schéma, Flynnova taxonomie, základní deska, procesor, mikroarchitektura procesoru, paměti, sběrnice, řadič, přídavné karty, ovladače).<tech/2>`
3. :doc:`Paměťový systém počítače a ukládání dat (typy, principy fungování, frekvence, normy, logická a fyzická struktura disku, RAM, ROM, Cache, HDD, CD, DVD, FLASH…)<tech/3>`

4. :doc:`Architektura periferních zařízení (rozdělení, principy, funkce, typy, rozhraní, příklady)<tech/4>`
5. :doc:`Servery a pracovní stanice (rozdíly, kritéria výběru, role serverů, serverové technologie, zálohování dat včetně RAID)<tech/5>`
6. :doc:`Komunikační prostředky (principy komunikace, modulace signálu, rozdělení a porovnání, média, mobilní technologie)<tech/6>`
7. :doc:`ETHERNET (principy fungování, vývoj a topologie, přístupová metoda, síťová karta, strukturovaná kabeláž)<tech/7>`
8. :doc:`RM ISO/OSI, TCP/IP (popis a srovnání, funkce zásadních protokolů, IP adresy)<tech/8>`
9. :doc:`Internet (organizační struktura, vývoj, RFC dokumenty, domény, technické předpoklady pro připojení, hrozby)<tech/9>`
10. :doc:`Směrování (základní principy, směrovací protokoly, směrovací algoritmy, směrovače)<tech/10>`
11. :doc:`Propojování a management sítí (přenosová média, technologie pro různé vrstvy, WIFI, VPN, systémy pro vzdálený přístup, řešení založená na SNMP)<tech/11>`
12. :doc:`Principy operačních systémů (základní rozdělení, druhy operačních systémů, procesy, správa procesů a systémových zdrojů, uživatelská rozhraní).<tech/12>`
13. :doc:`Souborové systémy a logická struktura dat (principy, porovnání, příklady).<tech/13>`
14. :doc:`Operační systémy Windows (principy MS DOS, MS Windows, architektura, verze, funkce, rozdíly).<tech/14>`
15. :doc:`Operační systémy Unix, Linux, BSD, MacOS (základní myšlenky, výhody a nevýhody, open-source, vznik a vývoj, licence, distribuce, základy ovládání - shell, rozdíly, historie a vývoj)<tech/15>`
16. :doc:`Serverové operační systémy (specifika serverových operačních systémů, rozdíly mezi OS pro osobní počítač a pro server, serverové služby, správa uživatelů)<tech/16>`


Syntaxe - **reStructuredText**
------

* http://sphinx-doc.org/rest.html
* SublimeText plugin https://sublime.wbond.net/packages/RestructuredText%20Improved
* SublimeText plugin https://github.com/mgaitan/sublime-rst-completion
* dostupné formáty pro export http://sphinx-doc.org/builders.html
* Auto build https://pypi.python.org/pypi/sphinx-autobuild
	* pip install watchdog  
	* watchmedo shell-command --patterns=*.rst --recursive --command='sphinxuild -b html ./source/ ./' 

Jak přispět ?
------

1. Fork na githubu
2. Editace v source/..
3. Build sphinx-build -b html ./source/ ./
4. Pull request

Většina textů převzata a upravena z http://ai-fim-uhk.wikispaces.com/

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

