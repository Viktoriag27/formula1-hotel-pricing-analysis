# Formula 1 Impact on Barcelona Hotel Prices

## Overview
Analysis of Formula 1's impact on Barcelona hotel prices using booking.com data, comparing with Lisbon as a control city. The study employs difference-in-differences (DiD) methodology and text mining techniques to examine price variations during the F1 event period (May 29 - June 2, 2025).

## Key Findings
- Barcelona hotels show significant price increases during F1 weekend
- Lower-rated hotels experience larger price jumps compared to higher-rated properties
- Each additional amenity correlates with €81.24 price increase
- Pre-event baseline shows Barcelona hotels €69.1 more expensive than Lisbon

## Methodology
- Difference-in-Differences (DiD) analysis
- Text mining of hotel descriptions
- Fixed effects regression models
- Heterogeneous treatment effects analysis

## Data Collection
- Primary data source: Booking.com
- Time periods: May 22-26 (control) and May 29-June 2 (treatment)
- Cities: Barcelona (treatment) and Lisbon (control)
- Features collected:
  - Hotel prices
  - Ratings
  - Amenities
  - Hotel descriptions

## Models
1. Impact of Treatment Period
2. Impact of Treatment City
3. Difference-in-Differences (DiD)
4. Fixed Effects Regression
5. Enhanced DiD with Amenities
6. Heterogeneous Treatment Effects

## Technologies Used
- Python
- Natural Language Processing
- Statistical Analysis
- Web Scraping

## Important Disclaimer
The dataset used in this analysis was obtained through web scraping of Booking.com on February 1, 2025. All regression results and econometric analyses are based on this specific dataset. To reproduce our exact findings:

1. Use the provided dataset files instead of running the scraping code
2. Begin analysis from the text processing stage

While the scraping code remains functional, running it will generate new data that may yield different regression results due to dynamic pricing and availability changes.

## Authors
- Viktoria Gagua <viktoria.gagua@bse.eu>
- Alejandro Delgado Tello <alejandro.delgado@bse.eu>
- Alex Malo <alex.malo@bse.eu>

## University
Barcelona School of Economics, February 2025
