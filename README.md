<h1>Optimizing Pricing Strategy with Statistical Modeling – Big Mountain Ski Resort<h1>

  <h2>1. Problem Statement</h2>

Big Mountain Resort had just upgraded their facilities, adding a $1,540,000 chair lift. They wanted to ensure they were maximizing revenue and not underpricing tickets. They needed to understand customer preferences and determine how to optimize ticket pricing.

<h2>2. Data</h2>

The data used for this analysis consists of ticket pricing and customer features at Big Mountain Resort. It was cleaned and preprocessed for analysis to identify which factors influence ticket pricing.

<h2>3. Data Cleaning & EDA</h2>

The dataset required cleaning, which included:
- Fitlering down relevant data from a much larger set of many other ski resorts
- Restrucuring the sheet so the data is more easily digestible

### Exploratory Data Analysis (EDA)

Key features that influence ticket pricing include:
- Reliable snow terrain
- Night skiing
- Terrain parks
- Days open

I also decided to exclude weekday prices and focus on weekend pricing.

<h2>4. Modeling</h2>

In this project, I used a data-driven approach to predict how different features at Big Mountain Resort could impact ticket pricing. Rather than relying on advanced algorithms, I modeled ticket prices using simple delta adjustments to various features and analyzing the resulting changes in price.

### Key Steps:
1. **Ticket Price Prediction**: I first predicted the current ticket price for Big Mountain Resort using its existing features, and compared this predicted price to the actual price.

2. **Feature Modifications (Deltas)**: For each feature, I calculated the change (delta) that would occur if certain conditions were adjusted. For example, increasing or decreasing the number of runs or the vertical drop would modify the predicted ticket price. I applied these deltas and measured the effect on the ticket price.

3. **Scenario Analysis**: I tested multiple business scenarios by adjusting the features. For example, in Scenario 1, I simulated the effect of closing up to 10 of the least used runs. The results showed how the price would decrease as more runs were closed.

4. **Revenue Impact**: I calculated the potential impact on revenue by applying the predicted price changes to the expected number of visitors (350,000) and their average number of ski days (5 days per visitor).

5. **Example Scenarios**: Below are the results from testing some key scenarios:
    - **Scenario 1**: Closing 1 to 10 of the least used runs showed minimal price impact, but closing more than 6 runs resulted in a larger drop in ticket price and revenue.
    - **Scenario 2**: Adding 150 feet to the vertical drop and installing an additional chair lift increased ticket price by $1.99, leading to a revenue increase of approximately $3.47 million.
    - **Scenario 3**: Adding 2 acres of snowmaking did not significantly impact the price or revenue.
    - **Scenario 4**: Increasing the longest run by 0.2 miles and adding 4 acres of snowmaking had no effect on the ticket price.

6. **Results Interpretation**: Based on the modeling, Big Mountain Resort could support a higher ticket price, potentially increasing it to $95.87 from the current $81. This increase could generate substantial additional revenue, which would easily offset the new $1.54 million operating cost of the new chairlift.

<h2>5. Business Implications & Recommendations</h2>

- **Price Adjustment**: I recommend increasing the ticket price from $81 to $95.87 to better align with the market and compensate for additional operational costs.
- **Scenario Testing**: Further analysis could be done to evaluate the potential impact of closing runs or making snowmaking improvements, but the findings suggest that the most effective changes would likely be related to infrastructure enhancements such as adding vertical drop or new lifts.

<h2>6. Future Work</h2>

Future work could explore the impact of adding more data, such as customer preferences and operating costs, to refine the predictions further. Additionally, further testing could be done to evaluate the business's ability to close underutilized runs without damaging customer experience.
