# Web Scraping NFL Data
Code to scrape player statistics from NFL.com and resultant data

### Data Format

Player statistics are broken into two separate csv files, one file for Quarterback Stats and one for Reciever Stats.

#### Quarterback Stats - qb_data.csv

| Feature   | Expanded Feature Name   | Description                                 |
|-----------|-------------------------|---------------------------------------------|
| QB        | Player Name             | Name of the player                          |
| Team      | Player Team             | Team of the player                          |
| GP        | Games Played            | Number of games played in that season       |
| Year      | Season                  | Season year                                 |
| ATT(R)    | Rush Attempts           | Number of rushing attempts                  |
| YDS(R)    | Rush Yards              | Total rushing yards                         |
| YPC       | Yards per Carry         | Average yards per carry                     |
| TDs(R)    | Rushing Touchdowns      | Number of rushing touchdowns                |
| YDS       | Passing Yards           | Total passing yards                         |
| ATT       | Passing Attempts        | Number of passing attempts                  |
| YPA       | Yards per Attempt       | Average yards per passing attempt           |
| CMP       | Completed Passes        | Number of completed passes                  |
| TDs       | Passing Touchdowns      | Number of passing touchdowns                |
| INTs      | Interceptions           | Number of interceptions                     |
| QBR       | Rating                  | Quarterback rating                          |
| SCK       | Times Sacked            | Number of times the quarterback was sacked  |

#### Reciever Stats - wr_full.csv

| Feature   | Expanded Feature Name    | Description                                 |
|-----------|--------------------------|---------------------------------------------|
| Reciever  | Player Name              | Name of the player                          |
| Team      | Player Team              | Team of the player                          |
| Games     | Games Played             | Number of games played in that season       |
| Year      | Season                   | Season year                                 |
| Receptions| Receptions               | Number of receptions                        |
| REC_YDS   | Receiving Yards          | Total receiving yards                       |
| REC_TDS   | Receiving Touchdowns     | Total receiving touchdowns                  |
| REC_YAC   | Yards After Catch        | Receiving yards after the catch             |
| Targets   | Targets                  | Number of times targeted                    |


