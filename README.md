# latitude-coding-challenge

### The following text is a copy of an email I received regarding the coding test.

Thanks for the chat just now and agreeing to the next step in our recruitment process! We’re excited about building this new squad and would love you to be a part of it. 

Please complete the coding challenge within the next 3-5 days and return via email in a GitHub repo (preferred) or ZIP File. We’ll have your coding challenge reviewed by the engineering team and let you know next steps. If you’re not successful, we’ll let you know.

This coding challenge is as much about clean code as it is about problem solving. Best of luck please let me know if you have any questions!

Suppose we could access yesterday's stock prices as a list, where:

    The indices are the time in minutes past trade opening time, which was 10:00am local time.
    The values are the price in dollars of the stock at that time.
    So if the stock cost $5 at 11:00am, stock_prices_yesterday[60] = 5.

Write an efficient function that takes an array of stock prices and returns the best profit could have been made from 1 purchase and 1 sale of 1 stock.

For example:

	int[] stockPrices = {10, 7, 5, 8, 11, 9};

	Assert.assertEquals (6, getMaxProfit(stockPrices)); // returns 6 (buy at $5 sell

You must buy before you sell. You may not buy and sell in the same time step (at least 1 minute must pass).

Expectations

- Implement a solution in Java.
- Prove it works by creating unit tests that test the possible scenarios that the numbers could present.
- Include any comments that you think will be relevant to provide any context around the approach taken / solution developed.
- We prefer the response as a Git repo or ZIP File.
- Once you have completed the challenge it will be reviewed and next steps discussed. If you are unsuccessful, you will receive feedback as to why
