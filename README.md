# Playing-with-avocados
Avocados are a well known and much appreciated food, especially among millennials. A couple of years ago, a dataset appeared on Kaggle with a very specific challenge: to find the city in the U.S. where millennials could pay the least for their beloved avocados. So they could finally afford an apartment too, at least according to the author of the dataset. While such an analysis would also require some data about the U.S. housing market, it will still be fun to discover what secrets this famous “Avocado dataset” contains.

The code behind my results is divided in two Jupyter Notebooks:

– Playing with avocados, part 1- Exploratory Data Analysis

– Playing with avocados, part 2 – Mapping the change in average price

Before, going any further it is worth it to spend a few words on the content of the dataset. The dataset displays data from beginning 2015 until March 2018 on avocado prices and sales volume in several U.S. cities/areas. It was put together using data available on the website of the Hass Avocado Board, meaning it provides information concerning Hass avocados only. The dataset includes data on sales from different channels and the average price reported refers to a per unit cost (i.e. it is the price of a single avocado).

There are two main types of avocados, conventional and organic, and for each type we have data concerning the units sold for three sizes: small, medium and large avocados.

I wondered where to start from, so I began with something easy: what kind of avocado do consumers actually prefer? Unsurprisingly, very few choose the organic ones that sell on average 98% less. Among the conventional avocados, consumers are a bit indecisive between medium and large ones, although in the end they go for the medium.

After understanding that most people buy medium-size conventional avocados, the next step was for me to try to individuate some patterns in this behaviour. Apparently, consumers seem to have understood that the best moment for buying is February, but they also love it as a summer food – sales peak in June –. The cold season comes with an increase in average prices and a decrease in units sold. Shifting in preferences as well as lower availability of the products due to harvest times might play a role (i.e. Hass avocados are usually picked up in February).

As a last step, I decided to tackle the issue of the 2017’s avocado shortage. For those who are not frequent avocado buyers, you must know that due to a reduced harvest, in 2017 avocado prices had a sharp increase. In the U.S., the average price for conventional avocados saw an increase of 17%. The regions the most affected were New York, Hartford Springfield, Grand Rapids, Chicago, where average prices reached 1.6 USD. Data show that during the shortage, consumers started buying more conventional small-sized avocados possibly due to the lower purchasing power that did not allow them to enjoy medium-sized avocados anymore.

In conclusion, in order to enable everyone to see what the dataset can tell in terms of changes in the average price, I created an interactive map using the Mapbox API (see "Playing with avocados, part 2 – Mapping the change in average price"). 
