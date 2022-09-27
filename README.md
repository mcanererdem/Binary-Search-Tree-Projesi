# Binary-Search-Tree-Projesi
## Proje 3
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
root = 7
7

5 < 7 soldan

= [5 / 7]

1 < 7 soldan  ->  1 < 5 soldan

= [1 / 5]  /* [5 / 7]

8 > 7 sağdan

= [1 / 5]  /* [5 / 7 \ 8]

3 < 7 soldan -> 3 < 5 -> soldan -> 3 > 1 -> sağdan

= [1 \ 3] / [1 / 5]  /* [5 / 7 \ 8]

6  < 7 soldan -> 6 > 5 -> sağdan

= [1 \ 3] / [1 / 5 \ 6]  /* [5 / 7 \ 8]

0 < 7 -> soldan 0 < 5 -> soldan 0 < 1 -> soldan

= [0 / 1 \ 3] / [1 / 5 \ 6]  /* [5 / 7 \ 8]

9 > 7 -> sağdan 9 > 8 -> sağdan

= [0 / 1 \ 3] / [1 / 5 \ 6]  /* [5 / 7 \ 8] *\ [8 \ 9]

4 < 7 -> soldan 4 < 5 -> soldan 4 > 1 -> sağdan 4 > 3 -> sağdan

= [3 \ 4] \ [0 / 1 \ 3] / [1 / 5 \ 6]  /* [5 / 7 \ 8] *\ [8 \ 9]

2 < 7 -> soldan 2 < 5 -> soldan 2 > 1 -> sağdan 2 < 3 -> soldan

= [2 / 3 \ 4] \ [0 / 1 \ 3] / [1 / 5 \ 6]  /* [5 / 7 \ 8] *\ [8 \ 9]
