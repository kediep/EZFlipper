# EZ Flipper 

## Description
EZ Flipper is a program that scrapes a third party marketplace, 
[Grailed](https://www.grailed.com/), to find brand new items and compares the 
buying price to the average sale price of that same item on another reselling 
marketplace, [StockX](https://stockx.com/), to calculate the possible profit 
margins from flipping that item. The user gets to choose the minimum profit 
threshold by adjusting the variable 'min_profit' to determine which items are 
worth reselling. With millions of listings on Grailed, there's an abundance of 
hidden profitable items ready to be found and flipped. 

## Requirements
You must have the latest verion of Google Chrome and 
Python 3.8.5 (or higher). 

### macOS
When running for the first time, you may need to go to system preferences to 
allow chromedriver to run as a trusted executable.

## Instructions
0. Install all of the requirements listed above. 
1. Open your terminal and go to the directory you'd like to clone EZ Flipper.
2. Clone the repository by typing the following command into your terminal:  
	
		git clone https://github.com/kd24972/EZFlipper.git

3. Once you've successfully cloned the repository, go into it: 
	
		cd EZFlipper

4. Install the requirements to run EZ Flipper by typing in your terminal: 
	
		pip install -r requirements.txt

5. Open up EZFlipper.py and adjust the variables 'brands', 'min_profit', 
'max_age', and 'transaction_fee' to your preference and save it. 

6. Return to your terminal and run the script: 
	
		python EZFlipper.py > items.txt

7. Open items.txt to find all of the profitable items with their corresponding 
links ordered by descending profit.
