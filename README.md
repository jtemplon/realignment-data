# College Basketball Realignment Data

This is all the data that was used in NYC Buckets' college basketball realignment week that ran from May 8-12, 2017. The data is being provided here in case people want to try doing their own analysis. I'm not providing the cluster analysis that was done to create the final conferences in [`results`](https://github.com/jtemplon/realignment-data/blob/master/results) because the K-Means clustering that was used can result in random states and ends up being more confusing than helpful in my experience.

## Raw

The [raw](https://github.com/jtemplon/realignment-data/blob/master/raw) data collected from various sources.

- `average_attendance.csv`: Collected by parsing PDFs that the NCAA puts out, the average attendance for each home game for each team from 2013-14 through 2015-16.
- `Expenses_All_Sports_and_Men's_Women's_and_Coed_Teams_2015.csv`: The total expenses for all sports for each school in the U.S. Department of Education Equities in Athletics data.
- `Sport_Data_2015.csv`: Men's basketball expenses for each school in the U.S. Department of Education Equities in Athletics data.
- `locations.csv`: The location is each school. This was found on the web and turned into a CSV. There's no guarantee that every school is 100% correct.

*Please note:* The Equities in Athletics datasets do not include data about Air Force, Army or Navy.

## Clean

The datasets described above that have been cleaned and given a canonical UNITID, which was originally created in the Equities in Athletics data. The expenses have been combined into one dataset: `expenses.csv`. In addition [this folder](https://github.com/jtemplon/realignment-data/blob/master/clean) contains a `usnews.csv`, which was collected by hand from the U.S. News website.

## Results

The [results](https://github.com/jtemplon/realignment-data/blob/master/results) of my clustering analysis on May 2, 2017, which is what the series of posts were based upon.

## Links

- Introduction: http://www.nycbuckets.com/2017/05/realignment-week-explainer/
- Conferences 32-27: http://www.nycbuckets.com/2017/05/realignment-conferences-32-through-27/
- Conferences 26-24: http://www.nycbuckets.com/2017/05/realignment-conferences-26-through-24/
- Conferences 23-18: http://www.nycbuckets.com/2017/05/realignment-conferences-23-through-18/
- Conferences 17-13: http://www.nycbuckets.com/2017/05/realignment-conferences-17-through-13/
- Conferences 12-8: http://www.nycbuckets.com/2017/05/realignment-conferences-12-through-8/
- Conferences 7-1: http://www.nycbuckets.com/2017/05/realignment-conferences-7-through-1/

## Questions?

Email nycbuckets@gmail.com