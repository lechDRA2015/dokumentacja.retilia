

Portal - konfiguracja systemu
#################################
.. contents:: Spis treści
    :backlinks: none


Zakładka "Dane firmy"
******************************

Uszczegółowienie danych firmy
=====================================

Użytkownik logując się po raz pierwszy swoje prace powinien rozpocząć od wstępnej konfiguracji systemu. Podstawowym elementem konfiguracyjnym jest wprowadzenie do systemu informacji podstawowych o firmie, która wykorzystuje system MobilePos w swojej sprzedaży. W skład informacji jakie należy podać jest np. nazwa firmy, nip czy regon. Najważniejsze pola oznaczono gwiazdką, gdzie system nie umożliwi zapisania danych jeżeli pola będą puste. W każdym momencie jest możliwość modyfikacji już wprowadzonych danych (oprócz adresu e-mail). Jeżeli użytkownik postanowi zmienić adres e-mail w tym celu powienien napisać maila do administratora systemu pod adresem admin@retilia.pl

Zmiana hasła użytkownika na portalu
============================================

Pole “Nowe hasło” służy do zmiany hasła, które wymagane jest do autoryzacji użytkownika  podczas logowania do portalu internetowego MobilePos. W przypadku kiedy użytkownik zapomni hasła, nowe można wygenerować podając adres e-mail w kreatorze odzyskiwania hasła. Patrz punkt “Resetowanie hasła”.

Dane do autoryzacji na tabletach
============================================
Łącząc aplikację na tablecie z portalem należy podać NIP firmy oraz hasło. Hasło to jest ustanawiane na portalu w polu “hasło” sekcji “Dane do autoryzacji na tabletach”. Aplikacja w celu autoryzacji zawsze sprawdza poprawność hasła dlatego należy pamiętać o wypełnieniu tego pola jako jeden z pierwszych kroków konfiguracji systemu.


Zakładka "Sklepy"
*********************************
Zakładka “Sklepy” umożliwia definiowanie “sklepów”, czyli punktów w których pracuje system MobilePos. Zdefiniowanie “sklepu” wykorzystywane jest do m.in. analizy danych sprzedażowych. Pozycja sklepu pozwala wystawiać dokumenty np. fakturę a także zatowarować sklep utrzymując przy tym kontrolę stanów magazynowych.


Dodawanie sklepu
======================

W celu dodania nowego sklepu należy kliknąć przycisk “Nowy sklep” i wypełnić wszystkie wymagane pola. Każdy nowy sklep będzie występował jako kolejny rekord listy. W razie pomyłki lub zmian rekordy można edytować bądź usunąć.

Zakładka "Kontrahenci"
**********************************
System umożliwia wprowadzanie dwóch grup kooperantów będących stroną w transakcjach. 

Kontrahenci
=====================
Firmy reprezentowane przez osoby, od których zakupiono towar tzw. dostawcy. Portal umożliwia zdefiniowanie nowych kontrachentów w celu wykorzystywania np. do za towarowania sklepów.

Klienci
=====================
Osoby bądź firmy, którzy kupują od towar - tzw. odbiorcy. System wykorzystuje zapisane dane w celu automatyzacji pracy np. przy tworzeniu faktur.

Nowa pozycja listy
=======================
W celu dodania nowego kooperatna należy kliknąć przycisk “Nowy kontrachent” / “Nowy klient” i wypełnić wszystkie wymagane pola. Każdy nowy kooperant będzie występował jako kolejny rekord listy. W razie pomyłki lub zmian rekordy można edytować bądź usunąć.

Zakładka "Grupy towarowe"
*********************************
Grupy towarowe służą do organizacji produktów w listę kategorii. Pozwala to klientom sklepu na szybkie dotarcie do danego produktu, gdy wiedzą oni jakiego rodzaju typu produktów poszukują. W zakładce Grupy towarowe widoczna jest lista utworzonych wcześniej grup oraz dostępne są trzy przyciski “Dodaj grupę towarową”, “Edycja grupy towarowej”, “Usuń grupę towarową” za pomocą których dodajemy , edytujemy bądź usuwamy kolejne pozycje.

System pozwala wiązać towar z jedną grupą towarową. Istnieje w systemie predefiniowana grupa towarowa “Wszystkie” - do której należy cały asortyment.

Zakładka "Towary"
*****************************
Wybór zakładki prezentuje listę towarów dostępnych w sklepie. Lista podzielona jest na kolumny z najbardziej zanaczącymi polami opisu. Interfejs obsługujący listę towarów został wyposażony 
w wyszukiwarkę towaru po nazwie oraz po kodzie EAN. Można również wykorzystać skaner kodów kreskowych. Towary można sortować wybierając grupę towarową bądź wyświetlić towary dostępne lub usunięte z systemu.

