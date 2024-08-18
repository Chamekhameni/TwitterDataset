# Context
This dataset is part of a thesis conducted at the MIRACL research laboratory, focusing on sentiment analysis within the agricultural sector. Our dataset is enriched through collaboration with agricultural experts from the National Agronomic Institute of Tunisia (INAT), to identify sentiment polarities and ensure the annotation process. 
--> To address the current lack of datasets in this field, we propose a method for constructing such datasets by collecting and annotating tweets related to pest control and crop diseases in agriculture.

# How was it collected?
- The "Twitter_Dataset" was automatically collected from Twitter using a Python web extension designed to extract tweets.
- The collection period extends from May 19, 2009, to February 27, 2024.
- The data collection detailed in our paper titled " An agricultural sentiment dataset for pest control
and crop diseases".

# Content of Twitter_Dataset
- The data is a CSV file comprising 1617 tweets collected on pest control and crop diseases in agriculture.
- The tweets are categorized into six types of pests and diseases: "Insects", "Fungi", "Herbs", "Bacteria", "Nematodes", and "Viruses".
- Each tweet includes columns for "class", "user", "userLink", "tweet", and "date".

# Annotation
The tweets were manually labeled in collaboration with INAT’s agricultural domain experts. This process involves reading the tweets
and attributing associated four polarities (positive, negative, neutral, or mixed feelings).
The annotation of the Twitter dataset shows a distribution of sentiments as follows: 608 positive, 436 negative, 486 neutral, and 87 mixed-feelings sentiments.

# Statistics
The aspect 'control methods' contains 11.7% of reviews are mixed-feelings, 13.4% of reviews are negative, 16.6% of reviews are neutral, 58.3% of reviews are positive.
The aspect 'disease' contains 3.8% of reviews are mixed-feelings, 29.9% of reviews are negative, 37.1% of reviews are neutral, 29.1% of reviews are positive.
The aspect 'efficacity' contains 4.8% of reviews are mixed-feelings, 15.4% of reviews are negative, 24.0% of reviews are neutral, 55.8% of reviews are positive.
The aspect 'overall' contains 3.9% of reviews are mixed-feelings, 7.8% of reviews are negative, 52.6% of reviews are neutral, 35.7% of reviews are positive.
The aspect 'pest' contains 2.4% of reviews are mixed-feelings, 37.9% of reviews are negative, 34.8% of reviews are neutral, 24.8% of reviews are positive.
The aspect 'safety' contains 9.5% of reviews are mixed-feelings, 42.9% of reviews are negative, 2.4% of reviews are neutral, 45.2% of reviews are positive.
The aspect 'toxicity' contains 5.0% of reviews are mixed-feelings, 85.0% of reviews are negative, 3.3% of reviews are neutral, 6.7% of reviews are positive.
The aspect 'usage' contains 5.0% of reviews are mixed-feelings, 22.9% of reviews are negative, 24.0% of reviews are neutral, 48.0% of reviews are positive.
