przykład naszego autorskiego programu do zabaw szachowych, które wciąga dzieci, jako samodzielna gra, a jednocześnie bardzo rozwija ich umiejętności, myślenia, rozwiązywania problemów i ...uczy szachów, bo widzenie ruchów skoczka, to bardzo mocna broń na każdym poziomie, bo może zmienić losy partii do ostatniej chwili  ;)  

  
[https://tymczas.github.io/skoczek/skoczek.html](https://tymczas.github.io/skoczek/skoczek.html) (to jest wersja pokazowa, gdyż obecnie wszystkie gry uruchamiamy lokalnie w klasie BEZ konieczności internetu, ale kilka gier wrzuciłem online, żeby nie tłumaczyć o co chodzi, jak z kimś rozmawiam, tylko dać mu link do zagrania)
Problem skoczka szachowego to matematyczne i algorytmiczne zadanie polegające na tym, aby poruszając się według reguł ruchu skoczka na planszy szachowej, odwiedzić każde pole dokładnie jeden raz. Celem jest znalezienie ścieżki (tzw. trasy skoczka), która obejmuje wszystkie pola na planszy bez powtarzania odwiedzonych.

## Definicja problemu

Skoczek (koń) porusza się w kształcie litery "L": dwa pola w jednym kierunku i jedno pole w bok. Problem polega na tym, aby zaplanować sekwencję ruchów skoczka tak, by odwiedził wszystkie pola planszy (standardowo 8x8) raz i tylko raz.

## Rodzaje rozwiązań

- Ścieżka zamknięta: skoczek po ostatnim ruchu może wrócić na początkowe pole, tworząc cykl Hamiltona.
    
- Ścieżka otwarta: skoczek obejdzie wszystkie pola, ale nie wraca do punktu startowego.
    

Na planszach o wymiarach mniejszych niż 5x5 rozwiązanie często nie istnieje, ale dla plansz 8x8 i większych można znaleźć takie trasy.

## Matematyczne i algorytmiczne znaczenie

Problem skoczka jest przykładem problemu znalezienia ścieżki Hamiltona w teorii grafów (ścieżki odwiedzającej wszystkie wierzchołki bez powtórzeń). Jest także popularnym zadaniem algorytmicznym z zastosowaniem metod takich jak backtracking czy algorytm Warndorffa, który przy wyborze ruchu kieruje się zasadą minimalizacji dostępnych następnych ruchów, co znacznie optymalizuje znalezienie rozwiązania.

Leonhard Euler zajmował się tym problemem pod koniec XVIII wieku i stworzył metody umożliwiające znalezienie tras skoczka, a liczba możliwych rozwiązań jest ogromna, sięgając milionów kombinacji.[math+4](https://www.math.edu.pl/problem-skoczka-szachowego)


Leonhard Euler, wybitny szwajcarski matematyk XVIII wieku, zajął się problemem skoczka szachowego w 1759 roku, przedstawiając pierwszą obszerną matematyczną analizę tego zadania na planszy 8x8. W liście do Christiana Goldbacha z 1756 roku Euler podał przykłady rozwiązań polegających na odwiedzaniu kolejnych pól przez skoczka, zakrywając już odwiedzone pola monetami, co było praktyczną pomocą w wizualizacji problemu. Opublikował później swoje badania, wskazując między innymi, jak można uzyskać pełną trasę skoczka z częściowej podróży czy jak przekształcić ścieżkę otwartą w zamkniętą. Euler badał różne rozmiary i kształty plansz, w tym kwadratowe i prostokątne, oraz zwracał uwagę na istnienie i brak ścieżek zamkniętych w pewnych rozmiarach plansz.

Jego prace to fundament dla dalszych algorytmów, m.in. reguły Warnsdorffa (1823), która znacznie ułatwia znalezienie tras, polegając na tym, aby skoczek zawsze przechodził na pole z najmniejszą liczbą dostępnych kolejnych ruchów. Problem skoczka szachowego jest ważnym zadaniem w teorii grafów, związanym z poszukiwaniem ścieżki Hamiltona. Liczba możliwych tras na planszy 8x8 jest ogromna, liczącą się w milionach, co świadczy o ogromnej złożoności problemu.

Euler nie tylko nadał problemowi formalny matematyczny opis, ale jego prace stały się początkiem badań nad algorytmicznymi metodami rozwiązywania takich zadań kombinatorycznych i topologicznych.[mlodytechnik+3](https://mlodytechnik.pl/eksperymenty-i-zadania-szkolne/szachy/30892-problem-skoczka-szachowego)​

1. [https://mlodytechnik.pl/eksperymenty-i-zadania-szkolne/szachy/30892-problem-skoczka-szachowego](https://mlodytechnik.pl/eksperymenty-i-zadania-szkolne/szachy/30892-problem-skoczka-szachowego)
2. [https://zs2.naleczow.pl/lekcja-informatyki-w-terenie/](https://zs2.naleczow.pl/lekcja-informatyki-w-terenie/)
3. [https://pl.frwiki.wiki/wiki/Probl%C3%A8me_du_cavalier](https://pl.frwiki.wiki/wiki/Probl%C3%A8me_du_cavalier)
4. [https://pl.wikipedia.org/wiki/%C5%9Acie%C5%BCka_Hamiltona](https://pl.wikipedia.org/wiki/%C5%9Acie%C5%BCka_Hamiltona)
5. [https://towarzystwo.edu.pl/assets/prace_matematyczne/2022_Amajewski.pdf](https://towarzystwo.edu.pl/assets/prace_matematyczne/2022_Amajewski.pdf)
6. [https://pl.wikipedia.org/wiki/Leonhard_Euler](https://pl.wikipedia.org/wiki/Leonhard_Euler)
7. [https://zs2.naleczow.pl/page/13/?cat=-1](https://zs2.naleczow.pl/page/13/?cat=-1)
8. [https://www.mimuw.edu.pl/~rytter/TEACHING/ALCOMB/index1.pdf](https://www.mimuw.edu.pl/~rytter/TEACHING/ALCOMB/index1.pdf)
9. [https://pages.mini.pw.edu.pl/~domitrzw/Kamienie.pdf](https://pages.mini.pw.edu.pl/~domitrzw/Kamienie.pdf)
10. [https://cloud6.edupage.org/cloud/matematyka_jest_wszedzie.pdf?z%3AfAdOR5XroUJBCHix9HHLfuiyd53E6MHy5stThdRmv2Nq0u4F5eVXLKzjYXiut6jb](https://cloud6.edupage.org/cloud/matematyka_jest_wszedzie.pdf?z%3AfAdOR5XroUJBCHix9HHLfuiyd53E6MHy5stThdRmv2Nq0u4F5eVXLKzjYXiut6jb)​

1. [https://www.math.edu.pl/problem-skoczka-szachowego](https://www.math.edu.pl/problem-skoczka-szachowego)
2. [https://pl.wikipedia.org/wiki/Problem_skoczka_szachowego](https://pl.wikipedia.org/wiki/Problem_skoczka_szachowego)
3. [https://swistak.codes/post/problem-skoczka-szachowego/](https://swistak.codes/post/problem-skoczka-szachowego/)
4. [https://www.math.edu.pl/rozwiazanie-problem-skoczka-szachowego](https://www.math.edu.pl/rozwiazanie-problem-skoczka-szachowego)
5. [https://towarzystwo.edu.pl/assets/prace_matematyczne/2022_Amajewski.pdf](https://towarzystwo.edu.pl/assets/prace_matematyczne/2022_Amajewski.pdf)
6. [https://e-tronix.eu/problem-skoczka-szachowego/](https://e-tronix.eu/problem-skoczka-szachowego/)
7. [https://mlodytechnik.pl/eksperymenty-i-zadania-szkolne/szachy/30892-problem-skoczka-szachowego](https://mlodytechnik.pl/eksperymenty-i-zadania-szkolne/szachy/30892-problem-skoczka-szachowego)
8. [https://zsoms.eu/wp-content/uploads/2020/03/prezentacja_KIRE.pdf](https://zsoms.eu/wp-content/uploads/2020/03/prezentacja_KIRE.pdf)
9. [https://matematyka.pl/informatyka-f13/c-problem-skoczka-szachowego-t310376.html](https://matematyka.pl/informatyka-f13/c-problem-skoczka-szachowego-t310376.html)
10. 
ps to jest klasyczne zagadnienie rozwiązywalne czysto matematyczne np przez cykl Hamiltona,  [algorytm Pohla-Warnsdorffa](https://swistak.codes/post/problem-skoczka-szachowego/#algorytm-pohla-warnsdorffa) , [Reguła Warnsdorffa](https://swistak.codes/post/problem-skoczka-szachowego/#reguła-warnsdorffa)  
[https://pl.wikipedia.org/wiki/Cykl_Hamiltona](https://pl.wikipedia.org/wiki/Cykl_Hamiltona)  
[https://pl.wikipedia.org/wiki/Problem_skoczka_szachowego](https://pl.wikipedia.org/wiki/Problem_skoczka_szachowego)  
[https://swistak.codes/post/problem-skoczka-szachowego/](https://swistak.codes/post/problem-skoczka-szachowego/)  
[https://demonstrations.wolfram.com/TheKnightsTour/](https://demonstrations.wolfram.com/TheKnightsTour/)
