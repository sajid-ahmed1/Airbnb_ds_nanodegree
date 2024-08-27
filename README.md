# Airbnb Data Scientist Nanodegree

## Motivation

The motivation for this topic and dataset was due to the increasing pressure on first time home buyers living in London. In recent years, the housing market has balooned with once fair house valutions has been scrapped for inflated values. I was curious to find out if Airbnb is a small hack to produce some extra cash flow to a already tight homeowners pocket. By listing your spare room or property while you are away, it gives the chance to those interested in purchasing a home to make money monthly additional income to a very heavy liabilitiy. I look through the London Airbnb dataset that was scrapped off the website by InsideAirbnb (more information here: https://insideairbnb.com/about/). The data was last scrapped on the 16th of June 2024.
I have also posted a medium article about my findings here: https://medium.com/@caesura-oilers0y/how-to-upsell-your-airbnb-listing-8d17b10a7023

## Findings
For this assignment, I have chosen three business questions I feel are relevant and slightly challenging to the dataset. I have put myself into three business stakeholders who would be interested in this dataset.

1. As a property investor, I want to know which areas in London that have the most demand and what room types.
2. As an existing Airbnb host, I want to know if there are keywords in the list description that leads to higher reviews or prices.
3. As a landlord, I want to know what's the estimated daily price that my property can achieve.

From my findings, I have found that Westiminster is the most popular location for Airbnb listings in London with Tower Hamelts and Kensington & Chelsea. The most popular room type is entire home/apartment. Both Westminster and entire home/apartment is no surprise as Westminster is a walkable distance away from London's top attractions. Moreover, I had a look at the most common words used in the listing description and found the location 'London' and 'walk' to be the top 2 most used words. As an Airbnb host, looking to have potential customers, having these words entices the customer to book to the stay may result in higher review rating due to the accuracy and expectation you set in the listing. There was no indication from the charts to say if these words result to higher prices. Lastly, I looked at a linear model to predict the Airbnb listing price for a given property. After testing the model, it turned out a linear model did not work and a non-linear model should be used. The final model explained about 72% of the variance but can be tweaked further to produce better results.

## Libraries Used

- **Data Manipulation and Analysis:**
  - pandas
  - numpy
  - folium

- **Machine Learning:**
  - scikit-learn (sklearn)

- **Natural Language Processing:**
  - nltk

- **Data Visualization:**
  - matplotlib
  - seaborn

- **Other:**
  - warnings
 
## Files within repository

- **Airbnb.ipynb**
  - This is where the code is stored with the markdown text to explain each graph and my understanding/thoughts. I have a section that is code within a markdown text to prevent slowdown as it is not essential to      answering the business question.
- **airbnb_listings_london**
  - From the markdown code, it generates a html file which shows a map of all the airbnb listings around London.

## Licensing, Authors and Acknowledgement

- **Data Source**
  - [InsideAirbnb ](https://insideairbnb.com/about/)
- **Acknowledgements**
  - Murray Cox. Murray is a community artist and activist who uses data, media and technology for social change. He is the founder and current chief data activist of      Inside Airbnb.
- **License**
- MIT License

Copyright (c) [2024] [Sajid Ahmed]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
