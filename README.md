# Analise_WeRateDogs

Analise_WeRateDogs is a project created in Jupyter Notebooks, developed for Udacity's Data Analytic Fundamentals Nanodegree program.

This project presents the work of data wrangling and exploratory data analysis of different datasets from WeRateDogs' [@dog_rates](twitter.com/dog_rates) Twitter account. This account rates images of dogs as well as adding funny pavement comments about each dog.

These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

## Overview

There are three inputs:
- A file called 'twitter-archive-enhanced.csv' provided by WeRateDogs, corresponding to your Twitter archive. This file contains over 2,000 of their tweets, plus the growth stage of the dog posted (i.e. doggo, floofer, pupper, and puppo); plus the numerator and denominator of the rating. However, this file has the disadvantage of not having the complete information regarding replies and retweets. CSV format.

- Complementary data obtained directly from the twitter API, obtained from the ID of each tweet in the previously commented file. JSON format.

- There is a file with prediction or identification of the breed of each dog, based on the images included in the tweet. This work was previously carried out by a learning machine. It is obtained through the request library. TSV format.

In the code of the wrangle_act.ipynb file, you can see how each of the files is generated.

A Data Wrangling process is developed in its three stages:
1. Gather
2. Assess
3. Clean

Finally, an EDA is carried out.

## License

### MIT License

Copyright (c) 2021 Eric Melillanca.

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
