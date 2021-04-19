# Reliability-Aware Circuit Design

Brief summary of papers in reliability-aware circuit design

### Survey
| Title | Year | Published in | Brief Summary |
| :---: | :--: | :----------: | :-----: |
| Reliable on-chip systems in the nano-era: Lessons learnt and future trends | 2013 | DAC |  |

### Aging Monitoring

| Title | Year | Published in | Brief Summary |
| :---: | :--: | :----------: | :-----: |
| Chip health tracking using dynamic in-situ delay monitoring | 2019 | DATE | monitor multiple paths to get "monitor excitation rate" |
| Re-using BIST for circuit aging monitoring | 2015 | ETS | reuse BIST |
| Using programmable delay monitors for wear-out and early life failure prediction | 2020 | DATE | reuse "FAST" | 
| An efficient method to identify critical gates under circuit aging | 2007 | ICCAD | use search algorithm to identify critical gates |
| Representative critical-path selection for aging-induced delay monitoring | 2013 | ITC | select representative critical-path and predict delay |
| Circuit failure prediction and its application to transistor aging | 2007 | VTS | monitor guardband violation |
| Predictive error detection by on-line aging monitoring | 2010 | IOLTS | monitor critical path delay |
| A distributed critical-path timing monitor for a 65nm high-performance microprocessor | 2007 | ISSCC | monitor critical-path, edge detection |
| Early Selection of Critical Paths for Reliable NBTI Aging-Delay Monitoring | 2016 | TVLSI | early selection of CPs without spatial correlation information from circuit layout |
| Aging-and variation-aware delay monitoring using representative critical path selection | 2015 | TODAES |  |

### Aging Analysis/Prediction

| Title | Year | Published in | Brief Summary |
| :---: | :--: | :----------: | :-----: |
| Aadam: A Fast, Accurate, and Versatile Aging-Aware Cell Library Delay Model using Feed-Forward Neural Network | 2020 | ICCAD | Feed-forward network |
| Prognosis of NBTI aging using a machine learning scheme | 2016 | DFT | multivariate adaptive regression splines |
| Real-time prediction for IC aging based on machine learning | 2019 | TIM | multivariate adaptive regression splines |
| Instruction-level NBTI stress estimation and its application in runtime aging prediction for embedded processors | 2018 | TCAD | linear regression |
| On-line prediction of NBTI-induced aging rates | 2015 | DATE | linear regression | 
| Design of reliable SoCs with BIST hardware and machine learning | 2017 | TVLSI | Compare SVM(with ECC), TreeBagger, random forest, Adaboost, basic regression | 
| Fine-grained aging-induced delay prediction based on the monitoring of run-time stress | 2016 | TCAD | SVM |
| Aging-aware chip health prediction adopting an innovative monitoring strategy | 2019 | ASPDAC | SVM |
| Fine-grained aging prediction based on the monitoring of run-time stress using DfT infrastructure | 2015 | ICCAD | SVM |
| Aging-aware scheduling and binding in high-level synthesis considering workload effects | 2020 | Microelectronics Reliability | SVM |
| Re-using BIST for circuit aging monitoring | 2015 | ETS | SVM |
| On-chip droop-induced circuit delay prediction based on support-vector machines | 2015 | TCAD | SVM |
| Towards Reliability-Aware Circuit Design in Nanoscale FinFET Technology | 2017 | ICCAD | proposed algorithm | 
| NBTI and HCI Aging Prediction and Reliability Screening During Production Test | 2019 | TCAD | proposed algorithm |
| Circuit aging prediction for low-power operation | 2009 | CICC | Feature modeling, considering low-power technique |
| Remaining useful life prediction in embedded systems using an online auto-updated machine learning based modeling | 2021 | Microelectronics Reliability | nonlinear autoregressive (NAR) neural network |
| Statistical reliability analysis under process variation and aging effects | 2009 | DAC | gate aging statistical model |
| Optimized circuit failure prediction for aging: Practicality and promise | 2008 | ITC | Feature modeling |
| Unintrusive aging analysis based on offline learning | 2017 | DFT | Generalized Liner Model |
| Using machine learning to predict path-based slack from graph-based timing analysis | 2018 | ICCD |  |

### Design Framework

| Title | Year | Published in | Brief Summary |
| :---: | :--: | :----------: | :-----: |
| Reliability Aware Design and Lifetime Management of Computing Platforms | 2017 | TETC | A comprehensive design flow optimization method |
| Design for reliability Tradeoffs between lifetime and performance due to electromigration | 2021 | Microelectronics Reliability | DSE towards electromigration | 
| Reliability-and process-variation aware design of integrated circuits | 2008 | Microelectronics Reliability | reliability-aware design for logic and memory circuits |