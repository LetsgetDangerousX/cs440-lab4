# Vacuum Robot Grid (Lab 4)

## Grid Layout
The vacuum robot operates on a 3x4 grid with coordinates (row, column):

```
|       |    |   |    |
| ----- | -- | - | -- |
| start | 0  | 0 | 0  |
| 0     | X  | 0 | 0  |
| 0     | 0  | 0 | 10 |
```

- **Row 0**: (0,0)=start, (0,1)=0, (0,2)=0, (0,3)=0
- **Row 1**: (1,0)=0, (1,1)=X, (1,2)=0, (1,3)=0  
- **Row 2**: (2,0)=0, (2,1)=0, (2,2)=0, (2,3)=10

## Wall
- **Location**: Cell (1,1) contains 'X' which represents a wall/obstacle.
- The robot cannot move into this cell.

## Rewards
The reward structure is defined by the grid values:
- **Start position** (0,0): Reward = 0
- **Wall** (1,1): Cannot enter (no reward)
- **Empty cells** (0): Reward = 0
- **Goal position** (2,3): Reward = 10

The robot aims to reach the goal at (2,3) with a reward of 10 points.
