# Chemical Control Timing for Prevention of the Western Cherry Fruit Fly

## Background

The western cherry fruit fly is a key pest in all cherry growing regions of the western United States. The fly’s larva develops in ripening cherries. If uncontrolled, the pest can ruin almost all the fruit on a tree. Adults are weak migrators and will travel no further than necessary to find a host tree. For this reason, infestations in a region tend to be spotty. However, infestations within an orchard, where the trees are close together, can spread rapidly.

Timing of the first chemical control spray is based on the interval between emergence of the females and the first egg laying, usually 7 to 10 days. Because trapping flies in a commercial orchard is not a reliable way to determine the presence or emergence of the first fly, a degree model is helpful. This model uses a lower developmental threshold of 41 ºF, but no upper threshold. A degree-day look-up table for the western cherry fruit fly, based on daily maximum and minimum temperatures, is available. The table gives the relationship between the percentage of fly emergence and degree-days. First fly is expected at 950 degree-days after March 1. Chemical control sprays should be applied on or before 1060 degree-days to target mature, egg-laying flies. Sprays should be repeated every 10 to 21 days, depending on the residual activity of the product, to maintain residues high enough to kill adults before they lay eggs. Rain may reduce residues, requiring shorter intervals between sprays.

[Learn more about Western Cherry Fruit Fly prevention here.](http://treefruit.wsu.edu/crop-protection/opm/western-cherry-fruit-fly/)

## Contents

This package provides an algorithm for determination of the ideal time to apply chemical control measures to cherry trees according to the temperature history obtained from [Visual Crossing's Weather Data API](https://www.visualcrossing.com/). An API key can be obtained by creating an account with Visual Crossing (a free account will support individual use of this code). 

The notebook requires input of your zip code (myZipCode) and the Weather Data API key (myAPIKey). Each run will produce a file (weather.csv) containing weather data for the current year starting March 1. This data is used in conjunction with the degree-day lookup-table (WesternCherryFruitFly.csv) to calculate the total degree-days. The final cell in the notebook tells if it is time to apply the first chemical control spray.
