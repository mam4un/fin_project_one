# pseudo_code for the project
## this is a file that outlines th pseudo code for project one. 

# Step 1:
Investors profile assessment:
a. Age: Decleare age as a list of float values. 
b. Expected return: Decleare return as a list of float values (percentage). 
c. Risk preference: Decleare risk preference as a list of float values (percentage) [0+] 
d. investment tenure: Decleare tenure as a list of float values.
e. Investable amount ( we do not need it; we can assume a figure and convert the return in percentage)

## Determine the types of investors
Define a function / use conditions (if / elif/ else) statement that uses the above variables to determine the types of investors. 
- Risk lover
- risk neutral
- risk averse

# Step 2: Investment options
## Stocks from NYSE:
## Information needed: Use Alpaca API calling to get the data
- Price / daily return
- Industry / market return
- Calculated stock beta

## Use simple sharpe ratio to classify stocks into various group: use conditions (if / elif/ else) statement
- Sharpe ratio <1 is sub-optimal investment
- Sharpe ratio>1.0 & <2 is good investment
- Sharpe ratio>2.0 & <3 is very good investment
- Sharpe ratio>2.0 & <3 is very good investment

## Use beta to catagorize stock
- Aggressive vs defensive stocks

## Other investment option:
- Treasury securities / bonds
- Commodities - Gold

industry data: https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html

# Step 3: Generating profolio and determine the relevant characteristics
- Set a rule of stock holding: 15 to 20 securities
- Use sorting function to determine the candidate stock for portfolio given the invetors types determined in step 1. 
- Use random function to provide weight
- Determine portfolio risk and return
- Follow the steps mutliple times to develop a list of portfolio and their characterisitcs

# Step 4:
- Use simualtion to develop projected cummulative return and risk of the portfolio over a several given time horizon. 

# Step 5:
- Visualization. 

