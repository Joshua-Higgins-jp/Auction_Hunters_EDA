# **Auction Hunters**
## Exploratory Data Analysis
#### Joshua Higgins | March~ 2023

## Project Stages (Click to see)
* [Data Collection and Cleaning](https://github.com/Joshua-Higgins-jp/Auction_Hunters_EDA/blob/master/auction_hunters_preprocessing.ipynb)
   * Web Scraping / API
   * Data Extraction
   * Data Formatting
   * Data Validation
* [Explorative Data Analysis](https://github.com/Joshua-Higgins-jp/Auction_Hunters_EDA/blob/master/auction_hunters_eda.ipynb)
   * Financial Analysis
   * Location Analysis
   * Seasonal Analysis
   * Rating Analysis
   * Data Visualisation
   
* BONUS? Sentiment analysis and rating/profit prediction?? 

## What is *Auction Hunters*?
* Auction hunters is a TV show that aired in the USA from 2010-2015. Hosts Allen and Ton travel and bid for abandoned storage units. Each episode features their location, what storage units they bid for, how much they win or lose them for, and also chronicles the most exciting items found in each won unit and shows the people buying them, often with a demonstration.
* In each episode, they find buyers for the most profitable items in the storage units they bid on and won.
* The show reports how much each item was sold for, allowing the viewer to keep a tally of their profit for each unit.
* In addition to financial data, we also know where they are and thus can monitor location.
* For more information, check out: https://www.imdb.com/title/tt1742340/

<img src="https://m.media-amazon.com/images/M/MV5BNTc4OTE0MzcxOF5BMl5BanBnXkFtZTcwMjQ0NTM0Ng@@._V1_FMjpg_UX558_.jpg" alt="Hosts Allen and Ton of Auction Hunters">

# 📦 **Introduction to Storage Unit Auctions:** 
* There are businesses which allow people to rent storage units so that they can keep their belongings in it for a fee.
   * It's like having an offsite garage for your personal items that you cannot keep at home.
* If a customer stops paying their unit fee, the company owning the storage unit can auction off the contents to empty it and allow a new customer to use the storage unit space.
* Some people make a living off of buying these "abandoned" storage units and then selling the contents for a profit.
* Before buying an "abandoned" storage unit, potential buyers are not allowed inside the unit.
   * This is referred to as an eyes only inspection.
   * Potential buyers can only see from the open door what is inside. 
   * However, utilities such as torches and binoculars are allowed to get a "better view".
* There is a risk that a purchsed unit which appeared valuable, may actually have nothing of value, rendering the purchase of the unit a loss in time, bid and dumping fee.
* However, for experienced people with connections to the right buyers, they can turn a hundred dollar purchase into thousands of dollars worth of sales and profits. This is the attraction and interest value of the show "Auction Hunters".
* Deciding how much to bid for a unit, including the critical maximum bid, comes down to "profiling" the unit:
   * e.g. what the contents are or appear to be, how the contents are stored (wrapped, protected, in a gun case, a safe, car cover, nothing etc), and knowledge of the used resale value of appealing visible and potential items.
   * A potential buyer won't have time to research the resale value of items during profiling, so a successful _Auction Hunter_ must have experience in identifying and valuing used goods in order to profit from a purchase.