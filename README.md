# STTO

Command-line utility written in Go to check total line of code in a file present in a directory.



## Authors

- [Mainak Bhattacharjee](https://github.com/mainak55512)


## Dependencies

- go 1.22.5
- github.com/mattn/go-runewidth v0.0.9
- github.com/olekukonko/tablewriter v0.0.5


## Usage
### usage 1:
```bash
❯ stto
+--------------------+------------+-----------------+-----+----------+------+
|     FILE TYPE      | FILE COUNT | NUMBER OF LINES | GAP | COMMENTS | CODE |
+--------------------+------------+-----------------+-----+----------+------+
| vim_tutorial.c.swp |          1 |               3 |   0 |        0 |    3 |
| c                  |         46 |            1113 |  23 |        2 | 1088 |
| py                 |         14 |             165 |   6 |        6 |  153 |
| class              |          1 |               8 |   0 |        0 |    8 |
| m                  |          1 |               4 |   0 |        0 |    4 |
| out                |          1 |               6 |   0 |        0 |    6 |
| js                 |          1 |              21 |   2 |        0 |   19 |
| java               |          1 |              21 |   3 |        0 |   18 |
| css                |          1 |              14 |   0 |        0 |   14 |
| html               |          1 |              13 |   0 |        0 |   13 |
| cbl                |          1 |              10 |   0 |        0 |   10 |
| jl                 |          2 |              16 |   1 |        0 |   15 |
| txt                |          1 |              19 |   3 |        0 |   16 |
+--------------------+------------+-----------------+-----+----------+------+
+----------+--------+
|  TOTAL   | NUMBER |
+----------+--------+
| Files    |     72 |
| Lines    |   1413 |
| Gaps     |     38 |
| Comments |      8 |
| Code     |   1367 |
+----------+--------+

### Usage 2:
❯ stto -ext c
+-----------+------------+-----------------+-----+----------+------+
| FILE TYPE | FILE COUNT | NUMBER OF LINES | GAP | COMMENTS | CODE |
+-----------+------------+-----------------+-----+----------+------+
| c         |         46 |            1113 |  23 |        2 | 1088 |
+-----------+------------+-----------------+-----+----------+------+

```
** Only single line comments are supported

## 🚀 About Me
I'm a Tech enthusiast and a hobby programmer.
You can visit my [Github profile](https://github.com/mainak55512) to see my other works :)

