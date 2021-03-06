# Projektowanie i implementacja zaawansowanych aplikacji PHP

## Wprowadzenie

PHP to współczesny skryptowy język programowania dedykowany głównie dla rozwiązań webowych, którego pierwsza wersja została utworzona w 1994 roku przez Rasmus Lerdorfa. Początkowo był to zestaw prostych Common Gateway Interface (CGI), umożliwiających łączenie mechanizmów generowania stron HTML z kodem zaimplementowanym w języku C. Wraz z kolejnymi wydaniami języka (PHP 3 w roku 1998, PHP 4 w roku 1999, PHP 5 w roku 2004) był on wzbogacany o kolejne konstrukcje językowe, w tym koncepty programowania obiektowego. W 2015 roku wydana została wersja 7, w której całkowicie przeprojektowano mechanizmy runtime'u, zwiększając w ten sposób znacząco wydajność aplikacji opartych o język PHP.

Na przestrzeni lat język ten został obudowany szeregiem dodatkowych rozwiązań, wspomagających i upraszczających pracę developerów. Starsze aplikacje bardzo często korzystały więc z repozytoriów [PEAR](http://pear.php.net) oraz [PECL](https://pecl.php.net), obecnie sięga się bardzo często po rozwiązania m.in. typu [Composer](https://getcomposer.org) i powiązane z nim repozytorium [Packagist](https://packagist.org).

Swoją popularność język PHP zawdzięcza zarówno składni, upraszczającej proces poznawania języka, jak i bardzo rozbudowanemu ekosystemowi. Szacuje się, że język PHP (w różnych wersjach) jest wykorzystywany do obsługi ponad 83% znanych serwisów webowych.

Celem kursu jest nauka zarówno języka PHP jak i jego praktyczne wykorzystanie do implementacji złożonych aplikacji, w oparciu o aktualnie wykorzystywane narzędzia i rozwiązania (nowoczesne frameworki web, architektury aplikacji i systemu).


## Wymagania

Uczestnik zajęć powinien dysponować:

- podstawową wiedzą z zakresu programowania obiektowego
- podstawową znajomością relacyjnych baz danych (przydatne w drugiej części zajęć)


## Forma zajęć

Zajęcia odbywać się będą cyklicznie, zgodnie z informacjami w Systemie Zapisów:

- wykład, sala 119
- pracownia, sala 108


## Pracownia

### Zasady zaliczenia przedmiotu
   
- W każdym tygodniu zajęć publikowane będzie zadanie, przeznaczone do samodzielnego zaprogramowania. Za każde poprawnie zaprogramowane zadanie i oddane w terminie można będzie dostać do 10 punktów.
- Zadania publikowane będą w tygodniu poprzedzającym termin ich realizacji. Zadania należy oddawać terminowo.
- Prezentacja wykonanych zadań odbywać się będzie na pracowni. Podczas prezentacji mogą zostać zadane dodatkowe pytania dotyczące rozwiązania.
- Ocena końcowa wynikać będzie z liczby zgromadzonych w trakcie zajęć punktów:
    - 50% na ocenę dostateczną
    - 90% na ocenę bardzo dobrą,
    - oceny pośrednie są ustalane liniowo względem określonych powyżej wartości

    
## Listy zadań

**Uwaga!** Osoby, które zalegają z zadaniami z pracowni proszę o kontakt.

- [Zadanie 1, Cipher](exercises/01-cipher.md)
- [Zadanie 2, Numbers](exercises/02-numbers.md)
- [Zadanie 3, Students](exercises/03-students.md)
- [Zadanie 4 + 5, Accounts](exercises/04-05-accounts.md)
    - Ze względu na zagadnienia, 2 listy zostały połączone w jedno zadanie
- [Zadanie 6, Pager](exercises/06-pager.md)
    - UWAGA! Zadanie posiada rozszerzenie, za które można uzyskać dodatkowe punkty
- [Zadanie 7 + 8, Commands Bus + Financial Commitment](exercises/07-08-intro.md)
    - Ze względu na zagadnienia, 2 listy zostały połączone
    - UWAGA! Zadanie posiada rozszerzenie, za które można uzyskać dodatkowe punkty
- [Zadanie 9, Database repository](exercises/09-database-repository.md)
- [Zadanie 10, Data partitioning](exercises/10-database-performance.md)
- [Zadanie 11, Symfony Console](exercises/11-console-app.md) (ostatnie)

## Notatki z wykładów

Lista notatek z poszczególnych wykładów, wraz z linkami do dodatkowych materiałów uzupełniających

- [Wykład 1, Podstawy języka PHP, wprowadzenie do ekosystemu](notes/lectures/01-php-intro.md)
- [Wykład 2, Obiektowość, część 1](notes/lectures/02-objects.md)
- [Wykład 3, Obiektowość, część 2](notes/lectures/03-objects-continued.md)
- [Wykład 4, HTTP Flow](notes/lectures/04-http-flow.md)
- [Wykład 5, Szablony](notes/lectures/05-templates.md)
- [Wykład 6, Test Driven Development](notes/lectures/06-tdd.md)
- [Wykład 7, Modelowanie zdarzeniowe](notes/lectures/07-domain-modeling-events.md)
- [Wykład 8, Modelowanie z wykorzystaniem EventStormingu](notes/lectures/08-domain-modeling-event-storming.md)
- [Wykład 9, Modelowanie, integracja](notes/lectures/09-modeling-integration.md)
- [Wykład 10, Bazy danych, część 1](notes/lectures/10-database.md)
- [Wykład 11, Bazy danych, część 2](notes/lectures/11-database-continued.md)
- [Wykład 12, Wydajność i skalowalność](notes/lectures/12-performance-and-scalability.md)
- [Wykład 13, Deployment aplikacji](notes/lectures/13-deployment.md)

## Literatura

### Elektroniczna

- Dokumentacja języka, http://php.net/manual/en/
- PHP The Right Way, http://www.phptherightway.com/
