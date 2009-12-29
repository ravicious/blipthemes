======================================
/ JABOL - Just Another BliplOg Layout\
/ Nazwa kodowa: KELERIS              \
/ Wersja: 0.0.1                      \
/                                    \
/ autor: Rafał "ravicious" Cieślak   \
/ www: http://to.niejest.be          \
/ blip: ^ravicious                   \
/ e-mail: ravicious@gmail.com        \
/ jabber: ravicious@jabbim.pl        \
======================================

FAQ

P: Jak odblokować pokazywanie tagów/obserwowanych/obserwujących?
O: Przyjmijmy, że chcesz pokazać na bliplogu używane przez Ciebie tagi. Ten szablon to umożliwia, tak samo jak pokazywanie obserwowanych lub obserwujących, ale jest to domyślnie ukryte. Co należy zrobić? Szukasz w kodzie szablonu zapisu w stylu <!-- tagi -->. Obok znajduje się znacznik <!-- który należy usunąć. Następnie poszukaj zapisu <!-- tagi - koniec -->. Przed nim znajduje się znacznik --> który również należy usunąć. Teraz zapisz szablon - tagi powinny się wyświetlać. Analogicznie postępuj, jeśli chcesz "odkryć" obserwowanych i/lub obserwujących.

P: Czy ten szablon obsługuje funkcję #hide?
O: Tak, tagi #hide i #test są ukrywane na bliplogu.

INFORMACJE OD KODERA

* "Keleris" to port domyślnego szablonu Twittera, dlatego klasy i identyfikatory za bardzo się nie różnią.
* JABOL udostępniany na licencji CC: BY-NC
