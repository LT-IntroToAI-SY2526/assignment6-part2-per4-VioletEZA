# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Square Feet
2. Bedrooms
3. Bathrooms
4. Least Important: Age

**Explanation:**

Square feet v price graph was very, very close to a proper linear relationship, then the bedrooms and bathrooms v. price graphs were relatively similar, then the age v. price graph was basically a scatter plot so there wasn't a strong relationship.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each additional 100,000 square feet increases the price by $25,000.

**Feature 2:**
Each additional bathroom increases the price by $87,000

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
R² = 0.9936
This tells me that 99.36% of the variation in house prices can be explained by the model's inputs. It's not 100% so yes there is room for improvement.



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Neigborhood violence issues

**Why it would help:**
If the house is located in an area with high rates of crime then it lowers the price a decent amount

**Feature 2:**
Number of trains/expressways nearby

**Why it would help:**
Loud noises typically drive away home owners because they don't aprecciate the noise

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

Our data didn't get to any of those points, however it did get decently close. So because of that, I may trust the model slightly but not definitively because there is a chance it could be wrong. 

