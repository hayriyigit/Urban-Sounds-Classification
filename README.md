# Urban Sounds Classification
Final project of Deep Learning Bootcamp that organised by Global AI Hub and Koc Holding.

**Preprocessing:**
* Images augmented by shifting spectrograms by 50% to reduce class imbalance (applied to small classes)
* Applied min-max normalization (dividing image values by 255)

**Hyperparameter search:**
* Hyperopt library used for hyperparameter search
* Best parameters:
	* activation : tanh
	* filters: [32,64,64,128]
	* kernel_size: (3, 3)
	* learning_rate: 4.623998518043979e-05
	* optimizer: Adam

**Results:**
*Orange is validation result*
![img](https://i.hizliresim.com/f4ki41y.png)

**Test metrics:**
*Accuracy*: 0.8662821054458618

*F1 Score*: 0.8702771229110035

*Precision*: 0.8702702403508666

*Recall*: 0.8710366547578786
