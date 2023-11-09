# Greater Manchester JD Wetherspoons Pubs Reviews Dataset

## Overview
This repository contains a dataset of reviews for 24 JD Wetherspoons pubs located in Greater Manchester. The reviews were collected to support academic research in sentiment analysis and topic modeling as part of coursework assessments.

## Data Collection
The data was manually scraped using a custom script, which is available in a separate [repository](https://github.com/timadeg/google-map-reviews-scraper). Alongside the textual reviews, images were also scraped with the intention of training an image classifier specifically for JD Wetherspoon (JDW) establishments.

## Dataset Details
The dataset includes the following fields:
- Reviewer Name
- Review Date
- Star Rating
- Review Text
- Total Reviews by Reviewer
- Total Photos by Reviewer
- Is Local Guide
- Number of Images
- Image URLs
- Price per Person
- Food Rating
- Service Rating
- Atmosphere Rating
- Recommended Dishes
- Pub Name

Each file corresponds to a different pub and includes the above-mentioned fields.

## Usage
This dataset is intended for academic purposes, specifically for conducting sentiment analysis and topic modeling as part of coursework. If you intend to use this dataset for other purposes, please ensure to credit the original source and adhere to the licensing terms which can be found in the LICENSE file.

## Repository Structure
- `/data` - Contains the CSV files with the reviews for each pub.
- `/images` - Contains the images scraped from the reviews.

## Related Work
The scraping script used to collect this dataset can be found in my other GitHub repository: [google-map-reviews-scraper](https://github.com/timadeg/google-map-reviews-scraper).

## Contact
For any additional questions or requests regarding this dataset, please open an issue in this repository or contact me directly through GitHub.
