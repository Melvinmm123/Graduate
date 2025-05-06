Automated Candlestick Pattern Recognition Using CrossViT

This repository contains the implementation of a deep learning framework for automated recognition of candlestick chart patterns using Gramian Angular Field (GAF) images and the CrossViT model. The project focuses on classifying eight key patterns from OHLC (Open, High, Low, Close) data, addressing class imbalance, and enhancing out-of-distribution (OOD) performance during recession periods.

Project Overview





Purpose: Automate the identification of candlestick patterns for technical analysis in stock trading.



Methodology: Converts OHLC time-series data into GAF images and processes them with the CrossViT model.



Patterns Classified: Triple Bottom Reversal, Ascending Triangle, Symmetrical Triangle, Head and Shoulders, Descending Triangle, Double Top, Inverse Head and Shoulders, Cup and Handle.



Techniques: Oversampling with Historical Interpolation and Transformation (OHIT), Test-Time Adaptation (TTA).

