Paris AirBnB Market Analysis: Pricing, Capacity, and Regulatory Impact

Project Overview

This project presents an Exploratory Data Analysis (EDA) of AirBnB listings in Paris, France, focusing on understanding key market dynamics from 2008 to 2022. The analysis primarily investigates:

Geographical pricing disparities across Paris neighborhoods.

The relationship between listing accommodation capacity and average price.

The temporal trends of new host entry and average listing prices, particularly assessing the potential impact of 2015 regulatory changes.

This analysis provides insights for potential hosts, travelers, and policymakers interested in the Paris short-term rental market.

📊 Key Findings & Insights

The following are the core insights derived from the analysis, directly corresponding to the provided visualizations:

Insight 1: Significant Price Variation Across Paris Neighborhoods

Finding: There's a stark difference in average listing prices across Paris. The Elysee neighborhood (8th Arrondissement) consistently commands the highest average price per night (over €200), closely followed by Louvre (1st Arrondissement) and Passy (16th Arrondissement). In contrast, areas like Menilmontant (20th Arrondissement) and Buttes-Chaumont (19th Arrondissement) offer significantly lower average prices (around €75-€80).

Implication: Location remains the paramount factor for pricing strategy in the Paris AirBnB market, with central, tourist-heavy, and upscale arrondissements demanding a substantial premium.

![Visual](https://github.com/riyasha-gif/Paris-AirBnB-Listing-Analysis/blob/main/Insight%201.jpg) 
(Horizontal bar chart: Average Listing Price by Paris Neighbourhood)

Insight 2: Price Escalates with Accommodation Capacity

Finding: Across Paris, the average listing price shows a strong positive correlation with the number of people a property can accommodate. While 1-person accommodations are the cheapest (under €100), listings for 14, 13, 11, or 16 people reach the highest price points, nearing €1000 per night.

Implication: Larger listings, catering to bigger groups or families, represent the highest revenue-generating opportunities for hosts in the Parisian market. This suggests a strong demand for group travel accommodations.

![insight_2](https://github.com/riyasha-gif/Paris-AirBnB-Listing-Analysis/blob/main/Insight%202.jpg) 

(Horizontal bar chart: Average Listing Price by Accommodation Number)

Insight 3: The 2015 Regulations and Their Divergent Impact on Hosts vs. Prices

Finding:

New Host Entry (Orange Line): The number of new hosts entering the Paris AirBnB market peaked dramatically in 2015 and 2016. Following this peak, there was a sharp and sustained decline in new host registrations in subsequent years (2017-2022). This suggests the 2015 regulations, or market saturation, significantly slowed down new supply.

Average Price (Blue Line): The average AirBnB price in Paris shows volatility but generally maintained a relatively high level. Critically, after the 2015-2016 period, while new host entry plunged, the average price did not crash, instead showing fluctuations but largely sustaining its value (e.g., around €100-€140 in later years).

Implication: The 2015 regulations appear to have been effective in curtailing the growth of new listings (supply-side control). However, this reduction in new supply did not necessarily lead to lower prices for consumers, as demand likely remained strong, allowing existing listings to maintain their pricing.

![Visual](https://github.com/riyasha-gif/Paris-AirBnB-Listing-Analysis/blob/main/Insight%205.png) 

(Dual-axis line chart: New AirBnB Hosts vs. Average Price in Paris Over Time)

🛠️ Technical Stack

Language: Python

Libraries:

Pandas for data loading, cleaning, and manipulation.

Matplotlib, Seaborn for data visualization.

Jupyter Notebook for reproducible analysis and documentation.

📂 Repository Structure

paris_airbnb_analysis.ipynb: The main Jupyter Notebook containing all data cleaning, processing, EDA, and visualization code.

Insight 1.jpg, Insight 2.jpg, Insight 5.png: Exported image files corresponding to the core findings.

README.md: This document.

🚀 How to Run the Analysis

To reproduce this analysis locally, please follow these steps:

Clone the Repository:

git clone [https://github.com/riyasha-gif/paris-airbnb-listing-analysis.git](https://github.com/riyasha-gif/paris-airbnb-listing-analysis.git)


Install Dependencies: If you are not using an Anaconda environment that already has these, install the required libraries:

pip install pandas matplotlib


Launch Jupyter Notebook (via Anaconda):

Method 1: Anaconda Navigator

Open the Anaconda Navigator application.

Navigate to the directory where you cloned the repository.

Launch Jupyter Notebook from the main dashboard.

Method 2: Anaconda Prompt/Terminal

Open your Anaconda Prompt (Windows) or Terminal (Mac/Linux).

Change directory to the cloned repository folder:

cd path/to/paris-airbnb-listing-analysis


Launch the notebook server:

jupyter notebook


Open Notebook: Once the browser window opens, click on the paris_airbnb_analysis.ipynb file and run the cells sequentially to execute the EDA and generate the visuals.

