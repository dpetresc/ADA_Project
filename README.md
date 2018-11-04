# Title

# Abstract
How the color of a book's cover could influence the rate ? This is the main question we will try to answer by investigating the Amazon Customer Reviews dataset. This dataset provides a huge amount of reviews from 1995 to 2015, so we will also try to find how the reviews evolve over time. 

# Research questions
- How has reviews evolved over time (from 1995 to 2015) ?
- How are the reviews different accross languages and country (5 countries) ?
- How the color of the book's cover influence the rating ?

# Dataset
DATA COLUMNS:
- marketplace: 2 letter country code of the marketplace where the review was written.
- customer_id: Random identifier that can be used to aggregate reviews written by a single author.
- review_id: The unique ID of the review.
- product_id: The unique Product ID the review pertains to. In the multilingual dataset the reviews for the same product in different countries can be grouped by the same product_id.
- product_parent: Random identifier that can be used to aggregate reviews for the same product.
- product_title: Title of the product.
- product_category: Broad product category that can be used to group reviews.
- star_rating: The 1-5 star rating of the review.
- helpful_votes: Number of helpful votes.
- total_votes: Number of total votes the review received.
- vine: Review was written as part of the Vine program.
- verified_purchase: The review is on a verified purchase.
- review_headline: The title of the review.
- review_body: The review text.
- review_date: The date the review was written.

# A list of internal milestones up until project milestone 2
- 05/11/2018 - 11/11/2018: Data collection and wrangling
- 12/11/2018 - 18/11/2018: Data analysis
- 19/11/2018 - 25/11/2018: Data Visualization

# Questions for TAa
The provided dataset does not seem to have image information for the cover. Do we missed it ? Should we merge with another dataset ?
