Problem Statement:

Kiva Zip (https://zip.kiva.org/) is a p2p crowdfunding platform that makes 0% interest rate loans to small business owners by connecting lenders and borrowers. I am planning to predict what factors help a crowdfunding campaign succeed (fully fundraise) on the Kiva Zip crowdfunding platform. So far, about 12,000 loans have been made, but ~250 have expired on the platform, which means the borrower did not reach the target amount and consequently did not get their loan disbursed.

What I have accomplished so far:

1) Scraped the Kiva website for data: scraped website for characteristics of 200+ U.S. based loans. E.g. Loan size, term, industry, duration of fundraising period, years of experience, purpose of loan, conversations with lenders, internet frequency of borrowers etc. The scraping code can be found in the notebook: scrape loans.ipynb and the dataset can be found in: scrape loans.ipynb

2) Preliminary exploratory analysis: Explored data to find featues that are relevant (e.g. industry, size of loan, term of loan, trustee, conversations etc.) This can be found in the notebook: kiva EDA _ Logistic Regression.ipynb

3) Logistic regression model: Predicts with 64% accuracy whether a loan will be successful vs. a null accuracy rate of 50%. Hoping to include more variables to increase accuracy. This can be found in the notebook: kiva EDA _ Logistic Regression.ipynb

3) Preliminary decision tree. This can be found in kiva Decision Tree.ipynb

What remains to be done: 

1) finish decision tree

2) Make visualizations and make them pretty 

3) Draw conclusions

4) Make slides 
