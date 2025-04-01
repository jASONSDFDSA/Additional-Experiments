# Additional Experiments

## Catalogue
- [For Reviewer BzXw](#BzXw)
   - [Methods And Evaluation Criteria](#BzXw_M)
- [For Reviewer WHHW](#WHHW)
  - [Methods And Evaluation Criteria: M3 and Essential References Not Discussed](#WHHW_M)
- [For Reviewer 9xQG](#9xQG)
  - [Answers to Questions](#9xQG_A)
  - [Claims And Evidence: C4](#9xQG_C)
  - [Essential References Not Discussed](#9xQG_E)
  - [Other Comments Or Suggestions](#9xQG_O)


## For Reviewer BzXw<a id="BzXw"></a>
### For Methods And Evaluation Criteria<a id="BzXw_M"></a>
The forget classes are chosen randomly for fair comparison.
#### Random Subset Unlearning Experiment results on CUB dataset with ResNet18 model

| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ | 100.00 $\scriptsize{\pm}$ 0.00 | **100.00 $\scriptsize{\pm}$ 0.01** | 97.68 $\scriptsize{\pm}$ 1.20 | 86.47 $\scriptsize{\pm}$ 5.72 | **100.00 $\scriptsize{\pm}$ 0.00**  | 99.07 $\scriptsize{\pm}$ 0.09 | **100.00 $\scriptsize{\pm}$ 0.00** | 99.99 $\scriptsize{\pm}$ 0.02 |
| $\mathcal{D}_f$ | 100.00 $\scriptsize{\pm}$ 0.00 | **64.77 $\scriptsize{\pm}$ 2.14** | 81.10 $\scriptsize{\pm}$ 5.27 | 51.42 $\scriptsize{\pm}$ 6.97 | 100.00 $\scriptsize{\pm}$ 0.00 | 92.02 $\scriptsize{\pm}$ 0.30 | 100.00 $\scriptsize{\pm}$ 0.00 | **67.31 $\scriptsize{\pm}$ 2.55** |
| $\mathcal{D}_{test}$ | 70.74 $\scriptsize{\pm}$ 0.45 | **69.28 $\scriptsize{\pm}$ 1.55** | 53.31 $\scriptsize{\pm}$ 2.60 | 45.35 $\scriptsize{\pm}$ 5.31 | **69.00 $\scriptsize{\pm}$ 1.12**  | 49.24 $\scriptsize{\pm}$ 0.22 | 72.45 $\scriptsize{\pm}$ 0.37 | 67.07 $\scriptsize{\pm}$ 1.49 |
| MIA | 79.58 $\scriptsize{\pm}$ 0.50 | **51.22 $\scriptsize{\pm}$ 1.58** | 65.18 $\scriptsize{\pm}$ 1.58 | **52.33 $\scriptsize{\pm}$ 1.40** | 78.50 $\scriptsize{\pm}$ 0.62 | 73.20 $\scriptsize{\pm}$ 0.97 | 81.40 $\scriptsize{\pm}$ 1.35 | 48.70 $\scriptsize{\pm}$ 2.56 |

#### Continual Unlearning Experiment results on CUB dataset with ResNet18 model

| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ | 100.00 $\scriptsize{\pm}$ 0.00 | **100.00 $\scriptsize{\pm}$ 0.00** | 99.11 $\scriptsize{\pm}$ 0.39 | 97.56 $\scriptsize{\pm}$ 2.48 | **100.00 $\scriptsize{\pm}$ 0.00** | 98.23 $\scriptsize{\pm}$ 0.04 | **100.00 $\scriptsize{\pm}$ 0.00** | 99.96 $\scriptsize{\pm}$ 0.07 |
| $\mathcal{D}_f$ | 100.00 $\scriptsize{\pm}$ 0.00 | **64.05 $\scriptsize{\pm}$ 0.63** | **64.05 $\scriptsize{\pm}$ 2.88** | 63.83 $\scriptsize{\pm}$ 2.95 | 100.00 $\scriptsize{\pm}$ 0.00 | 95.77 $\scriptsize{\pm}$ 0.19 | 100.00 $\scriptsize{\pm}$ 0.00 | 67.89 $\scriptsize{\pm}$ 2.43 |
| $\mathcal{D}_{test}$ | 70.74 $\scriptsize{\pm}$ 0.45 | **68.86 $\scriptsize{\pm}$ 0.69** | 52.46 $\scriptsize{\pm}$ 1.33 | 58.50 $\scriptsize{\pm}$ 2.71 | 69.44 $\scriptsize{\pm}$ 1.04 | 52.55 $\scriptsize{\pm}$ 0.85 | 72.50 $\scriptsize{\pm}$ 0.46 | **67.25 $\scriptsize{\pm}$ 1.55** |
| MIA | 79.58 $\scriptsize{\pm}$ 0.50 | **51.39 $\scriptsize{\pm}$ 2.22** | 55.42 $\scriptsize{\pm}$ 1.04 | 53.89 $\scriptsize{\pm}$ 0.97 | 79.06 $\scriptsize{\pm}$ 0.13 | 74.42 $\scriptsize{\pm}$ 1.18 | 80.97 $\scriptsize{\pm}$ 0.55 | **50.39 $\scriptsize{\pm}$ 0.21** |

#### Class Unlearning Experiment results on CUB dataset with ResNet18 model

##### Unlearning on class Lazuli_Bunting

| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ | 100.00 $\scriptsize{\pm}$ 0.00 | **100.00 $\scriptsize{\pm}$ 0.00** | 95.45 $\scriptsize{\pm}$ 0.93 | 97.79 $\scriptsize{\pm}$ 0.43 | **100.00 $\scriptsize{\pm}$ 0.00** | **100.00 $\scriptsize{\pm}$ 9.00** | 55.96 $\scriptsize{\pm}$ 0.01 | **100.00 $\scriptsize{\pm}$ 0.01** |
| $\mathcal{D}_f$ | 100.00 $\scriptsize{\pm}$ 0.00 | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | 3.33 $\scriptsize{\pm}$ 0.00 | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** |
| $\mathcal{D}_{test}$ | 70.80 $\scriptsize{\pm}$ 0.65 | **71.04 $\scriptsize{\pm}$ 0.72** | 49.91 $\scriptsize{\pm}$ 0.95 | 54.58 $\scriptsize{\pm}$ 2.25 | 69.05 $\scriptsize{\pm}$ 0.54 | 70.22 $\scriptsize{\pm}$ 0.60 | 25.13 $\scriptsize{\pm}$ 0.66 | **69.43 $\scriptsize{\pm}$ 1.33** |
| Relearn Time |   | **43.60 $\scriptsize{\pm}$ 15.92** | 49.2 $\scriptsize{\pm}$ 22.62 | **42.20 $\scriptsize{\pm}$ 4.75** | 16.8 $\scriptsize{\pm}$ 3.42 | 25.80 $\scriptsize{\pm}$ 11.63 | 85.60 $\scriptsize{\pm}$ 16.83 | 48.4 $\scriptsize{\pm}$ 23.39 |

##### Unlearning on class Fish_Crow

| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ | 100.00 $\scriptsize{\pm}$ 0.00 | **100.00 $\scriptsize{\pm}$ 0.00** | 94.88 $\scriptsize{\pm}$ 2.60 | 95.87 $\scriptsize{\pm}$ 2.04 | **100.00 $\scriptsize{\pm}$ 0.00** | **100.00 $\scriptsize{\pm}$ 0.00** | 13.78 $\scriptsize{\pm}$ 0.00 | **100.00 $\scriptsize{\pm}$ 0.01** |
| $\mathcal{D}_f$ | 100.00 $\scriptsize{\pm}$ 0.00 | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** |
| $\mathcal{D}_{test}$ | 70.39 $\scriptsize{\pm}$ 0.31 | **71.29 $\scriptsize{\pm}$ 1.05** | 50.42 $\scriptsize{\pm}$ 3.93 | 52.55 $\scriptsize{\pm}$ 3.48 | 68.22 $\scriptsize{\pm}$ 0.66 | **72.00 $\scriptsize{\pm}$ 0.24** | 8.72 $\scriptsize{\pm}$ 0.30 | 68.83 $\scriptsize{\pm}$ 0.80 |
| Relearn Time |   | **146.2 $\scriptsize{\pm}$ 19.33** | 62.6 $\scriptsize{\pm}$ 20.04 | 86.4 $\scriptsize{\pm}$ 31.21 | 28.4 $\scriptsize{\pm}$ 6.69 | 51.2 $\scriptsize{\pm}$ 20.57 | 83.8 $\scriptsize{\pm}$ 25.06 | **96 $\scriptsize{\pm}$ 39.55** |

## For Reviewer WHHW<a id="WHHW"></a>

### For Methods And Evaluation Criteria: M3 and Essential References Not Discussed<a id="WHHW_M"></a>
The additional experiments here include additional metrics, such as "relearn time," on class unlearning and subclass unlearning, and an additional baseline method, SFR-on. The forget classes are chosen based on the setting in the work of SSD.

#### Random Subset Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | SalUn | SFR-on | VGE-BF |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  80.15  $\pm$ 0.00  |   **80.08 $\pm$ 1.39**  |  90.53 $\pm$  0.00  |  98.55 $\scriptsize{\pm}$ 1.19   |  **80.44 $\pm$ 0.74**   |
| $\mathcal{D}_f$ |  80.48 $\pm$ 0.00  |  **51.05 $\pm$ 1.62**   |  85.32 $\pm$ 0.00   |   0.00  $\scriptsize{\pm}$ 0.00  |  **55.58  $\pm$ 0.42**  |
| $\mathcal{D}_{test}$ |  52.21  $\pm$  0.51 |  **50.51  $\pm$ 0.39**  |  **51.02  $\pm$ 0.48**  |   29.82 $\scriptsize{\pm}$ 3.47  |  51.28  $\pm$ 0.79  |
| MIA |  64.18  $\pm$  0.61  |  **50.21  $\pm$  0.69** |  67.31 $\pm$ 0.29   |  93.86 $\scriptsize{\pm}$ 0.53  |  **52.14  $\pm$ 0.86**  |

#### Continual Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | SalUn | SFR-on | VGE-BF |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ | 80.15  $\pm$ 0.00   |  **80.24 $\pm$ 1.09**   |   96.84 $\pm$ 0.00  |  99.98  $\scriptsize{\pm}$ 0.00   |  **80.66 $\pm$ 0.74**   |
| $\mathcal{D}_f$ |  80.48 $\pm$ 0.00  |  **51.51  $\pm$ 0.66**  |  89.02  $\pm$ 0.00  |  30.27  $\scriptsize{\pm}$ 0.42   |  **55.81 $\pm$ 0.42**   |
| $\mathcal{D}_{test}$ |   52.32 $\pm$ 0.79  |  **51.38 $\pm$ 0.68**   |  52.03  $\pm$ 0.39  |   39.16  $\scriptsize{\pm}$ 0.95  |  **51.52  $\pm$ 0.79**  |
| MIA |  64.43  $\pm$ 0.78  |  **49.60 $\pm$ 0.75**   |  69.40  $\pm$ 0.35  |  56.35 $\scriptsize{\pm}$ 0.68   |  **52.10 $\pm$ 0.86**   |

#### Class Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | SalUn | SFR-on | VGE-BF |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  79.36 $\pm$ 0.00   | **87.09 $\pm$ 0.91**  |  95.30 $\pm$ 0.00   |  99.98 $\scriptsize{\pm}$ 0.00   |  **87.31 $\pm$ 1.03**   |
| $\mathcal{D}_f$ |  85.00 $\pm$ 0.00   |   **0.00 $\pm$ 0.00**  |  **0.00 $\pm$ 0.00**   |  **0.00 $\scriptsize{\pm}$ 0.00**   |  **0.00 $\pm$ 0.00**   |
| $\mathcal{D}_{test}$ |   50.83 $\pm$ 0.83  |   **52.06 $\pm$ 0.62**  |  55.09 $\pm$ 0.33   |  53.01 $\scriptsize{\pm}$ 0.00  |  **51.60 $\pm$ 0.80**   |
| Relearn Time |       |  **778.40 $\pm$ 183.77**  |  11 $\pm$ 0.00   |   2923.67 $\scriptsize{\pm}$ 481.78  |  **570.40 $\pm$ 90.89**   |

##### Unlearning on class Mushroom.

| Metric | Original | Retrain | SalUn | SFR-on | VGE-BF |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  79.32 $\pm$ 0.00   |  **86.42 $\pm$ 0.84**   |  95.17 $\pm$ 0.40   |  99.98 $\scriptsize{\pm}$ 0.00   |   **87.53 $\pm$ 0.47**  |
| $\mathcal{D}_f$ |  89.20 $\pm$ 0.00   |   **0.00 $\pm$ 0.00**  |   **0.00 $\pm$ 0.00**  |   **0.00 $\scriptsize{\pm}$ 0.00**   |  **0.00 $\pm$ 0.00**  |
| $\mathcal{D}_{test}$ |  51.10 $\pm$ 0.53   |  **51.87 $\pm$ 0.58**   |  54.74  $\pm$ 0.52   |  54.55 $\scriptsize{\pm}$ 0.00   |  **52.55 $\pm$ 0.49**   |
| Relearn Time |     |  **1775.20 $\pm$ 210.51**   |  21.00 $\pm$ 2.24   |  2511.00 $\scriptsize{\pm}$ 267.09   |  **1753.40  $\pm$ 210.38**  |

#### Subclass Unlearning Experiment results on CIFAR-20 dataset with ResNet18 model.
##### Unlearning on class Rocket.

| Metric | Original | Retrain | SalUn | SFR-on | VGE-BF |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |   89.07 $\pm$ 0.00 |  **87.96 $\pm$ 1.81**   |  96.57 $\pm$ 0.00   |   99.98 $\scriptsize{\pm}$ 0.00  |  **86.24 $\pm$ 3.62**   |
| $\mathcal{D}_f$ |   94.00 $\pm$ 0.00 |  **2.28 $\pm$ 1.11**   |   9.40 $\pm$ 0.00  |   **0.93 $\scriptsize{\pm}$ 1.27**  |  7.72 $\pm$ 2.01   |
| $\mathcal{D}_{test}$ |  65.02 $\pm$ 0.11  |   **63.58 $\pm$ 1.08**  |  66.77 $\pm$  0.44  |  68.67 $\scriptsize{\pm}$ 4.16   |   **61.98 $\pm$ 3.10**  |
| Relearn Time |     |  **765.20  $\pm$ 232.08**  |  11.00 $\pm$  0.00  |  **900.33 $\scriptsize{\pm}$ 642.92**   |  608.20 $\pm$ 139.05   |

##### Unlearning on class Sea.

| Metric | Original | Retrain | SalUn | SFR-on | VGE-BF |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  86.95 $\pm$ 0.00   |  **88.82 $\pm$ 0.70**   |  95.50  $\pm$ 0.00  |  99.91 $\scriptsize{\pm}$ 0.02    |  **88.23  $\pm$ 1.13**  |
| $\mathcal{D}_f$ |   98.20 $\pm$ 0.00  |  **71.76 $\pm$ 9.46**   |  **76.40 $\pm$ 2.24**   |   60.93 $\scriptsize{\pm}$ 4.93  |  81.30 $\pm$ 3.62   |
| $\mathcal{D}_{test}$ |   63.53 $\pm$ 0.30  |  **64.43  $\pm$ 0.81**  |   67.44 $\pm$ 0.64  |  64.00 $\scriptsize{\pm}$ 5.29   |  **64.37 $\pm$ 0.50**   |
| Relearn Time |     |  **646.80 $\pm$ 90.94**   |  10.00 $\pm$ 0.00  |  187.00 $\scriptsize{\pm}$ 141.11   |   **609.20 $\pm$ 152.78**   |


## For Reviewer 9xQG<a id="9xQG"></a>

### For Answers to Questions: A1<a id="9xQG_A"></a>

We used different values for the coefficient $\lambda$ to the loss on the forget set in NegGrad+ to update the model during gradient ascent. Results show that focusing on too much of either objective impairs the overall performance of unlearning.

![NegGrad+_lambda0](assets/neggrad_images_0.png)

![NegGrad+_lambda0.5](assets/neggrad_images_0.5.png)

![NegGrad+_lambda1](assets/neggrad_images_1.png)

![NegGrad+_lambda1.5](assets/neggrad_images_1.5.png)

![NegGrad+_lambda2](assets/neggrad_images_2.png)

### For Claims And Evidence: C4<a id="9xQG_C"></a>

We set epoch the epoch for the retrained model to 10. Hyperparameters for other methods follow their experimental settings in their work. 

| $t=5$ | $\mathcal{D}_r$ | $\mathcal{D}_f$ | $\mathcal{D}_{test}$ | MIA |
| :---: | :---: | :---: | :---: | :---: |
| Original | 77.31 | 78.06 | 52.32 | 62.80 |
| Retrain | **90.81** | **50.26** | **51.28** | **49.91** |
| FT w/o $\mathcal{D}_f$ | 81.87 | 66.04 | **50.54** | **57.94** |
| BadT | 67.37 | **64.50** | 49.64 | 58.39 |
| SalUn | **87.76** | 80.50 | 54.99 | 62.94 |
| $t=10$ | $\mathcal{D}_r$ | $\mathcal{D}_f$ | $\mathcal{D}_{test}$ | MIA |
| Original | 91.59 | 92.00 | 52.78 | 70.03 |
| Retrain | **90.11** | **49.60** | **50.64** | **50.62** |
| FT w/o $\mathcal{D}_f$ | **93.20** | 83.04 | **51.74** | 66.02 |
| BadT | 83.45 | **78.70** | 49.74 | **64.70** |
| SalUn | 96.25 | 89.71 | 52.77 | 68.38 |
| $t=15$ | $\mathcal{D}_r$ | $\mathcal{D}_f$ | $\mathcal{D}_{test}$ | MIA |
| Original | 95.54 | 95.48 | 52.22 | 71.55 |
| Retrain | **90.22** | **50.16** | **50.81** | **50.32** |
| FT w/o $\mathcal{D}_f$ | 96.02 | 89.50 | **50.28** | 69.89 |
| BadT | **92.12** | **87.18** | 49.68 | **68.94** |
| SalUn | 98.39 | 92.72 | 51.91 | 70.48 |


### For Essential References Not Discussed<a id="9xQG_E"></a>

#### Random Subset Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  80.15  $\pm$ 0.00   |   **80.08 $\pm$ 1.39**   |  21.58 $\scriptsize{\pm}$ 0.95   |  68.28 $\scriptsize{\pm}$ 0.00  |  **80.44 $\pm$ 0.74**   |
| $\mathcal{D}_f$ |  80.48 $\pm$ 0.00   |   **51.05 $\pm$ 1.62**  |   20.58 $\scriptsize{\pm}$ 0.83  |   67.15 $\scriptsize{\pm}$ 0.06  |  **55.58  $\pm$ 0.42**   |
| $\mathcal{D}_{test}$ |  52.21  $\pm$  0.51   |   **50.51  $\pm$ 0.39**  |  20.21 $\scriptsize{\pm}$ 1.22  |  54.09 $\scriptsize{\pm}$ 0.01   |   **51.28  $\pm$ 0.79**  |
| MIA |  64.18  $\pm$  0.61    |   **50.21  $\pm$  0.69**  |  **50.99 $\scriptsize{\pm}$ 0.36**  | 57.05 $\scriptsize{\pm}$ 0.37 |  52.14  $\pm$ 0.86   |

#### Continual Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  80.15  $\pm$ 0.00   |  **80.24 $\pm$ 1.09**   |   1.60 $\scriptsize{\pm}$ 0.65  |  68.21 $\scriptsize{\pm}$ 0.00  |   **80.66 $\pm$ 0.74**  |
| $\mathcal{D}_f$ |   80.48 $\pm$ 0.00  |  **51.51  $\pm$ 0.66**   |   1.49 $\scriptsize{\pm}$ 0.70  |   67.49 $\scriptsize{\pm}$ 0.02  |   **55.81 $\pm$ 0.42**  |
| $\mathcal{D}_{test}$ |  52.32 $\pm$ 0.79   |  **51.38 $\pm$ 0.68**    |  1.56 $\scriptsize{\pm}$ 0.59   |   53.92 $\scriptsize{\pm}$ 0.03  |  **51.52  $\pm$ 0.79**   |
| MIA |  64.43  $\pm$ 0.78    |  **49.60 $\pm$ 0.75**   |   **50.99 $\scriptsize{\pm}$ 0.37**  | 56.90 $\scriptsize{\pm}$ 0.27 |  52.10 $\pm$ 0.86   |

#### Class Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  79.36 $\pm$ 0.00   |  **87.09 $\pm$ 0.91**   | 27.83 $\scriptsize{\pm}$ 0.91  |   65.86 $\scriptsize{\pm}$ 0.00  |   **87.31 $\pm$ 1.03**   |
| $\mathcal{D}_f$ |  85.00 $\pm$ 0.00   |   **0.00 $\pm$ 0.00**  |  **0.00 $\scriptsize{\pm}$ 0.00**  |  73.60 $\scriptsize{\pm}$ 0.00   |   **0.00 $\pm$ 0.00**   |
| $\mathcal{D}_{test}$ |  50.83 $\pm$ 0.83   |   **52.06 $\pm$ 0.62**   |  26.81 $\scriptsize{\pm}$ 1.16  |   53.91 $\scriptsize{\pm}$ 0.01  |   **51.60 $\pm$ 0.80**  |

##### Unlearning on class Mushroom.
| Metric | Original | Retrain |SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  79.32 $\pm$ 0.00   |  **86.42 $\pm$ 0.84**   |  29.64 $\scriptsize{\pm}$ 1.45  |   65.98 $\scriptsize{\pm}$ 0.00  |  **87.53 $\pm$ 0.47**   |
| $\mathcal{D}_f$ |  89.20 $\pm$ 0.00   |  **0.00 $\pm$ 0.00**   |   **0.00 $\scriptsize{\pm}$ 0.00**  |  37.47 $\scriptsize{\pm}$ 0.01   |  **0.00 $\pm$ 0.00**   |
| $\mathcal{D}_{test}$ |   51.10 $\pm$ 0.53   | **51.87 $\pm$ 0.58**  | 28.06 $\scriptsize{\pm}$ 1.32  |  54.21 $\scriptsize{\pm}$ 0.01   |   **52.55 $\pm$ 0.49**  |

#### Subclass Unlearning Experiment results on CIFAR-20 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  89.07 $\pm$ 0.00   |   **87.96 $\pm$ 1.81**  |  50.98 $\scriptsize{\pm}$ 0.78 |   79.21 $\scriptsize{\pm}$ 0.01  |  **86.24 $\pm$ 3.62**   |
| $\mathcal{D}_f$ |   94.00 $\pm$ 0.00  |  **2.28 $\pm$ 1.11**  |  **0.02 $\scriptsize{\pm}$ 1.29**   |   68.60 $\scriptsize{\pm}$ 0.20  |  7.72 $\pm$ 2.01   |
| $\mathcal{D}_{test}$ |  65.02 $\pm$ 0.11   |   **63.58 $\pm$ 1.08**   |  57.33 $\scriptsize{\pm}$ 3.06   |  72.00 $\scriptsize{\pm}$ 0.00   |  **61.98 $\pm$ 3.10**   |

##### Unlearning on class Sea.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |  86.95 $\pm$ 0.00   |  **88.82 $\pm$ 0.70**  |  51.81 $\scriptsize{\pm}$ 1.21  |  79.16 $\scriptsize{\pm}$ 0.02   |  **88.23  $\pm$ 1.13**   |
| $\mathcal{D}_f$ |  98.20 $\pm$ 0.00   |   **71.76 $\pm$ 9.46**  |  **70.87 $\scriptsize{\pm}$ 9.13**  |  92.60 $\scriptsize{\pm}$ 0.00   |   81.30 $\pm$ 3.62  |
| $\mathcal{D}_{test}$ |  63.53 $\pm$ 0.30   |   **64.43  $\pm$ 0.81**  |  48.67 $\scriptsize{\pm}$ 9.02   |   64.00 $\scriptsize{\pm}$ 0.00  |   **64.37 $\pm$ 0.50**  |

### For Other Comments Or Suggestions<a id="9xQG_O"></a>
The forget class (Mushroom) is one of the classes used in the main paper. $t=5$ is the VGE seleted checkpoint.
#### Ablation experiments on the selection of the early stopping epoch (under class unlearning).
| Metric | Original | Retrain | $t=1$ | $t=3$ | $t=5$ | $t=7$ | $t=9$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ | 90.54 $\scriptsize{\pm}$ 0.00 | **90.56 $\scriptsize{\pm}$ 0.83** | 80.52 $\scriptsize{\pm}$ 1.32 | 86.99 $\scriptsize{\pm}$ 0.73 | **91.45 $\scriptsize{\pm}$ 0.98** | 93.56 $\scriptsize{\pm}$ 0.62 | 94.71 $\scriptsize{\pm}$ 0.51 |
| $\mathcal{D}_f$ | 93.80 $\scriptsize{\pm}$ 0.00 | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** | **0.00 $\scriptsize{\pm}$ 0.00** |
| $\mathcal{D}_{test}$ | 51.94 $\scriptsize{\pm}$ 0.48 | **51.99 $\scriptsize{\pm}$ 0.69** | **51.92 $\scriptsize{\pm}$ 1.00** | 52.45 $\scriptsize{\pm}$ 0.40 | 52.40 $\scriptsize{\pm}$ 0.80 | 52.16 $\scriptsize{\pm}$ 0.51 | 52.55 $\scriptsize{\pm}$ 0.55 |

