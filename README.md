# Literature-
Summaries of papers I have already read during my research as a PhD student.

## Index
- [All Papers](#all-papers)
- [System Identification](#system-identification)
- [Reinforcement Learning](#reinforcement-learning)
- [Deep Learning](#deep-learning)
- [Data-Driven Control](#data-driven-control)
- [Fluid Resuscitation](#fluid-resuscitation)
- [[Data Augmentation]](#data-augmentation)

****

### [All papers:](#all-papers)

- [Papers read in 2022](#papers-read-in-2022)
- [Papers read in 2021](#papers-read-in-2021)
- [Papers read in 2020](#papers-read-in-2020)

#### [Papers read in 2022](#papers-read-in-2022)

##### [18-1-22] [paper#14]
- **Time Series Data Augmentation for Deep Learning: A Survey** [[pdf]](https://arxiv.org/abs/2002.12478)
- *Qingsong Wen, Liang Sun, Fan Yang, Xiaomin Song, Jingkun Gao, Xue Wang, Huan Xu*
- [[Deep Learning]](#deep-learning) [[Data Augmentation]](#data-augmentation)
- ```Very well-written and well-organized.```
- ```Different methods to duplicate (or increase) the whole time-series. For example, if we have samples for 10 subjects, these methods help us to have samples for 30 subjects.```
- ```But, I need some method to increase the samples in one time-series, like interpolation```

##### [14-1-22] [paper#13]
- **Probabilistic Robust Autoencoders for Anomaly Detection** [[pdf]](https://arxiv.org/abs/2110.00494)
- *Y Aizenbud, O Lindenbaum, Y Kluger*
- [[Deep Learning]](#deep-learning)

##### [13-1-22] [paper#12]
- **Learning Robust Auto-Encoders With Regularizer for Linearity and Sparsity** [[pdf]](https://ieeexplore.ieee.org/abstract/document/8630910)
- *Y Shi, M Lei, R Ma, L Niu*
- [[Deep Learning]](#deep-learning)
- ``` need to be studied in more details.```

##### [13-1-22] [paper#11]
- **A recurrent neural network approach to predicting hemoglobin trajectories in patients with End-Stage Renal Disease** [[pdf]](https://www.sciencedirect.com/science/article/pii/S0933365719307304)
- *Benjamin Loboa, Emaad Abdel, Rahmanc Donald, Browna Lori, Dunnb Brendan Bowmanc*
- [[Deep Learning]](#deep-learning)
- ``` In this work the hemoglobin predictions are patient specific, and they are predicted using a recurrent neural network.```
- ``` this work is just a machine learning method, No mathematical model or control strategy is used.```

##### [12-1-22] [paper#10]
- **Reinforcement Learning-based Control of Tumor Growth under Anti-angiogenic Therapy** [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S016926071831887X)
- *Parisa Yazdjerdi, Nader Meskin, Mohammad Al-Naemi, Ala-Eddin Al Moustafa, Levente Kov«acs*
- [[Reinforcement Learning]](#reinfocement-learning) [[Data-Driven Control]](#data-driven-control)
- ``` Same approach as papaer #9 for another mathematical model of cancer.```

##### [10-1-22] [paper#9]
- **Reinforcement learning-based control of drug dosing for cancer chemotherapy treatment** [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0025556417304327)
- *Regina Padmanabhana, NaderMeskinaWassim, M.Haddadb*
- [[Reinforcement Learning]](#reinfocement-learning) [[Data-Driven Control]](#data-driven-control)
- ```They used a mathematical model as an environment for RL, where Tumor cells and chemotherapy drug are states and actions of the environment, respectively.```
- ```An online learning approach, which means we need the mathematical model of the system anyway.```

##### [9-1-22] [paper#8]
- **Reinforcement Learning in System Identification** [[pdf]](https://www.researchgate.net/publication/221786764_Reinforcement_Learning_in_System_Identification) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%238.pdf)
- *Mariela Cerrada, Jose Aguilar*
- [[Reinforcement Learning]](#reinforcement-learning) [[System Identification]](#system-identification)
- ``` Online learning based on RL algorithm is used for identification of nonlinear System```

##### [8-1-22] [paper#7]
- **Individualized Goal-Directed Therapy: The Challenge With the Fluids** [[pdf]](https://journals.lww.com/anesthesia-analgesia/Fulltext/2020/03000/Individualized_Goal_Directed_Therapy__The.8.aspx) [[highlited pdf]](https://github.com/elham24471/Literature-/blob/main/Highlited%20pdfs/Individualized_Goal_Directed_Therapy__The.8.pdf)
- *Tim G. Kampmeier, PhD, and Christian Ertmer, PhD*
- [[Fluid Resuscitation]](#fluid-resuscitation) 

##### [7-1-22] [paper#6]
- **Convex Optimization In Identification Of Stable Non-Linear State Space Models** [[pdf]](https://www.researchgate.net/publication/46583979_Convex_Optimization_In_Identification_Of_Stable_Non-Linear_State_Space_Models) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Sammary%20of%20paper%236.docx) [[Code]](https://github.com/elham24471/Literature-/blob/main/Symmaries/spot_manual.pdf)
- *Mark M. Tobenkin, Ian R. Manchester, Jennifer Wang, Alexandre Megretski, Russ Tedrake1*
- [[System Identification]](#system-identification)

##### [2-1-22] [paper#5]
- **Fluid resuscitation in paediatric burns: how do we get it right? A systematic review of the evidence.** [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30262511/) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%235.pdf)
- *Christopher Stutchfield, Anna Davies, Amber Young*
- [[Fluid Resuscitation]](#fluid-resuscitation)
- ```A review paper, mostly about different kinds of endpoints used in fluid resuscitation.```
- ```Three endpoints: 1)UO with vital signs 2)albumin 3)haemodynamic variables.```
- ```There is no significant conclusion about which endoint is better. They made just a comparison.```
- ```A good source when it comes to writting a literature review.```


#### [Papers read in 2021](#papers-read-in-2021)

##### [28-12-21] [paper#4]
- **Deep State Space Models for Nonlinear System Identification.** [[pdf]](https://arxiv.org/abs/2003.14162) [[code]](https://github.com/dgedon/DeepSSM_SysID)
- *Daniel Gedon, Niklas Wahlström, Thomas B. Schön, Lennart Ljung*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ```very well-written and useful. trying to understand the code and use the function for my own purpose```

##### [24-12-21] [paper#3]
- **Structured Inference Networks for Nonlinear State Space Models.** [[pdf]](https://arxiv.org/abs/1609.09869) [[code]](https://github.com/clinicalml/structuredinference) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%233.pdf)
- *Rahul G. Krishnan, Uri Shalit, David Sontag*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ```Useful but HARD TO FOLLOW```

##### [21-12-21] [paper#2]
- **Learning nonlinear state-space models using deep autoencoders.** [[pdf]](https://ieeexplore.ieee.org/document/8619475) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%232.pdf)
- *Daniele Masti; Alberto Bemporad*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ``` very well-written and useful. Trying to impelemnt it to gain a better understanding of SSM and AEs.```

##### [20-12-21] [paper#1]
- **Control Oriented Modeling and Identification of Nonlinear Systems.** [[pdf]](https://www.scientific.net/AMM.841.330)
- *Ali Emami,  Afshin Banazadeh*
- [[System Identification]](#system-identification)
- ```In this paper a low-order equivalent linear model of the nonlinear system is obtained.```
- ```Didn't find it useful for my purpose.```
- ```Practical for identification using frequency domain analysis where small number of points in iteration identification are needed.```

### [System Identification](#system-identification)

##### [20-12-21] [paper#1]
- **Control Oriented Modeling and Identification of Nonlinear Systems.** [[pdf]](https://www.scientific.net/AMM.841.330)
- *Ali Emami,  Afshin Banazadeh*
- [[System Identification]](#system-identification)
- ```In this paper a low-order equivalent linear model of the nonlinear system is obtained.```
- ```Didn't find it useful for my purpose.```
- ```Practical for identification using frequency domain analysis where small number of points in iteration identification are needed.```

##### [7-1-22] [paper#6]
- **Convex Optimization In Identification Of Stable Non-Linear State Space Models** [[pdf]](https://www.researchgate.net/publication/46583979_Convex_Optimization_In_Identification_Of_Stable_Non-Linear_State_Space_Models) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Sammary%20of%20paper%236.docx) [[Code]](https://github.com/elham24471/Literature-/blob/main/Symmaries/spot_manual.pdf)
- *Mark M. Tobenkin, Ian R. Manchester, Jennifer Wang, Alexandre Megretski, Russ Tedrake1*
- [[System Identification]](#system-identification)[[Robust System Identification]](#robust-system-identification)

##### [9-1-22] [paper#8]
- **Reinforcement Learning in System Identification** [[pdf]](https://www.researchgate.net/publication/221786764_Reinforcement_Learning_in_System_Identification) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%238.pdf)
- *Mariela Cerrada, Jose Aguilar*
- [[Reinforcement Learning]](#reinforcement-learning) [[System Identification]](#system-identification)
- ``` Online learning based on RL algorithm is used for identification of nonlinear System```

##### [28-12-21] [paper#4]
- **Deep State Space Models for Nonlinear System Identification.** [[pdf]](https://arxiv.org/abs/2003.14162) [[code]](https://github.com/dgedon/DeepSSM_SysID)
- *Daniel Gedon, Niklas Wahlström, Thomas B. Schön, Lennart Ljung*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ```very well-written and useful. trying to understand the code and use the function for my own purpose```

##### [24-12-21] [paper#3]
- **Structured Inference Networks for Nonlinear State Space Models.** [[pdf]](https://arxiv.org/abs/1609.09869) [[code]](https://github.com/clinicalml/structuredinference) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%233.pdf)
- *Rahul G. Krishnan, Uri Shalit, David Sontag*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ```Useful but HARD TO FOLLOW```

##### [21-12-21] [paper#2]
- **Learning nonlinear state-space models using deep autoencoders.** [[pdf]](https://ieeexplore.ieee.org/document/8619475) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%232.pdf)
- *Daniele Masti; Alberto Bemporad*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ``` very well-written and useful. Trying to impelemnt it to gain a better understanding of SSM and AEs.```

### [Reinforcement Learning](#reinforcement-learning)

##### [12-1-22] [paper#10]
- **Reinforcement Learning-based Control of Tumor Growth under Anti-angiogenic Therapy** [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S016926071831887X)
- *Parisa Yazdjerdi, Nader Meskin, Mohammad Al-Naemi, Ala-Eddin Al Moustafa, Levente Kov«acs*
- [[Reinforcement Learning]](#reinfocement-learning) [[Data-Driven Control]](#data-driven-control)
- ``` Same approach as papaer #9 for another mathematical model of cancer.```

##### [10-1-22] [paper#9]
- **Reinforcement learning-based control of drug dosing for cancer chemotherapy treatment** [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0025556417304327)
- *Regina Padmanabhana, NaderMeskinaWassim, M.Haddadb*
- [[Reinforcement Learning]](#reinfocement-learning) [[Data-Driven Control]](#data-driven-control)
- ```They used a mathematical model as an environment for RL, where Tumor cells and chemotherapy drug are states and actions of the environment, respectively.```
- ```An online learning approach, which means we need the mathematical model of the system anyway.```

##### [9-1-22] [paper#8]
- **Reinforcement Learning in System Identification** [[pdf]](https://www.researchgate.net/publication/221786764_Reinforcement_Learning_in_System_Identification) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%238.pdf)
- *Mariela Cerrada, Jose Aguilar*
- [[Reinforcement Learning]](#reinforcement-learning) [[System Identification]](#system-identification)
- ``` Online learning based on RL algorithm is used for identification of nonlinear System```

### [Deep Learning](#deep-learning)

##### [18-1-22] [paper#14]
- **Time Series Data Augmentation for Deep Learning: A Survey** [[pdf]](https://arxiv.org/abs/2002.12478)
- *Qingsong Wen, Liang Sun, Fan Yang, Xiaomin Song, Jingkun Gao, Xue Wang, Huan Xu*
- [[Deep Learning]](#deep-learning) [[Data Augmentation]](#data-augmentation)
- ```Very well-written and well-organized```
- ```ways to duplicate the whole time-series. I need some method to increase the samples in one time-series, like interpolation```

##### [14-1-22] [paper#13]
- **Probabilistic Robust Autoencoders for Anomaly Detection** [[pdf]](https://arxiv.org/abs/2110.00494)
- *Y Aizenbud, O Lindenbaum, Y Kluger*
- [[Deep Learning]](#deep-learning)

##### [13-1-22] [paper#12]
- **Learning Robust Auto-Encoders With Regularizer for Linearity and Sparsity** [[pdf]](https://ieeexplore.ieee.org/abstract/document/8630910)
- *Y Shi, M Lei, R Ma, L Niu*
- [[Deep Learning]](#deep-learning)
- ``` need to be studied in more details.```

##### [13-1-22] [paper#11]
- **A recurrent neural network approach to predicting hemoglobin trajectories in patients with End-Stage Renal Disease** [[pdf]](https://www.sciencedirect.com/science/article/pii/S0933365719307304)
- *Benjamin Loboa, Emaad Abdel, Rahmanc Donald, Browna Lori, Dunnb Brendan Bowmanc*
- [[Deep Learning]](#deep-learning)
- ``` In this work the hemoglobin predictions are patient specific, and they are predicted using a recurrent neural network.```
- ``` this work is just a machine learning method, No mathematical model or control strategy is used.```

##### [28-12-21] [paper#4]
- **Deep State Space Models for Nonlinear System Identification.** [[pdf]](https://arxiv.org/abs/2003.14162) [[code]](https://github.com/dgedon/DeepSSM_SysID)
- *Daniel Gedon, Niklas Wahlström, Thomas B. Schön, Lennart Ljung*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ```very well-written and useful. trying to understand the code and use the function for my own purpose```

##### [24-12-21] [paper#3]
- **Structured Inference Networks for Nonlinear State Space Models.** [[pdf]](https://arxiv.org/abs/1609.09869) [[code]](https://github.com/clinicalml/structuredinference) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%233.pdf)
- *Rahul G. Krishnan, Uri Shalit, David Sontag*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ```Useful but HARD TO FOLLOW```

##### [21-12-21] [paper#2]
- **Learning nonlinear state-space models using deep autoencoders.** [[pdf]](https://ieeexplore.ieee.org/document/8619475) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%232.pdf)
- *Daniele Masti; Alberto Bemporad*
- [[System Identification]](#system-identification) [[Deep Learning]](#deep-learning)
- ``` very well-written and useful. Trying to impelemnt it to gain a better understanding of SSM and AEs.```

### [Data-Driven Control](#data-driven-control)

##### [12-1-22] [paper#10]
- **Reinforcement Learning-based Control of Tumor Growth under Anti-angiogenic Therapy** [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S016926071831887X)
- *Parisa Yazdjerdi, Nader Meskin, Mohammad Al-Naemi, Ala-Eddin Al Moustafa, Levente Kov«acs*
- [[Reinforcement Learning]](#reinfocement-learning) [[Data-Driven Control]](#data-driven-control)
- ``` Same approach as papaer #9 for another mathematical model of cancer.```

##### [10-1-22] [paper#9]
- **Reinforcement learning-based control of drug dosing for cancer chemotherapy treatment** [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0025556417304327)
- *Regina Padmanabhana, NaderMeskinaWassim, M.Haddadb*
- [[Reinforcement Learning]](#reinfocement-learning) [[Data-Driven Control]](#data-driven-control)
- ```They used a mathematical model as an environment for RL, where Tumor cells and chemotherapy drug are states and actions of the environment, respectively.```
- ```An online learning approach, which means we need the mathematical model of the system anyway.```

### [Fluid Resuscitation](#fluid-resuscitation)

##### [8-1-22] [paper#7]
- **Individualized Goal-Directed Therapy: The Challenge With the Fluids** [[pdf]](https://journals.lww.com/anesthesia-analgesia/Fulltext/2020/03000/Individualized_Goal_Directed_Therapy__The.8.aspx) [[highlited pdf]](https://github.com/elham24471/Literature-/blob/main/Highlited%20pdfs/Individualized_Goal_Directed_Therapy__The.8.pdf)
- *Tim G. Kampmeier, PhD, and Christian Ertmer, PhD*
- [[Fluid Resuscitation]](#fluid-resuscitation) 

##### [2-1-22] [paper#5]
- **Fluid resuscitation in paediatric burns: how do we get it right? A systematic review of the evidence.** [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30262511/) [[Summary]](https://github.com/elham24471/Literature-/blob/main/Symmaries/Summary%20of%20paper%235.pdf)
- *Christopher Stutchfield, Anna Davies, Amber Young*
- [[Fluid Resuscitation]](#fluid-resuscitation)
- ```A review paper, mostly about different kinds of endpoints used in fluid resuscitation.```
- ```Three endpoints: 1)UO with vital signs 2)albumin 3)haemodynamic variables.```
- ```There is no significant conclusion about which endoint is better. They made just a comparison.```
- ```A good source when it comes to writting a literature review.```

### [Data Augmentation](#data-augmentation)

##### [18-1-22] [paper#14]
- **Time Series Data Augmentation for Deep Learning: A Survey** [[pdf]](https://arxiv.org/abs/2002.12478)
- *Qingsong Wen, Liang Sun, Fan Yang, Xiaomin Song, Jingkun Gao, Xue Wang, Huan Xu*
- [[Deep Learning]](#deep-learning) [[Data Augmentation]](#data-augmentation)
- ```Very well-written and well-organized```
- ```ways to duplicate the whole time-series. I need some method to increase the samples in one time-series, like interpolation```
