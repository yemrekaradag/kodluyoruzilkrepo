# Binary Search Tree – [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Root: İlk eleman 7 → root olur.

    7

5 < 7 → root'un soluna eklenir.

    7

/
5

1 < 7 → soluna bak → 1 < 5 → 5’in soluna eklenir.

    7

/
5
/
1

8 > 7 → root'un sağına eklenir.

    7

/ \
 5 8
/
1

3 < 7 → sol, 3 < 5 → sol, 3 > 1 → 1’in sağına eklenir.

    7

/ \
 5 8
/
1
\
 3

6 < 7 → sol, 6 > 5 → 5’in sağına eklenir.

    7

/ \
 5 8
/ \
1 6
\
 3

0 < 7 → sol, 0 < 5 → sol, 0 < 1 → 1’in soluna eklenir.

    7

/ \
 5 8
/ \
1 6

/
0 3

9 > 7 → sağ, 9 > 8 → 8’in sağına eklenir.

7
/ \
 5 8
/ \ \

1 6 9
/
0 3

4 < 7 → sol, 4 < 5 → sol, 4 > 1 → sağ, 4 > 3 → 3’ün sağına eklenir.

7
/ \
 5 8
/ \ \

1 6 9
/
0 3

4

2 < 7 → sol, 2 < 5 → sol, 2 > 1 → sağ, 2 < 3 → 3’ün soluna eklenir.

```
   7
  / \
 5   8
/ \     \
1   6     9
/ \
0   3
/ \
2   4
```
