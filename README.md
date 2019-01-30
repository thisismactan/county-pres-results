It's a testament to how embarrassingly behind American elections officials are when it comes to data maintenance that it's nearly impossible to find a free, centralized, clean, and accurate source of presidential election data at the county level. The data are available in bits and pieces around the Internet on Wikipedia and state secretaries of states' websites, as well as the wonderful [OpenElections Project](https://github.com/openelections), but so far as I can tell there is no single, easily accessible dataset that does the simple job of showing vote totals for the two major-party candidates in each county in 2012 and 2016.

(Caveat: there is one. But there are large discrepancies, with the national vote totals for 2012 and 2016 being off by millions of votes.)

None, that is, until now. This dataset, which I've put together using a combination of Wikipedia tables and data from the aforementioned OpenElections Project, is not guaranteed to be 100% accurate, either. But it is very, very close. The national vote totals in this dataset are within 10,000 votes of the correct national vote totals for both major parties in both elections covered, and in the vast majority of states the numbers are dead on; furthermore, some of these discrepancies are due to how different states treat overseas ballots or write-in votes. Any discrepancies are likely to be indistinguishable from statistical noise. 

Note: Some counties and county-equivalents saw their names changed between 2012 and 2016. The dataset uses the contemporaneous names but keeps the FIPS code as of 2016 for consistency with shapefiles and other datasets which use FIPS code as a key.
