# Zara Instagram Analysis

Using image analysis and text mining to predict engagement for Zara's Instagram page and generating actionable insights.

This project:
1. Scrapes Zara's Instagram page for images, captions, number of likes, and number of comments
2. Generates an engagement metric by weighting number of likes and number of comments
3. Uses Google Vision API to retrieve image labels for each image
4. Predicts engagement using Logistic Regression with image labels and caption words as the predictors
5. Performs topic modeling using Latent Dirichlet Allocation and examines topic differences between high and low engagement posts
6. Provides actionable insights for Zara to improve user engagement
