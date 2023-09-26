# APT： Audio prompt tuning for universal sound separation
This is the official repository of [paper: AUDIO PROMPT TUNING FOR UNIVERSAL SOUND SEPARATION](). This work is a simple yet effective approach to enhance existing universal sound separation systems. Audio prompt tuning (APT) improves the separation performance of specific sources through training a small number of prompt parameters with limited data, while maintaining the generalization of the universal sound separation model by keeping its parameters frozen. The number of tuned parameters are **less than 0.1%** of the parameters of the backbone model. <br>
![pipeline](https://github.com/redrabbit94/APT-USS/assets/29458099/8058871c-3b3f-4f24-b8ad-1c6d7cbe2a32)

## Demo Page
Demo page 

## Results
We evaluate our method on MUSDB18 and ESC-50 dataset with **few-shot** settings and full training data. Average SDR scores of APT and average prompt embedding without tuning (Baseline) list in the following table.

|         |MUSDB18_fulldata|ESC-50_fulldata|ESC-50_1-shot|ESC-50_5-shot|ESC-50_10-shot|
|  -----  |   -----    |    -----  |    -----    |    -----   |     -----  |
|   APT   |   4.98     |    8.50   |    4.57     |    6.68    |     7.59    |
|Baseline |   4.31     |    6.44   |    4.09     |    5.59    |     6.10    |

Detailed results on ESC-50 are available [here](https://github.com/redrabbit94/APT-USS/blob/main/Results-ESC50.csv).

## Cite our work
To be done after publishing
