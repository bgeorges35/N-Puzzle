# N-Puzzle

The goal of this project is to solve the N-puzzle game using the A* search algorithm, Greedy search algorithm or Djikstra's  search algorithm.

<table align="center">
  <tr align="center">
    <td><img src="https://miro.medium.com/max/420/1*HppvOLfDxXqQRFn0Cv2dHQ.gif"></td>
    <td><img width = 300 src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Greedy-search-path.gif"></td>
    <td><img src="https://miro.medium.com/max/420/1*2jRCHqAbTCY7W7oG5ntMOQ.gif"></td>
  </tr>
    <tr align="center">
    <td>A* search algorithm</td>
     <td>Greedy algorithm</td>
     <td>Djikstra's algorithm</td>
    </tr>
 </table>

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install -r requirements.txt
```

## Usage

```python npuzzle.py```

```bash
usage: npuzzle.py [-h] [-l] file

  positional arguments:
    file          path of n-puzzle file


  optional arguments:
    -h, --help    show this help message and exit
    -l, --linear  solve N-Puzzle lineary

```

## Example

```
python npuzzle.py an_example_of_N-Puzzle
python npuzzle.py an_example_of_N-Puzzle -l
```
