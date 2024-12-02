Introduction

Advani company has created their own platform for displaying various stocks from NSE and BSE exchange and also from various sectors.

Array of stocks: https://gist.github.com/imrhlrvndrn/3d06ab8a7e06e45b610248c71d783638

They need someone to help them display the stocks sorted in the following parameters:
Price
Growth

So, we need to use our Sorting and Filtering methods to display the stocks as per user actions.

Instructions

Make sure you return the JSON of stocks in the format res.json({ stocks: sortedStocks }) where sortedStocks is the variable name used to store the result

Before declaring the API Endpoints, make sure you import cors to the code.

Note: Don’t forget to add:

let cors = require('cors');

app.use(cors());

Step 1: Display all the stocks so that when you click “Load Stocks”, all the stocks are displayed first.

Now, follow the various endpoints that you need to create to get the desired results.

Once done, test your implemented code on the frontend here: https://bd2-stock-listing.vercel.app/

What are the various Actions and Consequences a user has to undergo?

Select the following sorting options and see the stocks getting sorted:
Pricing
Growth

Select any filter based on the Exchange:
NSE
BSE

Select any filter based on the industrial sector:
Finance
Pharma
Power

The stocks are listed based on the filters applied.