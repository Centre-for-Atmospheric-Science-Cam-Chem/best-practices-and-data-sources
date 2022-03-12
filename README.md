# best-practices-and-data-sources

## CMIP6 scenarios and emissions

The shared socio-economic pathway (SSP) greenhouse gas concentrations and their extensions to 2500 [Meinshausen et al.](https://doi.org/10.5194/gmd-13-3571-2020).

## Global weather via Meteostat
[Meteostat](https://meteostat.net/en) is an open access service which aggregates weather data from numerous global sources. They have a [Python library](https://dev.meteostat.net/python/#installation) for data access using Pandas.

## UK datasets

### London Air Quality Network (LAQN)
The LAQN is an air pollution monitoring network, with stations distributed across Greater London. The data feeds (open access) are currently managed by the Environmental Research Group at Imperial College London. 
- [LAQN data feeds landing page](https://www.londonair.org.uk/Londonair/API/), with links to [Help docs](http://api.erg.ic.ac.uk/AirQuality/Information/Documentation/pdf) and [APIs](http://api.erg.ic.ac.uk/AirQuality/help).
Individual datasets are also available download via the [website](https://www.londonair.org.uk/london/asp/datadownload.asp).

### UK regional daily mortality
Daily mortality data at the regional scale for England and Wales is publicly available via the Office for National Statistics (ONS) in multiple data releases, from 1981 onwards:
- [2015 - 2018](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/adhocs/11189dailydeathsenglishregionsandwales2015to2018occurrences) 
- [2013 - 2017](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/adhocs/009728dailydeathoccurrencesregionsofenglandandwales2013to2016) 
- [2015 - 2016](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/adhocs/009049dailydeathoccurrencesenglandandwales2015to2016) 
- [1981 - 2014](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/adhocs/005459dailydeathoccurrencesenglandregionsofenglandandwales1970to2014)

### UK household income by local authority
Annual gross disposable household income (GDHI) data is available at the local authority level, via the Office for National Statistics (ONS). Datasets are divided by region.
- [ONS data release](https://www.ons.gov.uk/economy/regionalaccounts/grossdisposablehouseholdincome/datasets/regionalgrossdisposablehouseholdincomebylocalauthoritiesbynuts1region)

Note:
- GDHI represents the amount of money available for spending or saving after payment of taxes and receipt of benefits.
- Estimates include effects of inflation (i.e. given in today's prices)
- GDHI represents all individuals in the household sector, not an average household or family unit (there are separate tables for total GDHI or per capita). 
- These datasets also include breakdowns of various components of GDHI.
