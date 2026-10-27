# WONS-Power-Consumption-Model-Standardized
The tables report the coefficients of the Linear Regression models that estimate the power demand of a base station layer (technology),
with one model for each technology (M4T). The models are built with the data of the base stations of vendor 1 (V1 based), of vendor 2 (V2 based),
or of both vendors (V1-V2 based), in the last case also using as input the vendor of the base station (V).
The coefficients are non-negative by construction.
The coefficients refer to the standardized features: each feature is standardized with the mean and standard deviation of the training set reported below.

## Coefficient Values V1 based model with RB<sub>DL</sub> as input
| Technology   |   RB<sub>DL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE800       |         0.031478  |   0.164507  |
| LTE1800      |         0.0374003 |   0.113516  |
| LTE2100      |         0.0316001 |   0.0895073 |
| LTE700       |         0.0326541 |   0.136938  |
| LTE2600      |         0.037907  |   0.0845128 |
| NR3700       |         0.0182829 |   0.17102   |


## Coefficient Values V2 based model with RB<sub>DL</sub> as input
| Technology   |   RB<sub>DL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE1800      |         0.0293835 |   0.285541  |
| LTE2100      |         0.054245  |   0.171494  |
| LTE800       |         0.0524146 |   0.26294   |
| LTE2600      |         0.0209082 |   0.0957267 |
| LTE700       |         0.0419689 |   0.100834  |


## Coefficient Values V1-V2 based model with RB<sub>DL</sub> as input
| Technology   |   RB<sub>DL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE1800      |         0.0420703 |    0.215581 |
| LTE2100      |         0.0451568 |    0.125451 |
| LTE800       |         0.0311953 |    0.21755  |
| LTE2600      |         0.0374251 |    0.084952 |
| LTE700       |         0.0399611 |    0.120187 |
| NR3700       |         0.0182829 |    0.17102  |


## Coefficient Values V1-V2 based model with RB<sub>DL</sub>, V as input
| Technology   |   RB<sub>DL</sub> |          V |   Intercept |
|:-------------|------------------:|-----------:|------------:|
| LTE1800      |         0.0329744 | 0.0807887  |    0.215581 |
| LTE2100      |         0.0411532 | 0.0361199  |    0.125451 |
| LTE800       |         0.0425697 | 0.0574903  |    0.21755  |
| LTE2600      |         0.0373949 | 0.00132209 |    0.084952 |
| LTE700       |         0.0399611 | 0          |    0.120187 |
| NR3700       |         0.0182829 | 0          |    0.17102  |


## Coefficient Values V1 based model with RB<sub>UL</sub> as input
| Technology   |   RB<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE800       |         0.027255  |   0.164507  |
| LTE1800      |         0.0357631 |   0.113516  |
| LTE2100      |         0.0265813 |   0.0895073 |
| LTE700       |         0.037367  |   0.136938  |
| LTE2600      |         0.0358459 |   0.0845128 |
| NR3700       |         0.0196957 |   0.17102   |


## Coefficient Values V2 based model with RB<sub>UL</sub> as input
| Technology   |   RB<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE1800      |         0.0202575 |   0.285541  |
| LTE2100      |         0.0586756 |   0.171494  |
| LTE800       |         0.0564504 |   0.26294   |
| LTE2600      |         0.0174468 |   0.0957267 |
| LTE700       |         0.0374233 |   0.100834  |


## Coefficient Values V1-V2 based model with RB<sub>UL</sub> as input
| Technology   |   RB<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------:|
| LTE1800      |        0.00330355 |    0.215581 |
| LTE2100      |        0.0296071  |    0.125451 |
| LTE800       |        0.0210199  |    0.21755  |
| LTE2600      |        0.0343095  |    0.084952 |
| LTE700       |        0.0411767  |    0.120187 |
| NR3700       |        0.0196957  |    0.17102  |


## Coefficient Values V1-V2 based model with RB<sub>UL</sub>, V as input
| Technology   |   RB<sub>UL</sub> |         V |   Intercept |
|:-------------|------------------:|----------:|------------:|
| LTE1800      |         0.028396  | 0.092227  |    0.215581 |
| LTE2100      |         0.0399914 | 0.0491334 |    0.125451 |
| LTE800       |         0.0475344 | 0.0676879 |    0.21755  |
| LTE2600      |         0.0359072 | 0.0087397 |    0.084952 |
| LTE700       |         0.0411767 | 0         |    0.120187 |
| NR3700       |         0.0196957 | 0         |    0.17102  |


