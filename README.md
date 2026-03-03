# Task 2: Restaurant Recommendation System

## Objective
The goal of this task is to build a restaurant recommendation system that suggests restaurants based on user preferences, such as cuisine, price range, rating, and city. The system uses a content-based filtering approach to provide relevant recommendations.

---

## Approach & Steps

### Step 1: Data Preprocessing
- Loaded the dataset and explored the data to understand its structure.
- Selected the relevant columns: `Cuisines`, `Average Cost for two`, `Aggregate rating`, and `City`.
- Checked for missing values and removed any incomplete entries.
- Reset the index to ensure the dataset is clean and ready for analysis.

### Step 2: Defining User Preferences
- Determined the criteria for recommending restaurants:
  - Cuisine type (e.g., "North Indian", "Chinese", etc.)
  - Maximum budget for two people
  - Minimum restaurant rating
  - City of interest
- These preferences allow the system to filter restaurants according to individual user needs.

### Step 3: Recommendation Logic
- Applied a content-based filtering approach.
- Filtered the restaurants that matched all user-defined preferences.
- Returned the top recommended restaurants to the user for easy selection.

### Step 4: Testing the System
- Tested the system using different user preferences to ensure accurate recommendations.
- Verified that the recommendations were relevant and consistent with the chosen criteria.

---

## Visualizations & Charts

### Chart 1: Cuisine Distribution
- Purpose: To show the number of restaurants available for each cuisine.
- Insight: Identifies the most common cuisines in the dataset and highlights diversity.
- Steps:
  1. Counted the number of restaurants for each cuisine.
  2. Sorted the cuisines based on their frequency.
  3. Represented the results in a horizontal bar chart for clear visualization.

### Chart 2: Average Cost Distribution
- Purpose: To understand the price range of restaurants in the dataset.
- Insight: Shows how restaurant costs are distributed and helps identify budget-friendly options.
- Steps:
  1. Calculated the distribution of the "Average Cost for two" across all restaurants.
  2. Visualized the frequency of different cost ranges using a histogram.
  3. Added a density line to show the overall trend in pricing.

### Chart 3: Ratings vs Cost (Scatter Plot)
- Purpose: To explore the relationship between restaurant ratings and cost.
- Insight: Helps understand if higher-rated restaurants tend to be more expensive and highlights affordable high-rated options.
- Steps:
  1. Plotted restaurant ratings against their average cost.
  2. Used different colors to represent cuisines for better differentiation.
  3. Analyzed patterns to identify cost-effective, high-quality restaurants.

### Chart 4: Top Recommended Restaurants (Bar Chart)
- Purpose: To highlight the top recommended restaurants for a sample user based on preferences.
- Insight: Shows which restaurants meet the user’s criteria and have the highest ratings.
- Steps:
  1. Selected restaurants that match a specific user’s preferences.
  2. Sorted them by rating in descending order.
  3. Visualized the top recommendations using a horizontal bar chart to clearly communicate the best options.

---

## Outcome
- Successfully implemented a **content-based restaurant recommendation system**.
- Provided accurate and relevant recommendations based on user preferences.
- Created visualizations that offer insights into cuisine popularity, cost distribution, rating trends, and top recommended restaurants.
- Tested the system with multiple user scenarios to ensure reliability and quality of recommendations.

---



