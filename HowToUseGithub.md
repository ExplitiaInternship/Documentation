## Przed tobą krótki tutorial mający na celu utworzenie i postawienie Githuba w sourcetree na Twoim komputerze, ale na początek...

# PODCZAS REALIZACJI ZADAŃ KAŻDY Z PRAKTYKANTÓW MUSI UTWORZYĆ SWOJEGO BRANCHA I PRACOWAĆ NA NIM W CELU UTRZYMANIA PORZĄDKU W STRUKTURZE GIT-A. PROSZĘ O NIE PUSHOWANIE ZMIAN NA MASTERA/MAINA. Informację jak to zrobić znajdziesz na dole tego dokumentu.

## Tworzenie konta na githubie i podłączenie do sourcetree
1. Utwórz konto na Githubie https://github.com/
2. Po utworzeniu konta wyślij na mój adres email wojciech.kostrzewski@explitia.com maila o treści : "Proszę o dodanie mnie (imię i nazwisko) do zespołu praktykantów. [tutaj wpisz nazwę Twojego użytkownika Github]"
3. Po akceptacji zostaniesz dodany do organizacji Githubowej "ExplitiaInternship" utworzonej na potrzeby praktyk. Powinieneś w tym momencie mieć dostep do linku https://github.com/ExplitiaInternship
4. W lewym górnym rogu znajdować się będzie kilka zakładek z czego w tym momencie najważniejsza dla Ciebie będzie "Repositories".![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/35cbc12f-e09e-402b-87e4-a5f957bdd822)
5. W celu pobrania repozytorium należy:
- w celu sklonowania repozytorium przy użyciu sourcetree będziesz musiał połaczyć je z githubem. W nowym oknie wybieramy przycisk remote a następnie klikamy przycisk oznaczony numerem 2 aby dodać konto ![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/2ccf7bc0-cb56-4e4e-9718-b03dcd2c96bf)
- ustawiamy opcje tak jak na screenie i klikamy przycisk zaznaczony strzałką - zostaniemy przekierowani na stronę githuba aby się zalogować w celu zatwierdzenia, że sourcetree może korzystać z githuba ![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/66eb68ed-75d5-4994-adca-c059130c3e5e)
- teraz należy przejść na githubie do wybranego repozytorium klikając na nie
- skopiować adres repozytorium, które chcemy sklonować na nasz lokalny komputer według instrukcji załaczonych na zdjęciu ![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/813b82e2-9e2d-4edd-92ec-c1975314ece7)
- otworzyć sourcetree i w nowej zakładce kliknąć "clone" zaznaczone munerem 1 na zdjęciu. W pole oznaczone jako 2 wprowadzamy wcześniej skopiowany adres url. W pole oznaczone jako 3 wprowadzamy adres to folderu na Twoim komputerze do którego chcesz sklonować repozytorium. Folder do którego chcesz sklonować repozytorium nie może zawierać innnego repozytorium. Całość zatwierdzamy klikając przycisk clone oznaczony numerem 4. ![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/83f814d4-4524-4a07-8703-1aa916b368e4)
- po udanym sklonowaniu powinniśmy widzieć w sourcetree taki ekran ![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/37f38a49-9297-4170-a7d1-57976ecfc499)
numerami oznaczone są głowne panele. 1. panel Workspace pozwala przeklikać miedzy kartami filestatus i history - w filestatus pojawiać się będą pliki, które zmienisz w swoim repozytorium. Kliknięcie na karte history wyświetla panel oznaczony numerem 3. Panel numer 2 to struktura repozytorium, interesującą kartą jest karta branches gdzie możesz zobaczyć na którym branchu aktualnie się znajdujesz, oraz wybrać inny. W celu przepięcie się na inny branch należy to zrobić dwa razy klikając na jego nazwę.


## Podstawowy know how pobierania zmian, zmieniania branchy i pushowania swoich zmian

Jest to krótkie wprowadzenie w obsługę sourcetree. Jeśli chcesz zagłębić się w szczegóły informacji na ten temat w Internecie jest ogrom.

Najczęściej wykorzystywane narzędzia z sourcetree zostały zaznaczone na screenie 

![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/5d6d7a11-00e3-49f2-b8e0-70dae312e7eb)

- commit - pozwala nam zacommitować nasze zmiany. Commitując zmiany mamy możliwość wybrac, które z pośród wprowadzonych przez nas zmian chcemy wypushować.
- pull pobiera zmiany z repozytorium
- push wypucha zacommitowane zmiany lokalnie do repozytorium
- fetch pobiera informacje czy do pobrania z repozytorium sa jakieś nowe zmiany. Jeśli jakieś są to przy przycisku pull pojawi się liczba reprezentująca ilość commitów do pobrania.
- branch pozwala utworzyć nowego brancha - tj odnogę głównego projektu na której możesz działać nie wpływając na główny projekt

### Workflow w celu pobrania nowych zmian:

klikam fetch (pobieram informacje czy są jakieś zmiany)-> (jeśli są zmiany do pobrania) klikam pull

### Worflow w celu wypushowania lokalnych zmian 

Jeśli mamy jakieś zmiany do zacommitowania będzie wyglądało to w ten sposób ![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/68b76227-4832-4471-967d-fd07fdb2d2ef)

Klikając na commit przechodzimy do panelu z podsumowaniem. Pliki które chcemy zacommitować wybieramy i klikamy stage selected, jesli chcemy zacommitować wszystkie to wybieramy stage all (oznaczone numerem 1). W polu oznacoznym numerem 2 wpisujemy wiadomość dotyczącą naszego commita. Całość zatwierdzamy klikając przycisk oznaczony numerem 3 Commit.![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/5d61b310-d4d0-42ac-aa78-fa51a663262a)
 
Po zacommitowaniu zmian, mozemy je wypushować klikając przycisk push i wybierając brancha, który będzie nas interesował. 






# Jak utworzyć swojego brancha?

Klikamy przycisk branch i uzupełniamy dialog. Dobrą praktyką jest tworzenie brancha o nazwie pierwsza litera imienia i nazwiska ukośnik i nazwa tego co robimy na tym branchu. W moim przypadku mogłoby to wyglądać wk/minimes-training. Użycie ukośnika w nazwie utworzy ładną strukturę w branchach.

![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/0b48af62-2ecf-4a99-9f26-5bb293e41a58)

Utworzony branch widoczny będzie w panelu branches 
![image](https://github.com/ExplitiaInternship/Documentation/assets/163396037/6afeb1fd-2612-44a1-958f-eff66a46c32c)





