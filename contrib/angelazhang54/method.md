# Methodology 

For this research, I use data from the Federal Reserve's Survey and Diary of Consumer Payment Choice (SDCPC) from 2008 to 2024. I focus only on in-person payments under $25.

My main dependent variable is whether someone uses cash or card for a payment. For my independent variables, I look at transaction size, merchant acceptance of cash and/or card, and personal preferences of the respondents.

To analyze my data, I first look at how the percentage of cash vs. card payments changes over time from 2008 to 2024 and make a graph showing the overall percentage of cash vs. card payments each year. I then use a logistic regression to look at how each factor influences consumers' preferences for cash vs card. My main regression equation is Prob(Cash Payment) = β₀ + β₁(transaction size) + β₂(merchant acceptance) + β₃(personal preferences) + ε

I conduct my analysis and create visuals to depict my results using tools such as Pandas, Matplotlib, and Numpy in a Jupyter Notebook.