## Coefficient Values V1 based model with V<sub>DL</sub> as input
| Technology   |   V<sub>DL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE800       |        0.0323239 |   0.164507  |
| LTE1800      |        0.0338316 |   0.113516  |
| LTE2100      |        0.0301634 |   0.0895073 |
| LTE700       |        0.0337573 |   0.136938  |
| LTE2600      |        0.0346138 |   0.0845128 |
| NR3700       |        0.012134  |   0.17102   |


## Coefficient Values V2 based model with V<sub>DL</sub> as input
| Technology   |   V<sub>DL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE1800      |        0.0325674 |   0.285541  |
| LTE2100      |        0.071363  |   0.171494  |
| LTE800       |        0.0440195 |   0.26294   |
| LTE2600      |        0.0248878 |   0.0957267 |
| LTE700       |        0.0394073 |   0.100834  |


## Coefficient Values V1-V2 based model with V<sub>DL</sub> as input
| Technology   |   V<sub>DL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE1800      |        0.0438016 |    0.215581 |
| LTE2100      |        0.0523189 |    0.125451 |
| LTE800       |        0.0297489 |    0.21755  |
| LTE2600      |        0.0339794 |    0.084952 |
| LTE700       |        0.0370765 |    0.120187 |
| NR3700       |        0.012134  |    0.17102  |


## Coefficient Values V1-V2 based model with V<sub>DL</sub>, V as input
| Technology   |   V<sub>DL</sub> |          V |   Intercept |
|:-------------|-----------------:|-----------:|------------:|
| LTE1800      |        0.0333095 | 0.0801403  |    0.215581 |
| LTE2100      |        0.0485798 | 0.0355754  |    0.125451 |
| LTE800       |        0.0377053 | 0.0545658  |    0.21755  |
| LTE2600      |        0.0343169 | 0.00466013 |    0.084952 |
| LTE700       |        0.0370765 | 0          |    0.120187 |
| NR3700       |        0.012134  | 0          |    0.17102  |


## Coefficient Values V1 based model with V<sub>UL</sub> as input
| Technology   |   V<sub>UL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE800       |        0.0325388 |   0.164507  |
| LTE1800      |        0.0308087 |   0.113516  |
| LTE2100      |        0.0258624 |   0.0895073 |
| LTE700       |        0.0247698 |   0.136938  |
| LTE2600      |        0.0331565 |   0.0845128 |
| NR3700       |        0.0134422 |   0.17102   |


## Coefficient Values V2 based model with V<sub>UL</sub> as input
| Technology   |   V<sub>UL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE1800      |        0.019221  |   0.285541  |
| LTE2100      |        0.0615821 |   0.171494  |
| LTE800       |        0.0372887 |   0.26294   |
| LTE2600      |        0.0226606 |   0.0957267 |
| LTE700       |        0.0338532 |   0.100834  |


## Coefficient Values V1-V2 based model with V<sub>UL</sub> as input
| Technology   |   V<sub>UL</sub> |   Intercept |
|:-------------|-----------------:|------------:|
| LTE1800      |        0.050925  |    0.215581 |
| LTE2100      |        0.0497434 |    0.125451 |
| LTE800       |        0.0378821 |    0.21755  |
| LTE2600      |        0.0325677 |    0.084952 |
| LTE700       |        0.0290893 |    0.120187 |
| NR3700       |        0.0134422 |    0.17102  |


## Coefficient Values V1-V2 based model with V<sub>UL</sub>, V as input
| Technology   |   V<sub>UL</sub> |          V |   Intercept |
|:-------------|-----------------:|-----------:|------------:|
| LTE1800      |        0.0246156 | 0.0759773  |    0.215581 |
| LTE2100      |        0.0434746 | 0.0322239  |    0.125451 |
| LTE800       |        0.035124  | 0.0470071  |    0.21755  |
| LTE2600      |        0.0328633 | 0.00438874 |    0.084952 |
| LTE700       |        0.0290893 | 0          |    0.120187 |
| NR3700       |        0.0134422 | 0          |    0.17102  |


