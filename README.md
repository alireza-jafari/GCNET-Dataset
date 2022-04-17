# GCNET-Dataset

This repository releases a comprehensive dataset for stock movement prediction from historical stock prices. Please cite the following paper [bib](https://arxiv.org/abs/2203.11091) if you use this dataset,

Alireza Jafari and Saman Haratizadeh.  2022. [GCNET: graph-based prediction of stock price movement using graph convolutional network](https://arxiv.org/abs/2203.11091)

Code of paper is [here](https://github.com/alireza-jafari/GCNET-Code) (GCNET-Code).

### Dataset Overview
Our dataset contains the historical data for 100 stocks with the largest market capitalization in the Nasdaq index from 01/01/2011 to 01/01/2021. The data in 15/09/2020 to 29/09/2020 interval is used for validation and to set the hyper-parameters. The test period is from 09/30/2020 to 12/30/2020 which includes 5952 records.

### Raw Price Data
Format: CSV  
Entries: date, open price, high price, low price, close price, adjust close price, volume  

@article{jafari2022gcnet,
 
 title={GCNET: graph-based prediction of stock price movement using graph convolutional network},
 
 author={Jafari, Alireza and Haratizadeh, Saman},
 
 journal={arXiv preprint arXiv:2203.11091},
 
 year={2022}

}
