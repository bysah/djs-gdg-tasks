# djs-gdg-tasks
GDG Interview Tasks

## Task 1: Pushpa - The Red Sandalwood Stash
Analyze a forest grid map to locate the densest stash of 'Lal Chandan' trees. The grid is a matrix where:
- `1` = Lal Chandan Tree (valuable).
- `0` = Empty spot.

### Features:
- Input the extraction zone size (m x m) and center coordinates.
- Slice out the extraction zone and count Lal Chandan Trees.
- Randomize tree positions while keeping the grid shape.

### Final Output:
The extraction zone(3X3) is:
[
    [1, 1, 1],
    [0, 1, 1],
    [1, 1, 0]
]
Total Trees: 7
