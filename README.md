# ExplainableSafetyRegions

This repository contains data and code associated to the paper _Narteni, S., Carlevaro, A., Guzzi, J., Mongelli, M. (2024). Ensuring Safe Social Navigation via Explainable Probabilistic and Conformal Safety Regions. In: Longo, L., Lapuschkin, S., Seifert, C. (eds) Explainable Artificial Intelligence. xAI 2024. Communications in Computer and Information Science, vol 2156. Springer, Cham. https://doi.org/10.1007/978-3-031-63803-9_22_

The paper deals with simulated social robotics navigation problem that involves a fleet of mobile agents moving in a Cross scenario, governed by a human-
like behavior. With the purpose of avoiding collisions among them, we show how safe and explainable AI (XAI) methods can constitute useful tools to tailor the parameters of the behavior towards a safe, collision-free, navigation. 

The overall flowchart is depicted below:

<img width="600" alt="Schermata 2024-04-10 alle 14 24 38" src="https://github.com/saranrt95/ExplainableSafetyRegions/assets/77918497/9aaa91ab-9a29-4844-98c2-a4c3ca395628">


# Usage

1) **Simulation and dataset collection**: run the `getdataset.py` script with the YAML settings contained in `config.yaml` file. Dataset used in 

2) **Native rule generation**: run `SkopeRules.ipynb` for training skope-rules model, and `NativeXAI_performance.ipynb` for its evaluation (along with evaluation of Logic Learning Machine model, which is trained within Rulex platform).

3) **Scalable Classifiers for Probabilistic/Conformal safety regions**: run `ConfidenceRegions_SVM.ipynb`

4) **Local Rule Extraction from PSR/CSR**: run `Anchor_PSR.ipynb`, `Anchor_CSR.ipynb` for Anchors extraction, and `AnchorAnalysis_PSR.ipynb`, `AnchorAnalysis_CSR.ipynb`for their evaluation.

# Citation and reference

If you want to use our code for your experiments, please cite our paper.

For further information, please contact us at: sara.narteni@cnr.it, alberto.carlevaro@ieiit.cnr.it

