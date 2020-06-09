# ASAP
This repository contains the data for the paper "ASAP: A Chinese Review Dataset Towards Aspect-BasedSentiment Analysis and Rating Prediction"

ASAP is a large-scale Chinese restaurant review dataset for aspect-based sentiment analysis and rating prediction.

# Read file
  ```
  import pandas as pd
  
  data = pd.read_csv(file_path, header=0)
  ```
# Data labels
  The sentiment polarity over the aspect category is labeled as 1(Positive), 0(Neutral), −1(Negative), −2(Not-Mentioned)
  
  The star ratings range from 1 to 5.
