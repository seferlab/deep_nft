**_`NFT Sales Characteristics And Price Prediction By Transfer Learning Visual Attributes`_**

*This is the repository for the "NFT Sales Characteristics And Price Prediction By Transfer Learning Visual Attributes". This repository serves the notebook files which include the code and results of the study.

## *_Steps to Reproduce Our Results_*

*_- Clone the Repository to Your Local Machine_*

```bash
git clone https://github.com/seferlab/deep_nft.git
```

*_- Make sure that the dataset is ready which can be found in [Non fungible tokens dataset](https://osf.io/wsnzr/?view_only=319a53cf1bf542bbbe538aba37916537) that is provided by the article Mapping the NFT revolution: market trends, trade networks, and visual features. *> Nadini, M., Alessandretti, L., Di Giacinto, F. et al. Mapping the NFT revolution: market trends, trade networks, and visual features. Sci Rep 11, 20902 (2021)*<br/>_*

*_- To calculate the median price and add it to the dataset as a feature, run the `MedianPrice Feature Calculation.ipynb`<br/>_*

*_- To calculate the resale probability and add it to the dataset as a feature, run the `Presale Calculation.ipynb`<br/>_*

*_- To analyze trader centrality behavior and add it to the dataset as a feature, run the `Trader Network.ipynb`<br/>_*

*_- To apply the SMOTE for the minority class and observe the effect on the performance, run the `SMOTE.ipynb`<br/>_*

*_- To get the best-performing experiments on CNN for the secondary sale classification, run the `CNN Secondary Sale Classification.ipynb`<br/>_*

*_- To obtain the grid search results of the XGBoost and observe the effect on the performance, run the `XGBoost Hyperparameter Tuning.ipynb` which is used for hyperparameter tuning.<br/>_*

*_- To obtain the grid search results of the secondary sale classification for AdaBoost, RandomForest, and XGBoost run the `HyperParameter Tuning.ipynb`.<br/>_*

*_- To obtain primary sale price prediction results, run the `Primary Sale Price Prediction.ipynb`.<br/>_*


## Contact

You can contact Emre Sefer (emre.sefer@ozyegin.edu.tr) or Mustafa Pala (mustafa.pala@ozu.edu.tr) if you have any questions about the implementation.
