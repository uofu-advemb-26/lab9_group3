# Session 1
## Invariant statements
* A train should never be present with the arms up
* Power is always on
* Sensors always function
* Each track is one-way
* Each present signal will be precceeded ny an approach signal
* Each depart will be pre



# Session 2
## Markdown table

| number | arms_down | alarm_on | northbound_present | southbound_present | north_approach | south_approach | north_depart | south_depart | elapsed | safety_hazard |
|--------|-----------|----------|--------------------|--------------------|----------------|----------------|--------------|--------------|---------|---------------|
|  0     | 0         | 0        | 0                  | 0                  | 6              | 5              | I            | I            | I       |               |
|  1     | 0         | 0        | 0                  | 1                  | I              | I              | I            | I            | I       |               |
|  2     | 0         | 0        | 1                  | 0                  | I              | I              | I            | I            | I       |               |
|  3     | 0         | 0        | 1                  | 1                  | I              | I              | I            | I            | I       |               |
|  4     | 0         | 1        | 0                  | 0                  | 6              | 5              | I            | I            | 0       |               |
|  5     | 0         | 1        | 0                  | 1                  | 7              | I              | I            | I            | 13      |               |
|  6     | 0         | 1        | 1                  | 0                  | I              | 7              | I            | I            | 14      |               |
|  7     | 0         | 1        | 1                  | 1                  | I              | I              | I            | I            | 15      |               |
|  8     | 1         | 0        | 0                  | 0                  | I              | I              | I            | I            | I       |               |
|  9     | 1         | 0        | 0                  | 1                  | I              | I              | I            | I            | I       |               |
| 10     | 1         | 0        | 1                  | 0                  | I              | I              | I            | I            | I       |               |
| 11     | 1         | 0        | 1                  | 1                  | I              | I              | I            | I            | I       |               |
| 12     | 1         | 1        | 0                  | 0                  | 14             | 13             | I            | I            | 4       |               |
| 13     | 1         | 1        | 0                  | 1                  | 15             | I              | I            | 12           | 13      |               |
| 14     | 1         | 1        | 1                  | 0                  | I              | 15             | 12           | I            | 14      |               |
| 15     | 1         | 1        | 1                  | 1                  | I              | I              | 13           | 14           | 15      |               |


## Invariant table

| number |                       invariant                              |
|--------|--------------------------------------------------------------|
| 16     | A train should never be present with the arms up             |
| 17     | Power is always on                                           |
| 18     | Sensors always function                                      |
| 19     | Each track is one-way                                        |
| 20     | Each present signal will be precceeded by an approach signal |
| 21     | Each depart will be precceeded by a present signal           |
| 22     | The arms will never be down without the alarm                |
| 23     | The alarm will always if a train is present                  |
| 24     | A train must be present before departing                     |


