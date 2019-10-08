# Sudoku-Solver


## How to use
Edit example.sud as described below and type in cli:

`ghci`

`:l Sudoku.hs`

`readAndSolve "example.sud"`


## The file to solve should be defined in "example.sud". 

| 3   | 6   |     |     | 7   | 1   | 2   |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     | 5   |     |     |     |     | 1   | 8   |     |
|     |     | 9   | 2   |     | 4   | 7   |     |     |
|     |     |     |     | 1   | 3   |     | 2   | 8   |
| 4   |     |     | 5   |     | 2   |     |     | 9   |
| 2   | 7   |     | 4   | 6   |     |     |     |     |
|     |     | 5   | 3   |     | 8   | 9   |     |     |
|     | 8   | 3   |     |     |     |     |  6  |     |
|     |     | 7   | 6   | 9   |     |     | 4   | 3   |

Define as following 9x9 grid: A period for zeros and number for non-zeros.

36..712..

.5....18.

..92.47..

....13.28

4..5.2..9

27.46....

..53.89..

.83....6.

..769..43

## And the output will be 

![Screenshot 2019-10-08 at 23 07 01](https://user-images.githubusercontent.com/31474146/66433336-70924d00-ea20-11e9-955f-875fef6b00f0.png)


364871295

752936184

819254736

596713428

431582679

278469351

645328917

983147562

127695843

Visually represented

| 3   | 6   | 4   | 8   | 7   | 1   | 2   | 9   | 5   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 7   | 5   | 2   | 9   | 3   | 6   | 1   | 8   | 4   |
| 8   | 1   | 9   | 2   | 2   | 4   | 7   | 3   | 6   |
| 5   | 9   | 6   | 7   | 1   | 3   | 4   | 2   | 8   |
| 4   | 3   | 1   | 5   | 8   | 2   | 6   | 7   | 9   |
| 2   | 7   | 8   | 4   | 6   | 9   | 3   | 5   | 1   |
| 6   | 4   | 5   | 3   | 2   | 8   | 9   | 1   | 7   |
| 9   | 8   | 3   | 1   | 4   | 7   | 5   | 6   | 2   |
| 1   | 2   | 7   | 6   | 9   | 5   | 8   | 4   | 3   |
