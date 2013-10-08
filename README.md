# Tabs To Table
Converts tabular data into a glorious table format.

# Example
```
Position	Elevation
0.00	0.00
1.00	0.17
2.00	0.37
3.00	0.58
4.00	0.76
5.00	0.99
6.00	1.20
7.00	1.45
8.00	1.69
9.00	1.86
10.00	2.06
11.00	2.24
12.00	2.48
13.00	2.65
```

Converts to:

```
Position  Elevation
    0.00       0.00
    1.00       0.17
    2.00       0.37
    3.00       0.58
    4.00       0.76
    5.00       0.99
    6.00       1.20
    7.00       1.45
    8.00       1.69
    9.00       1.86
   10.00       2.06
   11.00       2.24
   12.00       2.48
   13.00       2.65
```

# Usage
- **Windows:** <kbd>CTRL+Alt+T</kbd>
- **OSX:** <kbd>Super+Alt+T</kbd>
- **Linux:** <kbd>Ctrl+Alt+T</kbd>

# Configure
So far, only the table separator is configrable. Open `TabsToTable.sublime-settings` and change the `table_separator` to be whatever you'd like. A good option is ` | ` which will neatly separate your table into:

```
Position | Elevation
    0.00 |      0.00
    1.00 |      0.17
    2.00 |      0.37
    3.00 |      0.58
    4.00 |      0.76
    5.00 |      0.99
    6.00 |      1.20
    7.00 |      1.45
    8.00 |      1.69
    9.00 |      1.86
   10.00 |      2.06
   11.00 |      2.24
   12.00 |      2.48
   13.00 |      2.65
```

# Props
Big props go to [Dr. Drang](http://www.leancrew.com/all-this/) for his post, [Updated Text Tables bundle](http://www.leancrew.com/all-this/2008/09/updated-text-tables-bundle-for-textmate/).

# License
MIT - [http://jbrooksuk.mit-license.org](http://jbrooksuk.mit-license.org)