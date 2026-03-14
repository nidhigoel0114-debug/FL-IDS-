**Trust-Aware Privacy-Preserving Federated Learning for Robust Cross-Dataset Network Intrusion Detection**
This project implements a Trust-Aware Privacy-Preserving Federated Learning framework for Network Intrusion Detection Systems (NIDS). The system enables multiple distributed clients to collaboratively train a global model without sharing raw data, ensuring data privacy and secure model aggregation.

The framework introduces a trust-based aggregation mechanism that evaluates the reliability of client updates using a trust score derived from accuracy contribution, update stability, and similarity to the global model. This helps reduce the impact of unreliable or malicious clients during federated training.

To further strengthen security and robustness, the model incorporates differential privacy, adversarial robustness testing, and cross-dataset evaluation. Experiments are conducted on multiple intrusion detection datasets including CICIDS2017, UNSW-NB15, and Bot-IoT, demonstrating strong generalization across heterogeneous network environments.

**Key features include:**

Federated learning architecture for decentralized IDS training
Trust-weighted model aggregation to mitigate unreliable client updates
Differential privacy mechanisms for enhanced data protection
Adversarial robustness evaluation using FGSM attacks
Cross-dataset intrusion detection performance analysis
Comprehensive experimental evaluation with ablation studies

The proposed approach improves security, privacy, and robustness of collaborative intrusion detection systems while maintaining high detection accuracy across diverse network datasets.

**Outcomes of the project**
Developed a Trust-Aware Federated Learning framework for distributed network intrusion detection without sharing raw data.
Implemented trust-weighted model aggregation to evaluate and prioritize reliable client updates during federated training.
Integrated privacy-preserving mechanisms using differential privacy to protect sensitive network data.
Demonstrated robustness against adversarial attacks through FGSM-based adversarial evaluation.
Achieved strong cross-dataset generalization performance across CICIDS2017, UNSW-NB15, and Bot-IoT datasets.
Conducted ablation studies to analyze the contribution of trust scoring, privacy mechanisms, and robustness techniques.
Provided comprehensive evaluation metrics including accuracy, balanced accuracy, macro F1-score, ROC-AUC, and adversarial robustness.

**Dataset links**
1.CICIDS-2017: https://www.kaggle.com/datasets/cicdataset/cicids2017
2.UNSW-NB15: https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15
3.Bot-IoT:https://www.kaggle.com/datasets/gauravduttakiit/bot-iot


**Reference links**
1.CICIDS-2017: https://www.unb.ca/cic/datasets/ids-2017.html
2.UNSW-NB15: https://research.unsw.edu.au/projects/unsw-nb15-dataset
3.Bot-IoT:https://research.unsw.edu.au/projects/bot-iot-dataset

