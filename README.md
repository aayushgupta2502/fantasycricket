# Fantasy Cricket
This project aims to develop an ESPN-esque Fantasy Cricket app for the IPL.

## IPL Fantasy Cricket Platform Scoring System

### General Points:

| **Type of Points**                                          | **T20**  |
|-------------------------------------------------------------|----------|
| Being a part of the starting XI                             | 4        |
| Every run scored                                            | 1        |
| Every wicket taken (excluding run out)                      | 25       |
| Catch taken                                                 | 8        |
| Stumping / Run Out (direct)                                 | 12       |
| Run Out (Thrower / Catcher)                                 | 6 / 6    |
| Dismissal for a Duck (only for batsmen, wicket-keepers, and all-rounders) | -2       |

### Bonus Points:

| **Type of Points**                                          | **T20**  |
|-------------------------------------------------------------|----------|
| Every boundary hit                                          | 1        |
| Every six-hit                                               | 2        |
| Half Century (50 runs scored by a batsman in a single inning) | 8        |
| Century (100 runs scored by a batsman in a single inning)   | 16       |
| Maiden Over                                                 | 8        |
| 4 wickets                                                   | 8        |
| 5 wickets                                                   | 16       |

### Economy Rate Bonus:

| **Type of Points**                                          | **T20**  |
|-------------------------------------------------------------|----------|
| Minimum overs bowled by a player to be applicable           | 2 overs  |
| Between 6 and 5 runs per over                               | 2        |
| Between 4.99 and 4 runs per over                            | 4        |
| Below 4 runs per over                                       | 6        |
| Between 9 and 10 runs per over                              | -2       |
| Between 10.01 and 11 runs per over                          | -4       |
| Above 11 runs per over                                      | -6       |

### Low Strike Rate Penalty (except bowlers):

| **Type of Points**                                          | **T20**  |
|-------------------------------------------------------------|----------|
| Minimum balls faced by a player to be applicable            | 10 balls |
| Between 60 and 70 runs per 100 balls                        | -2       |
| Between 50 and 59.99 runs per 100 balls                     | -4       |
| Below 50 runs per 100 balls                                 | -6       |

