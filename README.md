# NC redistricting analysis - 2023

To analyze the districts proposed by Republican state lawmakers in October 2023 for signs of partisan gerrymandering, The News & Observer used a technique featured prominently in multiple legal challenges to maps across the country, including in North Carolina.

The analysis compares the proposals to a set of 100,000 computer-generated maps created by a team of mathematicians at Duke University led by Jonathan Mattingly. All of the maps in this "ensemble" follow [neutral redistricting criteria](https://webservices.ncleg.gov/ViewDocSiteFile/38467) established by the legislature during the 2021 redistricting process.

For each of these maps, the analysis uses precinct-level vote totals from past elections and re-sorts them into the different districts, simulating outcomes under different scenarios. The method doesn't predict how maps will perform in the future. Instead, it uses actual election data from past races unaffected by gerrymandering – president or governor, for example – where all voters cast ballots for the same set of candidates.

By counting how many Republicans or Democrats are elected using each map and in each election, the analysis can show how often a given proposal lines up with what we'd expect from the collection of "fair" maps.

To test how resistant the map proposals are to changing political sentiment, the analysis also simulated the outcomes if the Democratic vote percentage gradually increased.

See below for a full breakdown of the findings, methodology and additional information on the N&O's coverage.

For additional reference information and data dictionaries, see the [technical reference readme](https://github.com/mtdukes/redistricting2023/blob/main/technical_reference.md).

## Ongoing coverage

Tracking stories from The N&O and The Charlotte Observer on 2023 redistricting in North Carolina.

* [Congressional map predicted to gain 3 GOP seats moves forward in NC legislature](https://www.newsobserver.com/news/politics-government/article280879883.html) // Kyle Ingram // Oct. 23, 2023
* [N&O analysis confirms aggressive gerrymandering in NC political maps](https://www.newsobserver.com/news/politics-government/article280259464.html) // Tyler Dukes // Oct. 23, 2023
* [Mecklenburg Democrat says ‘blatantly rigged’ redistricting may force her to move](https://www.newsobserver.com/news/politics-government/article280795615.html) // Mary Ramsey // Oct. 20, 2023
* [The Triangle’s swing district would be eliminated in GOP congressional maps](https://www.newsobserver.com/news/politics-government/article280695505.html) // Avi Bajpai // Oct. 19, 2023
* [Democrat says maps that ‘take a sledgehammer to Wake County’ may force her to move](https://www.newsobserver.com/news/politics-government/article280744220.html) // Avi Bajpai // Oct. 19, 2023
* [Republicans release new NC maps for 2024 likely to expand GOP power in Congress](https://www.newsobserver.com/news/politics-government/article280682515.html) // Kyle Ingram // Oct. 18, 2023
* [NC Rep. Tricia Cotham switched parties. Here are 2 possible routes for her political future](https://www.newsobserver.com/news/politics-government/article280698270.html) // Dawn Baumgartner Vaughan // Oct. 18, 2023
* [New NC maps draw Jeff Jackson out of a district, give Tim Moore a chance to run](https://www.newsobserver.com/news/politics-government/article280700850.html) // Danielle Battaglia // Oct. 18, 2023
* [Redistricting has started in NC. Wait, again? Here’s what to know.](https://www.newsobserver.com/news/politics-government/article279748284.html) // Kyle Ingram // Sept. 26, 2023
* [Podcast: Explore North Carolina’s long history of gerrymandering election maps
](https://www.newsobserver.com/news/politics-government/article254382498.html) // Tyler Dukes // Sept. 23, 2021

## Analysis of proposed 2023 maps
The following tables were generated using precinct-level vote totals for each election contest, mapped to corresponding Census blocks by the Duke Quantifying Gerrymandering team. By using block assignment files generated from maps by the N.C. General Assembly, we can tally the number of Democrats and Republicans who would be elected using the given district map plan under the conditions of a specific electoral contest (2020 president, 2016 governor, etc.).

The table includes the statewide Democratic vote total across all precincts, according to the data from Duke, as well as a comparison of the 2023 proposed maps and the final maps used in the 2022 election by court-ordered redraw.

### NC House
*[N.C. House Bill 898.](https://ncleg.gov/BillLookUp/2023/H898)*

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — there's a **7 to 10 seat** difference in favor of the GOP compared to the maps used in 2022. Compared to the most common results of the ensemble for those races, there's a **5 to 7** seat difference in favor of the the GOP.

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — the maps proposed by the N.C. General Assembly would elect **5 to 7** more Republicans than expected, based on a collection of 100,000 computer-generated maps provided by the Duke team.

|Contest & year                | Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| # of ensemble matches| Difference, 2022| Difference, ensemble|
|:-----------------------------|------------------:|---------------------:|-----------------:|----------------------:|---------------------:|----------------:|--------------------:|
|2012 governor                 |              44.13|                    38|                39|                     40|                  8825|               -1|                   -2|
|2020 agriculture commissioner |              46.15|                    43|                44|                     45|                 11739|               -1|                   -2|
|2016 lieutenant governor      |              46.59|                    46|                47|                     47|                 34489|               -1|                   -1|
|2016 U.S. Senate              |              46.98|                    46|                47|                     47|                 29043|               -1|                   -1|
|2020 treasurer                |              47.43|                    45|                49|                     47|                  6553|               -4|                   -2|
|2016 president                |              48.02|                    49|                52|                     50|                 13785|               -3|                   -1|
|2020 insurance commissioner   |              48.23|                    48|                53|                     51|                  2764|               -5|                   -3|
|2020 lieutenant governor      |              48.36|                    47|                54|                     52|                    12|               -7|                   -5|
|2012 president                |              48.92|                    44|                48|                     48|                    18|               -4|                   -4|
|2020 U.S. Senate              |              49.10|                    48|                56|                     55|                     0|               -8|                   -7|
|2014 U.S. Senate              |              49.17|                    47|                49|                     49|                  6858|               -2|                   -2|
|2020 labor commissioner       |              49.18|                    48|                56|                     55|                     0|               -8|                   -7|
|2020 president                |              49.32|                    50|                59|                     57|                     0|               -9|                   -7|
|2012 lieutenant governor      |              49.88|                    51|                53|                     53|                 11274|               -2|                   -2|
|2016 governor                 |              50.05|                    49|                54|                     54|                    53|               -5|                   -5|
|2008 president                |              50.11|                    47|                50|                     50|                   569|               -3|                   -3|
|2020 attorney general         |              50.13|                    49|                59|                     56|                     0|              -10|                   -7|
|2016 attorney general         |              50.20|                    49|                53|                     53|                   646|               -4|                   -4|
|2020 auditor                  |              50.88|                    52|                62|                     59|                     0|              -10|                   -7|
|2020 secretary of state       |              51.16|                    51|                61|                     60|                     0|              -10|                   -9|
|2012 insurance commissioner   |              51.82|                    55|                57|                     57|                 10161|               -2|                   -2|
|2020 governor                 |              52.29|                    55|                64|                     62|                     0|               -9|                   -7|
|2008 insurance commissioner   |              53.57|                    62|                65|                     66|                    55|               -3|                   -4|
|2012 secretary of state       |              53.74|                    58|                62|                     65|                     3|               -4|                   -7|
|2008 U.S. Senate              |              54.33|                    64|                70|                     70|                     1|               -6|                   -6|

![Proposed NC House map under various election conditions compared to the Duke ensemble](https://github.com/mtdukes/redistricting2023/blob/main/charts/gifs/nc_house_h898.gif)

### NC Senate
*[N.C. Senate Bill 758](https://ncleg.gov/BillLookUp/2023/S758)*

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — there's a **2 to 4 seat** difference in favor of GOP compared to the maps used in 2022.

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — the maps proposed by the N.C. General Assembly would elect **1 to 3** more Republicans than expected, based on a collection of 100,000 computer-generated maps provided by the Duke team.

|Contest & year                | Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| # of ensemble matches| Difference, 2022| Difference, ensemble|
|:-----------------------------|------------------:|---------------------:|-----------------:|----------------------:|---------------------:|----------------:|--------------------:|
|2012 governor                 |              44.13|                    17|                16|                     17|                 44287|                1|                    0|
|2020 agriculture commissioner |              46.15|                    17|                19|                     18|                  1170|               -2|                   -1|
|2016 lieutenant governor      |              46.59|                    19|                20|                     19|                 84981|               -1|                    0|
|2016 U.S. Senate              |              46.98|                    19|                20|                     20|                 42360|               -1|                   -1|
|2020 treasurer                |              47.43|                    17|                19|                     18|                  5632|               -2|                   -1|
|2016 president                |              48.02|                    19|                21|                     20|                    33|               -2|                   -1|
|2020 insurance commissioner   |              48.23|                    18|                20|                     20|                   276|               -2|                   -2|
|2020 lieutenant governor      |              48.36|                    17|                21|                     20|                     0|               -4|                   -3|
|2012 president                |              48.92|                    20|                21|                     20|                 82162|               -1|                    0|
|2020 U.S. Senate              |              49.10|                    18|                22|                     21|                     0|               -4|                   -3|
|2014 U.S. Senate              |              49.17|                    20|                20|                     21|                 40487|                0|                   -1|
|2020 labor commissioner       |              49.18|                    19|                23|                     23|                     0|               -4|                   -4|
|2020 president                |              49.32|                    19|                22|                     21|                    25|               -3|                   -2|
|2012 lieutenant governor      |              49.88|                    23|                22|                     22|                 12343|                1|                    1|
|2016 governor                 |              50.05|                    19|                23|                     23|                     0|               -4|                   -4|
|2008 president                |              50.11|                    20|                21|                     20|                 46175|               -1|                    0|
|2020 attorney general         |              50.13|                    20|                23|                     23|                     0|               -3|                   -3|
|2016 attorney general         |              50.20|                    19|                23|                     22|                  1065|               -4|                   -3|
|2020 auditor                  |              50.88|                    23|                26|                     25|                  4062|               -3|                   -2|
|2020 secretary of state       |              51.16|                    23|                26|                     25|                     0|               -3|                   -2|
|2012 insurance commissioner   |              51.82|                    23|                22|                     22|                 20917|                1|                    1|
|2020 governor                 |              52.29|                    23|                25|                     24|                 16452|               -2|                   -1|
|2008 insurance commissioner   |              53.57|                    26|                27|                     27|                 22785|               -1|                   -1|
|2012 secretary of state       |              53.74|                    26|                25|                     26|                 44260|                1|                    0|
|2008 U.S. Senate              |              54.33|                    26|                27|                     27|                 31654|               -1|                   -1|

![Proposed NC Senate map under various election conditions compared to the Duke ensemble](https://github.com/mtdukes/redistricting2023/blob/main/charts/gifs/nc_senate_s758.gif)

### US House
*[N.C. Senate Bill 756](https://ncleg.gov/BillLookUp/2023/S756)*

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — there's a **3 to 4 seat** difference in favor of GOP compared to the maps used in 2022.

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — the maps proposed by the N.C. General Assembly would elect **2 to 4** more Republicans than expected, based on a collection of 100,000 computer-generated maps provided by the Duke team.

|Contest & year                | Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| # of ensemble matches| Difference, 2022| Difference, ensemble|
|:-----------------------------|------------------:|---------------------:|-----------------:|----------------------:|---------------------:|----------------:|--------------------:|
|2012 governor                 |              44.13|                     3|                 4|                      4|                 27278|               -1|                   -1|
|2020 agriculture commissioner |              46.15|                     3|                 6|                      4|                 14575|               -3|                   -1|
|2016 lieutenant governor      |              46.59|                     3|                 5|                      5|                  1418|               -2|                   -2|
|2016 U.S. Senate              |              46.98|                     3|                 6|                      5|                  1731|               -3|                   -2|
|2020 treasurer                |              47.43|                     3|                 6|                      5|                  1002|               -3|                   -2|
|2016 president                |              48.02|                     3|                 6|                      5|                   214|               -3|                   -2|
|2020 insurance commissioner   |              48.23|                     3|                 6|                      5|                   291|               -3|                   -2|
|2020 lieutenant governor      |              48.36|                     3|                 6|                      5|                   465|               -3|                   -2|
|2012 president                |              48.92|                     3|                 6|                      6|                     6|               -3|                   -3|
|2020 U.S. Senate              |              49.10|                     3|                 7|                      6|                    61|               -4|                   -3|
|2014 U.S. Senate              |              49.17|                     3|                 6|                      6|                    83|               -3|                   -3|
|2020 labor commissioner       |              49.18|                     3|                 7|                      6|                    54|               -4|                   -3|
|2020 president                |              49.32|                     3|                 7|                      6|                    77|               -4|                   -3|
|2012 lieutenant governor      |              49.88|                     4|                 6|                      7|                    16|               -2|                   -3|
|2016 governor                 |              50.05|                     3|                 7|                      6|                     6|               -4|                   -3|
|2008 president                |              50.11|                     3|                 6|                      6|                     0|               -3|                   -3|
|2020 attorney general         |              50.13|                     3|                 7|                      6|                     6|               -4|                   -3|
|2016 attorney general         |              50.20|                     3|                 7|                      6|                     0|               -4|                   -3|
|2020 auditor                  |              50.88|                     3|                 7|                      7|                     0|               -4|                   -4|
|2020 secretary of state       |              51.16|                     3|                 7|                      7|                     0|               -4|                   -4|
|2012 insurance commissioner   |              51.82|                     5|                 9|                      8|                    51|               -4|                   -3|
|2020 governor                 |              52.29|                     3|                 7|                      7|                     0|               -4|                   -4|
|2008 insurance commissioner   |              53.57|                     9|                10|                     10|                 20715|               -1|                   -1|
|2012 secretary of state       |              53.74|                     6|                 9|                      9|                   110|               -3|                   -3|
|2008 U.S. Senate              |              54.33|                     9|                10|                     11|                  9510|               -1|                   -2|

![Proposed Congressional map (S756) under various election conditions compared to the Duke ensemble](https://github.com/mtdukes/redistricting2023/blob/main/charts/gifs/us_house_s756.gif)

*[N.C. Senate Bill 757](https://ncleg.gov/BillLookUp/2023/S757)*

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — there's a **2 to 3 seat** difference in favor of GOP compared to the maps used in 2022.

Under the conditions of the major general elections in 2020 — president, U.S. Senate, governor, lt. governor and attorney general — the maps proposed by the N.C. General Assembly would elect **1 to 3** more Republicans than expected, based on a collection of 100,000 computer-generated maps provided by the Duke team.

|Contest & year                | Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| # of ensemble matches| Difference, 2022| Difference, ensemble|
|:-----------------------------|------------------:|---------------------:|-----------------:|----------------------:|---------------------:|----------------:|--------------------:|
|2012 governor                 |              44.13|                     4|                 4|                      4|                 28710|                0|                    0|
|2020 agriculture commissioner |              46.15|                     3|                 6|                      4|                 14575|               -3|                   -1|
|2016 lieutenant governor      |              46.59|                     4|                 5|                      5|                 18684|               -1|                   -1|
|2016 U.S. Senate              |              46.98|                     4|                 6|                      5|                 20896|               -2|                   -1|
|2020 treasurer                |              47.43|                     4|                 6|                      5|                 22471|               -2|                   -1|
|2016 president                |              48.02|                     4|                 6|                      5|                  8516|               -2|                   -1|
|2020 insurance commissioner   |              48.23|                     4|                 6|                      5|                  8430|               -2|                   -1|
|2020 lieutenant governor      |              48.36|                     4|                 6|                      5|                 12103|               -2|                   -1|
|2012 president                |              48.92|                     4|                 6|                      6|                  1359|               -2|                   -2|
|2020 U.S. Senate              |              49.10|                     4|                 7|                      6|                  5004|               -3|                   -2|
|2014 U.S. Senate              |              49.17|                     4|                 6|                      6|                  4731|               -2|                   -2|
|2020 labor commissioner       |              49.18|                     4|                 7|                      6|                  3352|               -3|                   -2|
|2020 president                |              49.32|                     4|                 7|                      6|                  5248|               -3|                   -2|
|2012 lieutenant governor      |              49.88|                     4|                 6|                      7|                    16|               -2|                   -3|
|2016 governor                 |              50.05|                     4|                 7|                      6|                  1908|               -3|                   -2|
|2008 president                |              50.11|                     4|                 6|                      6|                   138|               -2|                   -2|
|2020 attorney general         |              50.13|                     4|                 7|                      6|                   833|               -3|                   -2|
|2016 attorney general         |              50.20|                     4|                 7|                      6|                   537|               -3|                   -2|
|2020 auditor                  |              50.88|                     4|                 7|                      7|                    77|               -3|                   -3|
|2020 secretary of state       |              51.16|                     4|                 7|                      7|                    32|               -3|                   -3|
|2012 insurance commissioner   |              51.82|                     4|                 9|                      8|                     0|               -5|                   -4|
|2020 governor                 |              52.29|                     4|                 7|                      7|                     0|               -3|                   -3|
|2008 insurance commissioner   |              53.57|                     8|                10|                     10|                  3449|               -2|                   -2|
|2012 secretary of state       |              53.74|                     6|                 9|                      9|                   110|               -3|                   -3|
|2008 U.S. Senate              |              54.33|                     9|                10|                     11|                  9510|               -1|                   -2|

![Proposed Congressional map (S757) under various election conditions compared to the Duke ensemble](https://github.com/mtdukes/redistricting2023/blob/main/charts/gifs/us_house_s757.gif)

## Uniform swing analysis - proposed maps
One technique used by political scientists and other map experts to gauge the responsiveness of redistricting proposals is to perform a [uniform swing analysis](https://en.wikipedia.org/wiki/Swing_(politics)). By gradually increasing the percentage of Democratic (or Republican) votes across all districts, we can simulate a shift in the political winds toward either party and determine how sharp a swing we'd need to see before changing the number of elected Democrats (or Republicans) under the conditions of a given election.

We can perform the same analysis for the maps in the ensemble to see how the political swings in the electorate under a proposed map compare to what's "normal." Here, we're simplifying the results of that analysis to include the number of Democrats elected in the largest number of maps in the ensemble, or mode, along with the percentage of maps in the ensemble that resulted in that number.

### N.C. House
*2020 presidential race with an incremental half-percentage point swing.*

Under the conditions of this election, the analysis shows Democrats would need a **5.1 point** swing to take the majority.

| Swing value| Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| % of ensemble, mode|
|-----------:|------------------:|---------------------:|-----------------:|----------------------:|-------------------:|
|         0.0|               49.3|                    50|                59|                     57|                35.3|
|         0.5|               49.8|                    50|                59|                     58|                41.4|
|         1.0|               50.3|                    50|                60|                     59|                39.1|
|         1.5|               50.8|                    51|                61|                     59|                43.3|
|         2.0|               51.3|                    51|                62|                     59|                35.7|
|         2.5|               51.8|                    52|                63|                     60|                33.6|
|         3.0|               52.3|                    52|                63|                     61|                32.8|
|         3.5|               52.8|                    54|                63|                     62|                31.3|
|         4.0|               53.3|                    58|                64|                     64|                31.7|
|         4.5|               53.8|                    59|                64|                     65|                32.4|
|         5.0|               54.3|                    60|                65|                     65|                32.1|

*2020 governor race with an incremental half-percentage point swing.*

Under the conditions of this election, the analysis shows Democrats would need a **1.4 point** swing to take the majority.

| Swing value| Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| % of ensemble, mode|
|-----------:|------------------:|---------------------:|-----------------:|----------------------:|-------------------:|
|         0.0|               52.3|                    55|                64|                     62|                28.3|
|         0.5|               52.8|                    56|                64|                     62|                31.4|
|         1.0|               53.3|                    58|                64|                     64|                29.5|
|         1.5|               53.8|                    61|                65|                     66|                30.5|
|         2.0|               54.3|                    65|                67|                     67|                29.9|
|         2.5|               54.8|                    65|                67|                     68|                32.6|
|         3.0|               55.3|                    68|                68|                     70|                29.1|
|         3.5|               55.8|                    69|                68|                     71|                31.3|
|         4.0|               56.3|                    71|                71|                     72|                35.8|
|         4.5|               56.8|                    73|                73|                     73|                36.4|
|         5.0|               57.3|                    73|                73|                     74|                36.1|

### N.C. Senate
*2020 presidential race with an incremental half-percentage point swing.*

Under the conditions of this election, the analysis shows Democrats would need a **5 point** swing to take the majority.

| Swing value| Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| % of ensemble, mode|
|-----------:|------------------:|---------------------:|-----------------:|----------------------:|-------------------:|
|         0.0|               49.3|                    19|                22|                     21|                43.9|
|         0.5|               49.8|                    20|                23|                     23|                45.0|
|         1.0|               50.3|                    21|                24|                     23|                49.3|
|         1.5|               50.8|                    21|                24|                     23|                49.9|
|         2.0|               51.3|                    21|                24|                     23|                50.0|
|         2.5|               51.8|                    21|                24|                     23|                49.9|
|         3.0|               52.3|                    22|                24|                     23|                49.8|
|         3.5|               52.8|                    23|                25|                     24|                48.1|
|         4.0|               53.3|                    23|                25|                     24|                45.9|
|         4.5|               53.8|                    25|                27|                     27|                61.4|
|         5.0|               54.3|                    25|                27|                     27|                58.8|

*2020 governor race with an incremental half-percentage point swing.*

Under the conditions of this election, the analysis shows Democrats would need a **2.4 point** swing to take the majority.

| Swing value| Statewide D vote %| D seats, proposed map| D seats, 2022 map| D seats, ensemble mode| % of ensemble, mode|
|-----------:|------------------:|---------------------:|-----------------:|----------------------:|-------------------:|
|         0.0|               52.3|                    23|                25|                     24|                48.2|
|         0.5|               52.8|                    24|                26|                     25|                47.4|
|         1.0|               53.3|                    24|                26|                     25|                46.1|
|         1.5|               53.8|                    24|                27|                     26|                44.2|
|         2.0|               54.3|                    24|                27|                     26|                41.3|
|         2.5|               54.8|                    26|                28|                     27|                58.7|
|         3.0|               55.3|                    26|                28|                     27|                52.6|
|         3.5|               55.8|                    27|                28|                     28|                44.0|
|         4.0|               56.3|                    27|                29|                     28|                44.7|
|         4.5|               56.8|                    28|                29|                     28|                44.3|
|         5.0|               57.3|                    28|                29|                     28|                38.4|

## Helpful links

* [2021 redistricting repo](https://github.com/mtdukes/redistricting2021)
* [Duke Quantifying Gerrymandering data repository](https://git.math.duke.edu/gitlab/gjh/redistricting2020results)
* [2022 precinct sort data](https://s3.amazonaws.com/dl.ncsbe.gov/ENRS/2022_11_08/results_precinct_sort/AllCounties.txt)
* [2021 N.C. Senate analysis by Duke](https://sites.duke.edu/quantifyinggerrymandering/files/2021/11/senateNCGAReport_comparison.pdf#page=3)
* [2021 N.C. House analysis by Duke](https://sites.duke.edu/quantifyinggerrymandering/files/2021/11/houseNCGAReport_Comparison.pdf#page=3)
* [2021 N.C. Congressional analysis by Duke](https://sites.duke.edu/quantifyinggerrymandering/files/2021/11/congressionalReport_Comparison.pdf#page=2)
* [2023 map proposal analysis](https://sites.duke.edu/quantifyinggerrymandering/2023/10/20/newly-proposed-nc-maps-are-more-gerrymandered-and-less-responsive-than-maps-struck-down-in-2021/)