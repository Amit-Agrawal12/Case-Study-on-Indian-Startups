# Case-Study-on-Indian-Startups
Helping My Friend to get funding for his New Startup
QUESTION 1
1. The code reads a CSV file containing startup funding data and performs data manipulations 
using the pandas library.
2. It standardizes city names and extracts valid city names from the "CityLocation" column, 
focusing on specific locations: Bangalore, Mumbai, and NCR (New Delhi, Gurgaon, and Noida).
3. The code then counts the occurrences of each city and stores the results in a variable.
4. It prints the top three cities with the highest investment counts.
5. Finally, the code plots a bar graph to visualize the number of investments received by each 
location, allowing for a quick comparison of funding activity among the cities.


QUESTION 2
1. The code reads a CSV file containing startup funding data and performs data manipulations 
using the pandas library.
2. It focuses on the "InvestorsName" column and drops rows where this column is missing using 
the `dropna()` function.
3. The code then counts the occurrences of each investor and stores the results in a dictionary, 
considering multiple investors per startup.
4. It identifies the top 5 investors with the highest investment counts and stores their names and 
counts in separate lists.
5. Finally, the code plots a bar graph to visualize the investment counts for the top 5 investors, 
providing a quick overview of their investment activity.


QUESTION 3
1. The code reads a CSV file containing startup funding data and performs data manipulations 
using the pandas library.
2. It focuses on the "InvestmentType" and "InvestorsName" columns and drops rows where these 
columns are missing using the `dropna()` function.
3. The code standardizes the names of important startups (Ola Cabs, Flipkart.com, Oyo Rooms, 
Paytm Marketplace) by replacing variations with the correct names using the `replace()` 
function.
4. It creates a dictionary `d` to store the investors and the distinct startups they have invested in. 
It iterates through each row, splitting the investors' names by commas, and checks if the investor 
has already invested in the current startup. If not, it adds the startup name to the investor's list of 
investments in the dictionary.
5. The code then creates a dictionary `new` to store the count of distinct startups each investor 
has invested in. It iterates through the investors in `d`, checks for empty names, and adds the 
investor and the count of distinct startups to the dictionary. It sorts the `new` dictionary and 
retrieves the top 5 investors who have invested in different companies.
6. It initializes two lists to store the top investor names and their corresponding investment 
counts. The code iterates through the top 5 investors, appends their names and counts to the 
respective lists, and prints the results.
7. Finally, the code plots a bar graph using `plt.bar()` to visualize the investment counts for the 
top 5 investors in distinct companies, providing insights into their investment activity.


QUESTION 4
1. The code filters the startup funding data based on the investment types "Crowd Funding" and 
"Seed Funding" and corrects the spelling variations in the investment type column.
2. It corrects the spelling variations in important startup names such as "Ola Cabs," 
"Flipkart.com," "Oyo Rooms," and "Paytm Marketplace" to ensure accurate matching.
3. The code creates a dictionary to store the distinct startups each investor has invested in, 
considering multiple investors per startup.
4. It identifies the top 5 investors who have invested in the maximum number of different 
startups, excluding cases such as "Undisclosed Investors" or empty investor names.
5. Finally, the code generates a bar graph visualizing the investment counts for the top 5 
investors in distinct companies, specifically in the investment types of Crowdfunding or Seed 
Funding, assisting in the search for suitable investors for your friend's startup.


Question 5
1. The code reads a CSV file containing startup funding data and creates a copy of the 
DataFrame for data manipulation.
2. It filters the DataFrame based on the investment type "Private Equity" and corrects spelling 
variations in the investment type column.
3. The code corrects spelling variations in important startup names such as "Ola Cabs," 
"Flipkart.com," "Oyo Rooms," and "Paytm Marketplace" to ensure accurate matching.
4. It creates a dictionary to store the distinct startups each investor has invested in, considering 
multiple investors per startup, specifically for the investment type of Private Equity.
5. The code identifies the top 5 investors who have invested in the maximum number of different 
startups in the Private Equity category, excluding cases such as "Undisclosed Investors" or 
empty investor names. It generates a bar graph displaying the investment counts for these top 
investors, aiding in the search for potential new investors for your friend's startup.
