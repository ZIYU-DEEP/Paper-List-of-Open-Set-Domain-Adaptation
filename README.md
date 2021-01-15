# Paper List of Open Set Domain Adaptation

Only until 2017, people started to study "open set" domain adaptation. The presence of open set leads to negative transfer due to incorrect labelling on unknown classes.  

The major difference from anomaly detection problem is that this type of study assumes the samples in the target (test) domain is representative, while in anomaly detection this is usually impractical.


**Open Set Domain Adaptation** [[link](https://openaccess.thecvf.com/content_ICCV_2017/papers/Busto_Open_Set_Domain_ICCV_2017_paper.pdf)]  
*ICCV, 2017*
> - **Problem**: In classification problems, the source domain may not share the same label set as the target doamin, causing incorrect labeling.
> - **Method**: The paper proposes a model to isolate unknown samples to avoid negative transfer.
> - **Technical Details**: It is required to have an representative sample of the target domain, which is unachievable for anomaly detection tasks.

<br>

**Open Set Domain Adaptation by Backpropagation** [[link](https://arxiv.org/abs/1804.10427)]  
*ECCV, 2018*
> **Method**: Training a classifier to tell known and unknown classes through adversarial loss.
<br>

**Universal Domain Adaptation** [[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/You_Universal_Domain_Adaptation_CVPR_2019_paper.pdf)]  
*CVPR, 2019*   
> **Method**: Training a domain discriminator and label classifier together.
<br>

**Learning Factorized Representations for Open-Set Domain Adaptation** [[link](https://openreview.net/forum?id=SJe3HiC5KX)]  
*ICLR, 2019*  
> **Method**: Factorizing the target space into a known and an unknown space.
<br>

**Open Set Domain Adaptation via Progressive Separation** [[link](https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Separate_to_Adapt_Open_Set_Domain_Adaptation_via_Progressive_Separation_CVPR_2019_paper.pdf)]    
*CVPR, 2019*
> **Method**: Using mutli-binary classifiers to separate known and unknown classes.
<br>

**Open Set Domain Adaptation: Theoretical Bound and Algorithm** [[link](https://arxiv.org/abs/1907.08375)]  
*IEEE-TNNLS, 2020*
> - **Theory**: This paper derives an error bound on target samples, which consists of **source risk**, **domain discrepancy**, and **open-set risk**.
