# Natural Language Processing
Worked on building a model for DeFalco's restaurant.

The restaurant's menu includes an email address where visitors can give feedback about their food.

Createed a tool that automatically sends the manager all the negative reviews so he can fix them, while automatically sending all the positive reviews to the owner, so the manager can ask for a raise.

Built a model to distinguish positive reviews from negative reviews using Yelp reviews because these reviews include a rating with each review. The data consists of the text body of each review along with the star rating. Ratings with 1-2 stars count as "negative", and ratings with 4-5 stars are "positive". Ratings with 3 stars are "neutral" and have been dropped from the data.

Used this model to then appropriately flag emails.