## Coefficient Values V1 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|
| LTE800       |        0.00827677 |        0          |        0.0119356 |       0.0170478  |   0.164507  |
| LTE1800      |        0.0250875  |        0.0145871  |        0         |       0          |   0.113516  |
| LTE2100      |        0.0242218  |        0          |        0.0041533 |       0.00471063 |   0.0895073 |
| LTE700       |        0          |        0.0267958  |        0.0156041 |       0          |   0.136938  |
| LTE2600      |        0.0301618  |        0.00856219 |        0         |       0          |   0.0845128 |
| NR3700       |        0.00697672 |        0.0141023  |        0         |       0          |   0.17102   |


## Coefficient Values V2 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|
| LTE1800      |        0          |        0          |        0.0325674 |      0           |   0.285541  |
| LTE2100      |        0          |        0.0142838  |        0.0609617 |      0           |   0.171494  |
| LTE800       |        0.0179707  |        0.0415549  |        0         |      0           |   0.26294   |
| LTE2600      |        0.00360779 |        0          |        0.0214392 |      0.000679828 |   0.0957267 |
| LTE700       |        0.0408265  |        0.00129084 |        0         |      0           |   0.100834  |


## Coefficient Values V1-V2 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|
| LTE1800      |        0          |        0          |       0.016868   |        0.0393917 |    0.215581 |
| LTE2100      |        0          |        0          |       0.034479   |        0.0230012 |    0.125451 |
| LTE800       |        0.00662691 |        0          |       0.00134633 |        0.0321154 |    0.21755  |
| LTE2600      |        0.0323191  |        0.00578522 |       0          |        0         |    0.084952 |
| LTE700       |        0.00747615 |        0.0265876  |       0.0117769  |        0         |    0.120187 |
| NR3700       |        0.00697672 |        0.0141023  |       0          |        0         |    0.17102  |


## Coefficient Values V1-V2 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub>, V as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |          V |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|-----------:|------------:|
| LTE1800      |        0.0115146  |        0.00472529 |        0.0193831 |        0         | 0.0819528  |    0.215581 |
| LTE2100      |        0          |        0          |        0.0383914 |        0.0133425 | 0.0340506  |    0.125451 |
| LTE800       |        0.00623498 |        0.0342643  |        0.0105393 |        0         | 0.0652601  |    0.21755  |
| LTE2600      |        0.0297622  |        0.00860294 |        0         |        0         | 0.00306899 |    0.084952 |
| LTE700       |        0.00747615 |        0.0265876  |        0.0117769 |        0         | 0          |    0.120187 |
| NR3700       |        0.00697672 |        0.0141023  |        0         |        0         | 0          |    0.17102  |


## Coefficient Values V1 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub>, A, P<sub>Max</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |          A |   P<sub>Max</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|-----------:|------------------:|------------:|
| LTE800       |        0.0150228  |        0.0245786  |       0.0124382  |        0         | 0.0438197  |         0.0081625 |   0.164507  |
| LTE1800      |        0.0250967  |        0.00933173 |       0.00330165 |        0         | 0.00527714 |         0.0132589 |   0.113516  |
| LTE2100      |        0.0202582  |        0          |       0.00776145 |        0.0039135 | 0.00348993 |         0.0122467 |   0.0895073 |
| LTE700       |        0.00328031 |        0.00277501 |       0.0252515  |        0         | 0          |         0.0447852 |   0.136938  |
| LTE2600      |        0.0319173  |        0.00506013 |       0          |        0         | 0          |         0.0137607 |   0.0845128 |
| NR3700       |        0.00697672 |        0.0141023  |       0          |        0         | 0          |         0         |   0.17102   |


## Coefficient Values V2 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub>, A, P<sub>Max</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |           A |   P<sub>Max</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|------------------:|------------:|
| LTE1800      |        0          |         0         |        0.0268345 |      0.00218978  | 0.000947137 |         0.0228053 |   0.285541  |
| LTE2100      |        0          |         0.0142838 |        0.0609617 |      0           | 0           |         0         |   0.171494  |
| LTE800       |        0.0286395  |         0.0175394 |        0         |      0           | 0           |         0.0469294 |   0.26294   |
| LTE2600      |        0.00360779 |         0         |        0.0214392 |      0.000679828 | 0           |         0         |   0.0957267 |
| LTE700       |        0.016912   |         0         |        0.0178392 |      0           | 0           |         0.03064   |   0.100834  |