Dodawanie i edycja towaru
==============================
Nowy towar na portalu zakłada się za pomocą przycisku “Nowy towar”
Do dodawania oraz edycji produktów wykorzystywany jest ten sam formularz w zakładce - “Towary”.  Po wybraniu opcji “Nowy towar” w pierwszej kolejności określamy EAN produktu. EAN jest to kod kreskowy, który znajduje się na opakowaniu towaru. Można wykorzystać w tym celu skaner kodów kreskowych. System MobilePos zintegrowany jest z bazą numerów EAN, gdzie po znalezieniu kodu, portal w sposób automatyczny wypełni pola nazwa, cena oraz VAT - wymagane 
do rejestracji produktu. Portal domyślnie przyporządkuje grupę towarową “wszystkie” a za jednostkę przyjmie towar sprzedawany na sztuki. Sposób ten w znaczny sposób zwiększa efektywność dodawania nowego asortymentu.
Dostępne pola:
 
	#. **EAN** - Europejski Kod Towarowy, popularnie nazywany kodem kreskowym
	#. **Nazwa towaru** - przyporządkowanie nazwy towaru max 39 znaków
	#. **Grupa towarowa** - organizacja produktów w liste kategorii
	#. **Jednostka** - określenie czy towar jest sprzedawany na sztuki badź na wagę
	#. **Stawka VAT**- stawka VAT wybierana ze zdefiniowanego słownika stawek VAT (8%, 23%, itp.),
	#. **Cena z VAT** - określenie ceny brutto
	#. **Cena 2** - kreślenie ceny2 brutto.
	#. **Cena 3** - kreślenie ceny3 brutto
	#. **Cena 4** - kreślenie ceny4 brutto
	#. **Opis** - notatka dla sprzedawcy
	#. **Zdjęcie** - zdjęcie produktu ułatwiający lokalizację wyszukiwanego produktu. Zdjęcie można dodawać również przez aplikację na tablecie z użyciem wbudowanego aparatu.

.. note::

   		Portal może przyjąć do 4 cen brutto z czego tylko cena 1 jako cena domyślna jest wymagana do wypełnienia. Pozostałe ceny dają możliwość sprzedawcy szybkiego wyboru ceny w zależności od jego preferencji. 

Usuwanie towaru z portalu
==============================

Towar można usunąć z listy towarów poprzez przycisk “usuń” znajdujący się na pozycji z listy. Usuwanie chodź z nazwy nie usuwa całkowicie towaru a tylko go dezaktywuje. Taka sytuacja zapobiega sytuacjom powstawania dziur w systemie kiedy np. sprzedamy towar gdzie po usunięciu go system nie będzie miał się do czego odwołać. Usunięty towar można z powrotem przywrócić zgłaszając się do administratora systemu admin@retilia.pl.

Towar usunięty znika z listy towarów zarówno na portalu jak i w wersji na tablet. Istnieje możliwość podejrzenia towarów usuniętych przez zastosowanie filtra listy wyboru “usunięty” dostępnego w menu listy. 

Zakładka "Dostawy" - tworzenie dostawy towaru
*****************************************************

Przyjęcie magazynowe jest stałym elementem funkcjonowania sklepu. Dzięki takiej operacji sprzedawca posiada wiedzę:
* od kogo kupił towar
* w jakiej ilości
* do którego sklepu ten towar został przyjęty
* w jakiej cenie został zakupiony
Informacje są na bieżąco przetwarzane przez system, dzięki którym użytkownik systemu ma możliwość kontrolować stany magazynowe oraz przeglądać raporty zysków sprzedaży.

.. warning::

   Dostawę można wykonywać wyłącznie na portalu.
   Informacja: Można wykonywać sprzedaż towaru bez zrobionej dostawy. Stan magazynowy dla tego towaru będzie ujemny.


Kroki do utworzenia dostawy
=====================================

#. **Proces dostawy należy zainicjować wchodząc w zakładkę Dokumenty > Dostawy**
#. **Wypełnić kolejno wszystkie pola formaularza**
	* Numer dostawy - jest to indywidualny numer dostawy, którego format jest dowolny. Można przyjąć prosty sposób numeracji np. 1/10/2015 co w domyśle oznacza dzień w jakim dostawa została przyjęta
	* Kontrahent - pole pozycji wyboru utworzone w zakładce “Kontrahenci”
	* Sklep - pole pozycji wyboru utworzone w zakładce “Sklepy”
	* Towar - pole pozycji wyboru utworzone w zakładce “Towary”
	* C.netto - cena bez vat zakupu towaru do kontrahenta
	* Vat - pole pozycji wyboru stawki vat na dany produkt
	* War.netto - przeliczane automatycznie 
	* War.brutto - przeliczane automatycznie 
	* Data przydatności.- pole nie mające na dany moment zastosowania.
#. **Kolejna pozycja towaru jest inicjowana za pomocą przycisku “dodaj pozycję”**
#. **Zatwierdzenie dostawy jest zapisywane za pomocą przycisku “Zapisz”**
#. **Po zapisaniu nowa dostawa jest widziana jako kolejny rekord listy dostwaw.**

Lista z pozycjami odstaw możliwa jest do edytowania edytowania bądź usunięcia. Najeżdżając wskaźnikiem myszki na lupkę można przejrzeć listę towarów będącej zbiorem jednej dostawy.
