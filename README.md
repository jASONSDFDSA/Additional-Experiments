# VGE
Additional Experiments
## Catalogue
- [For Reviewer BzXw](#BzXw)
   - [Methods And Evaluation Criteria](#BzXw_M)
- [For Reviewer WHHW](#WHHW)
  - [Methods And Evaluation Criteria: M3 and Essential References Not Discussed](#WHHW_M)
- [For Reviewer 9xQG](#9xQG)
  - [Claims And Evidence](#9xQG_C)
    - [C3](#9xQG_C3)
    - [C4](#9xQG_C4)
  - [Essential References Not Discussed](#9xQG_E)
  - [Other Comments Or Suggestions](#9xQG_O)


## For Reviewer BzXw<a id="BzXw"></a>
### For Methods And Evaluation Criteria<a id="BzXw_M"></a>
The forget classes are chosen randomly for fair comparison.
#### Random Subset Unlearning Experiment results on CUB dataset with ResNet18 model.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |
| MIA |     |     |     |     |     |     |     |     |

#### Continual Unlearning Experiment results on CUB dataset with ResNet18 model.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |
| MIA |     |     |     |     |     |     |     |     |

#### Class Unlearning Experiment results on CUB dataset with ResNet18 model.
##### Unlearning on class Lazuli_Bunting
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |

##### Unlearning on class Fish_Crow
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |

## For Reviewer WHHW<a id="WHHW"></a>

### For Methods And Evaluation Criteria: M3 and Essential References Not Discussed<a id="WHHW_M"></a>
The additional experiments here include additional metrics, such as "relearn time," on class unlearning and subclass unlearning, and an additional baseline method, SFR-on. The forget classes are chosen based on the setting in the work of SSD.

#### Random Subset Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | SFR-on | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |     |
| MIA |     |     |     |     |     |     |     |     |     |

#### Continual Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SSD | SFR-on | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |     |
| MIA |     |     |     |     |     |     |     |     |     |

#### Class Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SFR-on | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |     |
| Relearn Time |     |     |     |     |     |     |     |     |     |

##### Unlearning on class Mushroom.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SFR-on | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |     |
| Relearn Time |     |     |     |     |     |     |     |     |     |

#### Subclass Unlearning Experiment results on CIFAR-20 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SFR-on | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |     |
| Relearn Time |     |     |     |     |     |     |     |     |     |

##### Unlearning on class Sea.
| Metric | Original | Retrain | FT w/o $\mathcal{D}_f$ | Random | BadT | SalUn | SFR-on | SSD | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |     |     |
| Relearn Time |     |     |     |     |     |     |     |     |     |


## For Reviewer 9xQG<a id="9xQG"></a>

### For Answers to Questions: A1
Please refer to [C3](#9xQG_C3) for details.

### For Claims And Evidence<a id="9xQG_C"></a>

#### C3<a id="9xQG_C3"></a>

We used different value for the coefficient($\lambda$) to the loss on the forget set in NegGrad+ to update the model during gradient ascent.

$\lambda=0$

![NegGrad+_lambda0](assets/neggrad_images_resnet18_cifar100_0.pdf)

$\lambda=0.5$

![NegGrad+_lambda0.5](assets/neggrad_images_resnet18_cifar100_0.5.pdf)

$\lambda=1$

![NegGrad+_lambda1](assets/neggrad_images_resnet18_cifar100_1.pdf)

$\lambda=1.5$

![NegGrad+_lambda1.5](assets/neggrad_images_resnet18_cifar100_1.5.pdf)

$\lambda=2$

![NegGrad+_lambda2](assets/neggrad_images_resnet18_cifar100_2.pdf)

#### C4<a id="9xQG_C4"></a>
We set epoch the epoch for the retrained model to 10. Hyperparameters for other methods follow their experimental settings in their work.

| $t=5$ | $\mathcal{D}_r$ | $\mathcal{D}_f$ | $\mathcal{D}_{test}$ | MIA |
| :---: | :---: | :---: | :---: | :---: |
| Original |     |     |     |     |
| Retrain |     |     |     |     |
| FT w/o $\mathcal{D}_f$ |     |     |     |     |
| BadT |     |     |     |     |
| SalUn |     |     |     |     |
| $t=10$ | $\mathcal{D}_r$ | $\mathcal{D}_f$ | $\mathcal{D}_{test}$ | MIA |
| Original |     |     |     |     |
| Retrain |     |     |     |     |
| FT w/o $\mathcal{D}_f$ |     |     |     |     |
| BadT |     |     |     |     |
| SalUn |     |     |     |     |
| $t=15$ | $\mathcal{D}_r$ | $\mathcal{D}_f$ | $\mathcal{D}_{test}$ | MIA |
| Original |     |     |     |     |
| Retrain |     |     |     |     |
| FT w/o $\mathcal{D}_f$ |     |     |     |     |
| BadT |     |     |     |     |
| SalUn |     |     |     |     |


### For Essential References Not Discussed<a id="9xQG_E"></a>

#### Random Subset Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |
| MIA |     |     |     |     |     |

#### Continual Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |
| MIA |     |     |     |     |     |

#### Class Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |

##### Unlearning on class Mushroom.
| Metric | Original | Retrain |SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |

#### Subclass Unlearning Experiment results on CIFAR-20 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |

##### Unlearning on class Sea.
| Metric | Original | Retrain | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |

### For Other Comments Or Suggestions<a id="9xQG_O"></a>
The forget class (Mushroom) is one of the classes used in the main paper. $t=5$ is the VGE seleted checkpoint.
#### Ablation experiments on the selection of the early stopping epoch (under class unlearning).
| Metric | Original | Retrain | $t=1$ | $t=3$ | $t=5$ | $t=7$ | $t=9$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |


