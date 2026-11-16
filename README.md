# Hidden Gems Finder

My app helps a gamer who wants something new decide which lesser-known games are worth buying by surfacing highly rated titles that relatively few people own.

> A course project for **MIST 4600: Computer Programming in Business** at the University of Georgia's Terry College of Business (Fall 2026).

## Problem
The user is a gamer looking for their next purchase who is tired of the same blockbusters every storefront pushes to the front. The hard part is finding games that are genuinely well liked but still under the radar, since popularity and quality often get tangled together, and then judging whether the price is a good deal. Storefront charts rank by sales and visibility, so the highly rated games that relatively few people own tend to stay buried.

## What it does
My app answers three questions:
1. **Which games are the gems?** Games with a high share of positive reviews but a low owner count.
2. **Which genres hide the most gems?** Grouping the gems by genre to see which categories are full of hidden value and which are mostly blockbusters.
3. **Are gems a better deal?** Comparing the average price of the gems against the most-owned games.

## Data
The [Steam Games Dataset](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset) on Kaggle, collected in March 2025. The dataset is shared under the MIT License by its creator, artermiloff. This repo uses `steam_games.csv`, a smaller file made for the course: the 1,000 games with the most reviews.

## Built with
- Python and pandas, in Google Colab
- The CheapShark
