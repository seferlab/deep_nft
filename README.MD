# **_deep_nft_**

**_`NFT Sales Characteristics And Price Prediction By Transfer Learning Visual Attributes`_**

*_This is the repository for the "NFT Sales Characteristics And Price Prediction By Transfer Learning Visual Attributes" master thesis at Özyegin University. This repository serves the notebook files which include the code and results of the study._**

## *_Steps to Re-Produce Our Results_*

*_- Clone the Repository to Your Local Machine_*

```bash
git clone https://github.com/seferlab/deep_nft.git
```

*_- Make sure that the dataset is ready which can be found in [Non fungible tokens dataset](https://osf.io/wsnzr/?view_only=319a53cf1bf542bbbe538aba37916537) that is provided by the article Mapping the NFT revolution: market trends, trade networks, and visual features. *> Nadini, M., Alessandretti, L., Di Giacinto, F. et al. Mapping the NFT revolution: market trends, trade networks, and visual features. Sci Rep 11, 20902 (2021)*<br/>_*

*_- To calculate the median price and add it to the dataset as a feature, run the `MedianPrice_Feature_Calculation.ipynb`<br/>_*

*_- To calculate the resale probability and add it to the dataset as a feature, run the `Presale_calculation.ipynb`<br/>_*

*_- To analyze trader centrality behavior and add it to the dataset as a feature, run the `Trader_network.ipynb`<br/>_*

*_- To apply the SMOTE for the minority class and observe the effect on the performance, run the `SMOTE.ipynb`<br/>_*

*_- To get the best-performing experiments on CNN for the secondary sale classification, run the `CNN_experiments_with_secondary_price_classification.ipynb`<br/>_*

*_- To obtain the grid search results of the XGBoost and observe the effect on the performance, run the `XGBoost_Hyperparameter_Tuning_Implementation.ipynb` which is used for hyperparameter tuning.<br/>_*

*_- To obtain the grid search results of the secondary sale classification for AdaBoost, RandomForest, and XGBoost run the `All_HyperParameter.ipynb`.<br/>_*

*_- To obtain the all results of the paper, run the `NFT_Report.ipynb`.<br/>_*



## *_Institution_*

- **_[Ozyegin University](https://www.ozyegin.edu.tr/)_**

## *_Thesis Members_*

- **_[Mustafa Pala](https://github.com/mustafapala)_**<br/>

## *_Thesis Advisor_*

- **_[Assistant Prof. Emre Sefer](http://www.emresefer.com/)_**