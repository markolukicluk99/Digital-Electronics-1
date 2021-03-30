# Repo link:
https://github.com/markolukicluk99/VUT-Digital-Electronics-1/blob/main/Labs/07-ffs/README.md

# Tabulky:

| *D* | *q(n)* | *q(n+1)* | *Comm* |
| :-: | :-: | :-: | :-- |
| 0 | 0 | 0 | No change |
| 0 | 1 | 0 | Reset |
| 1 | 0 | 1 | Set |
| 1 | 1 | 1 | No change |

| *J* | *k* | *q(n)* | *q(n+1)* | *Comm* |
| :-: | :-: | :-: | :-: | :-- |
| 0 | 0 | 0 | 0 | No change |
| 0 | 0 | 1 | 1 | No change |
| 0 | 1 | 0 | 0 | Reset|
| 0 | 1 | 1 | 0 | Reset |
| 1 | 0 | 0 | 1 | Set |
| 1 | 0 | 1 | 1 | Set |
| 1 | 1 | 0 | 1 | Inverse |
| 1 | 1 | 1 | 0 | Inverse |

| *T* | *q(n)* | *q(n+1)* | *Comm* |
| :-: | :-: | :-: | :-- |
| 0 | 0 | 0 | No change |
| 0 | 1 | 1 | No change |
| 1 | 0 | 1 | Inverse |
| 1 | 1 | 0 | Inverse |