## Coefficient Values V1-V2 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub>, A, P<sub>Max</sub> as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |          A |   P<sub>Max</sub> |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|-----------:|------------------:|------------:|
| LTE1800      |        0          |        0          |       0.020061   |        0.0162212 | 0.0120089  |         0.0705855 |    0.215581 |
| LTE2100      |        0          |        0          |       0.0338154  |        0.0162491 | 0.00422797 |         0.0264288 |    0.125451 |
| LTE800       |        0.0252661  |        0.00729706 |       0.00637619 |        0.0040286 | 0.00444174 |         0.0672303 |    0.21755  |
| LTE2600      |        0.0293363  |        0.0075832  |       0          |        0         | 0          |         0.0135166 |    0.084952 |
| LTE700       |        0.0146937  |        0.0300633  |       0.00256736 |        0         | 0          |         0.0126677 |    0.120187 |
| NR3700       |        0.00697672 |        0.0141023  |       0          |        0         | 0          |         0         |    0.17102  |


## Coefficient Values V1-V2 based model with RB<sub>DL</sub>, RB<sub>UL</sub>, V<sub>DL</sub>, V<sub>UL</sub>, A, P<sub>Max</sub>, V as input
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |          A |   P<sub>Max</sub> |         V |   Intercept |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|-----------:|------------------:|----------:|------------:|
| LTE1800      |        0.00884369 |        0.00272678 |       0.0202948  |      0.000395112 | 0.00184178 |        0.0323981  | 0.0551152 |    0.215581 |
| LTE2100      |        0          |        0          |       0.0380022  |      0.0130878   | 0.00110291 |        0.00427238 | 0.0308866 |    0.125451 |
| LTE800       |        0.0204655  |        0.016138   |       0.00863129 |      0           | 0.00550776 |        0.0574507  | 0.0142709 |    0.21755  |
| LTE2600      |        0.0293363  |        0.0075832  |       0          |      0           | 0          |        0.0135166  | 0         |    0.084952 |
| LTE700       |        0.0146937  |        0.0300633  |       0.00256736 |      0           | 0          |        0.0126677  | 0         |    0.120187 |
| NR3700       |        0.00697672 |        0.0141023  |       0          |      0           | 0          |        0          | 0         |    0.17102  |


## Mean of the different features for V1 based models
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |       A |   P<sub>Max</sub> |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|--------:|------------------:|
| LTE800       |          38.8672  |          27.6076  |      2.12359e+06 |           567643 | 1.21132 |           16.7059 |
| LTE1800      |          31.1735  |          17.2745  |      4.62538e+06 |           862513 | 1.27206 |           23.917  |
| LTE2100      |          29.376   |          17.5923  |      3.91611e+06 |           685535 | 1.29401 |           22.9688 |
| LTE700       |          28.7399  |          22.174   |      1.58459e+06 |           435184 | 1.14895 |           23.969  |
| LTE2600      |          25.9012  |          14.9595  |      4.51613e+06 |           564010 | 1.25531 |           21.105  |
| NR3700       |           2.00956 |           4.19637 | 865148           |           200423 | 1       |           38.9192 |


## Standard deviation of the different features for V1 based models
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |           A |   P<sub>Max</sub> |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|------------:|------------------:|
| LTE800       |          26.7124  |          14.2986  |      1.69071e+06 |           441077 | 0.0734203   |           5.43211 |
| LTE1800      |          26.9038  |          11.1283  |      4.56339e+06 |           788826 | 0.0962355   |           7.84786 |
| LTE2100      |          25.9173  |          10.7669  |      3.94048e+06 |           703981 | 0.110762    |           6.26429 |
| LTE700       |          19.4904  |           9.64672 |      1.10682e+06 |           370350 | 2.22045e-16 |           4.09812 |
| LTE2600      |          29.3869  |          10.0158  |      6.29125e+06 |           751697 | 0.101702    |           4.7277  |
| NR3700       |           1.50175 |           2.32302 |      1.17379e+06 |           230277 | 0           |           7.11643 |


## Mean of the different features for V2 based models
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |       A |   P<sub>Max</sub> |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|--------:|------------------:|
| LTE1800      |           37.1238 |          11.6933  |      5.74603e+06 |      1.55973e+06 | 1.32812 |           62.6543 |
| LTE2100      |           34.9569 |          13.2237  |      4.75856e+06 | 985903           | 1.32247 |           52.5013 |
| LTE800       |           28.9221 |          14.5863  |      1.68959e+06 | 630336           | 1.15684 |           53.1181 |
| LTE2600      |           29.3152 |           5.51652 |      2.19977e+06 | 306266           | 1.36752 |           30.2712 |
| LTE700       |           18.0963 |          11.6918  |      1.49921e+06 | 446595           | 1.15305 |           46.0363 |


