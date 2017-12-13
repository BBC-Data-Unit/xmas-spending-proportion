# 'I spend £400 on each of my five kids'

![](https://ichef.bbci.co.uk/news/624/cpsprodpb/14A40/production/_99144548_spendingchristmas_birmingham_qyno9-nc.png)

In December 2017 we helped do data analysis as part of radio 5Live's **James Graham** [report on the proportion of income being spent on Christmas by households in different parts of the country](http://www.bbc.co.uk/news/business-42299210).

The story was based on Centre for Retail Research (CRR) spending forecasts for Christmas, which needed to be matched with ONS regional income figures. However, whereas the CRR spending forecasts referred to *households*, the ONS "disposable income" (money left after tax and benefits are paid) was calculated per *head* or per *region*.

To make the figures compatible, we used the [total number of households by region for 2015](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/families/adhocs/005374totalnumberofhouseholdsbyregionandcountryoftheuk1996to2015) (the year covered by the disposable income figures).  

We then calculated the total after tax income per household by taking the total for the region and dividing it by the number of households.

We then divided this figure (total annual disposable income per household per region) by 12 to get a month's disposable income per household.

We then took the CRR figure on Christmas to calculate the % of a month's after tax/benefits income that goes on Christmas.

## Get the data

* CSV: [spending forecasts for Christmas](https://github.com/BBC-Data-Unit/xmas-spending-proportion/blob/master/spendingchristmas2015_CRR.csv) (Centre for Retail Research)
* ONS: [Gross disposable household income](https://www.ons.gov.uk/economy/regionalaccounts/grossdisposablehouseholdincome) - [cached here](https://github.com/BBC-Data-Unit/xmas-spending-proportion/blob/master/regionalgdhibyla.xls)
* ONS: [total number of households by region for 2015](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/families/adhocs/005374totalnumberofhouseholdsbyregionandcountryoftheuk1996to2015) - [cached here](https://github.com/BBC-Data-Unit/xmas-spending-proportion/blob/master/householdsbyregion1996to2016final.xls)

## Visualisation

* Bar chart: Spending per household on Christmas

## Related stories/repos

* [Is Christmas getting cheaper, or more expensive?](https://github.com/BBC-Data-Unit/christmas-dinner) (2015 and 2016)
* You can [find all Christmas-related stories from this account here](https://github.com/search?q=topic%3Achristmas+org%3ABBC-Data-Unit&type=Repositories)
