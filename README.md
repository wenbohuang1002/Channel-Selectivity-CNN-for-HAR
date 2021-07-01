# [IEEE JBHI 2021]Channel-Selectivity-CNN-for-HAR
[IEEE JBHI 2021] The convolutional neural networks training with Channel-Selectivity for human activity recognition based on sensors
![Model](https://github.com/wenbohuang1002/-IEEE-JBHI-2021-Channel-Selectivity-CNN-for-HAR/blob/main/Images/Model.png)
## How to train
### UCI-HAR dataset
```
# Baseline for UCI-HAR
$ python Net_UCI_B.py
# Baseline + Channel-selectivity for UCI-HAR
$ python Net_UCI_SC.py
# ResNet for UCI-HAR
$ python Net_UCI_ReB.py
# ResNet + Channel-selectivity for UCI-HAR
$ python Net_UCI_ReSC.py
```
### OPPORTUNITY dataset
```
# Baseline for OPPORTUNITY
$ python Net_Opportunity_B.py
# Baseline + Channel-selectivity for OPPORTUNITY
$ python Net_Opportunity_SC.py
# ResNet for OPPORTUNITY
$ python Net_Opportunity_ReB.py
# ResNet + Channel-selectivity for OPPORTUNITY
$ python Net_Opportunity_ReSC.py
```
### PAMAP2 dataset
```
# Baseline for PAMAP2
$ python Net_pamap2_B.py
# Baseline + Channel-selectivity for PAMAP2
$ python Net_pamap2_SC.py
# ResNet for PAMAP2
$ python Net_pamap2_ReB.py
# ResNet + Channel-selectivity for PAMAP2
$ python Net_pamap2_ReSC.py
```
### UniMiB-SHAR dataset
```
# Baseline for UniMiB-SHAR
$ python Net_unimib_B.py
# Baseline + Channel-selectivity for UniMiB-SHAR
$ python Net_unimib_SC.py
# ResNet for UniMiB-SHAR
$ python Net_unimib_ReB.py
# ResNet + Channel-selectivity for UniMiB-SHAR
$ python Net_unimib_ReSC.py
```
### WISDM dataset
```
# Baseline for WISDM
$ python Net_wisdm_B.py
# Baseline + Channel-selectivity for WISDM
$ python Net_wisdm_SC.py
# ResNet for WISDM
$ python Net_wisdm_ReB.py
# ResNet + Channel-selectivity for WISDM
$ python Net_wisdm_ReSC.py
```
## Citation
If you find Channel-Selectivity CNN for HAR useful in your research, please consider citing.
```
@article{huang2021convolutional,
  title={The convolutional neural networks training with Channel-Selectivity for human activity recognition based on sensors},
  author={Huang, Wenbo and Zhang, Lei and Teng, Qi and Song, Chaoda and He, Jun},
  journal={IEEE Journal of Biomedical and Health Informatics},
  year={2021},
  publisher={IEEE}
}
```
