Note that all the data used for experimentation is synthetic and gotten from random simulation in R. Feel free to look through the report. 

# Experimentation Projects (A/B-Testing)
Contains various projects ranging from beginner to advanced level experimentation techniques

## Stitch Fix Experimentation
Conducted A/B test to find the best algorithm between human and machine learning stylist that minimize the time it takes for a user to submit their cloth preferences and getting them delivered.
Utilized Bonferroni, Sidak, Holm’s test and discovered that clothes recommended by humans had the lowest time.

## Twitter A/B Testing
Ran multiple experiments to find which ad type (Video, Image, Text) maximizes user engagement in Twitter
Utilized Latin Square Designs to investigate the effects of ad type while controlling for user’s relationship with advertisers and discovered that Video tweets maximized engagement score

## Wish Experimentation
The goal of the project was to find what combination of discount duration and discount amount would lead to higher number of browsers (who surf the Wish website but don't buy) to purchaser. Discovered that 15% discount rate with 15 minutes of discount duration led to highest conversion metric.

## Netflix Homepage Optimization Experimentation
The aim was to find what factors among tile size (ratio of the tile’s height to the overall height), match score (prediction of how likely one will enjoy watching a movie/show based on their viewing history) and preview length (duration of show/movie’s preview in seconds) minimizes the average browsing time. Factor screening and response optimization (method of steepest descent, curvature test) follwed by central composite design were conducted to find the most optimal factors and region that mimimized the browsing time.