## Standard deviation of the different features for V2 based models
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |         A |   P<sub>Max</sub> |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|----------:|------------------:|
| LTE1800      |           25.0076 |           8.57807 |      3.87459e+06 |      1.01217e+06 | 0.0443189 |      17.886       |
| LTE2100      |           23.3614 |           8.98438 |      3.97385e+06 | 808273           | 0.0393468 |      20.0935      |
| LTE800       |           22.559  |          16.0128  |      1.24588e+06 | 598494           | 0.12171   |      15.6557      |
| LTE2600      |           17.6399 |           4.11182 |      2.68483e+06 | 381863           | 0.0251758 |       3.55271e-15 |
| LTE700       |           15.9832 |          12.754   |      1.36017e+06 | 487162           | 0.11142   |       7.39831     |


## Mean of the different features for V1-V2 based models
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |       A |   P<sub>Max</sub> |         V |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|--------:|------------------:|----------:|
| LTE1800      |          34.7039  |          13.9631  |      5.29027e+06 |      1.27618e+06 | 1.30532 |           46.9004 | 0.593314  |
| LTE2100      |          31.8227  |          15.6771  |      4.28544e+06 | 817218           | 1.30649 |           35.916  | 0.438406  |
| LTE800       |          33.5081  |          20.5908  |      1.88972e+06 | 601427           | 1.18196 |           36.3275 | 0.538873  |
| LTE2600      |          26.0349  |          14.5897  |      4.42541e+06 | 553915           | 1.2597  |           21.464  | 0.0391657 |
| LTE700       |          23.8015  |          17.3105  |      1.54498e+06 | 440478           | 1.15085 |           34.2076 | 0.463974  |
| NR3700       |           2.00956 |           4.19637 | 865148           | 200423           | 1       |           38.9192 | 0         |


## Standard deviation of the different features for V1-V2 based models
| Technology   |   RB<sub>DL</sub> |   RB<sub>UL</sub> |   V<sub>DL</sub> |   V<sub>UL</sub> |         A |   P<sub>Max</sub> |        V |
|:-------------|------------------:|------------------:|-----------------:|-----------------:|----------:|------------------:|---------:|
| LTE1800      |          25.9607  |          10.0766  |      4.20466e+06 |           989042 | 0.0754325 |          24.0194  | 0.491215 |
| LTE2100      |          24.9831  |          10.2562  |      3.97717e+06 |           766124 | 0.0881361 |          20.3415  | 0.496192 |
| LTE800       |          25.057   |          16.5705  |      1.48371e+06 |           532644 | 0.105857  |          21.7978  | 0.498487 |
| LTE2600      |          29.024   |          10.0202  |      6.20596e+06 |           742381 | 0.102161  |           4.96362 | 0.193989 |
| LTE700       |          18.717   |          12.3564  |      1.23161e+06 |           428563 | 0.0759222 |          12.4703  | 0.4987   |
| NR3700       |           1.50175 |           2.32302 |      1.17379e+06 |           230277 | 0         |           7.11643 | 0        |


## Unit of measurement of the different features
RB<sub>DL</sub>: % <br>
RB<sub>UL</sub>: % <br>
V<sub>DL</sub> : kbyte <br>
V<sub>UL</sub> : kbyte <br>
A: linear power ratio $10^{\frac{dB}{10}}$ <br>
P<sub>Max</sub>: W <br>
V: vendor of the base station (0 for V1, 1 for V2) <br>
Power Demand: kW

## How to Use the Model

To estimate the power demand for a given technology, standardize your collected feature values with the mean and standard deviation reported above
for the same model and technology, i.e., (feature - mean) / standard deviation, take the linear combination of the standardized feature values
and the corresponding coefficients from the relevant table above, then add the intercept:

Power Demand = (coefficient<sub>1</sub> × standardized feature<sub>1</sub>) + (coefficient<sub>2</sub> × standardized feature<sub>2</sub>) + ... + Intercept

For example, using the V1 model with RB<sub>DL</sub> as input for LTE800: Power Demand = 0.031478 × (RB<sub>DL</sub> - 38.8672) / 26.7124 + 0.164507. The same applies to the multi-feature tables, include one term per feature column for the chosen technology, using that row's coefficients, and sum them together with the intercept. A feature with (almost) zero standard deviation is constant for that technology: it is not standardized and its coefficient is zero, so it does not contribute to the power demand.
