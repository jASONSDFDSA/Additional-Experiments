# Additional Experiments

## For Reviewer BzXw
### For Methods And Evaluation Criteria
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

## For Reviewer WHHW

### For Methods And Evaluation Criteria: M3 and Essential References Not Discussed
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


## For Reviewer 9xQG  

### For Claims And Evidence

#### C3<a id="C3"></a>

#### C4

### For Essential References Not Discussed

#### Random Subset Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | RUM | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |
| MIA |     |     |     |     |     |     |

#### Continual Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
| Metric | Original | Retrain | RUM | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |
| MIA |     |     |     |     |     |     |

#### Class Unlearning Experiment results on CIFAR-100 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | RUM | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |

##### Unlearning on class Mushroom.
| Metric | Original | Retrain | RUM | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |

#### Subclass Unlearning Experiment results on CIFAR-20 dataset with ResNet18 model.
##### Unlearning on class Rocket.
| Metric | Original | Retrain | RUM | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |

##### Unlearning on class Sea.
| Metric | Original | Retrain | RUM | SCRUB | Rewind-to-delete | VGE-BF|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |

### For Other Comments Or Suggestions
The forget class (Mushroom) is one of the classes used in the main paper. $t=5$ is the VGE seleted checkpoint.
#### Ablation experiments on the selection of the early stopping epoch (under class unlearning).
| Metric | Original | Retrain | $t=1$ | $t=3$ | $t=5$ | $t=7$ | $t=9$ |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| $\mathcal{D}_r$ |     |     |     |     |     |     |     |
| $\mathcal{D}_f$ |     |     |     |     |     |     |     |
| $\mathcal{D}_{test}$ |     |     |     |     |     |     |     |

### For Questions: A1
Please refer to [C3](#C3) for details.
## For Reviewer 4S8A
