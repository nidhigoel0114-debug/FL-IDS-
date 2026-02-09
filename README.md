**ZT-TrustFed – Privacy-Preserving Federated Intrusion Detection System**
This project proposes ZT-TrustFed, a Zero-Trust, privacy-preserving Federated Learning (FL) framework for Intrusion Detection Systems (IDS). The goal is to detect cyber-attacks accurately without sharing raw network data, thereby preserving data privacy while maintaining high detection performance.Unlike centralized IDS approaches, ZT-TrustFed trains a deep learning model collaboratively across multiple clients (simulated organizations or network nodes). Each client performs local training, and only model updates are shared with the central server. To enhance security and reliability, the system integrates three key mechanisms:

1.Zero-Trust Principle – No client is assumed to be trustworthy by default. Each client is continuously evaluated using a dynamic trust score based on its behavior during training.
2.Trust-Aware Aggregation – A Trust-Krum aggregation strategy is used to reduce the impact of unreliable or malicious clients, improving robustness against poisoning and Byzantine attacks.
3.Privacy Preservation – Differential Privacy (DP) noise is added to model gradients to prevent leakage of sensitive information from client updates.

The framework also includes a lightweight ledger mechanism to log aggregation events, improving transparency and auditability of the federated process.Extensive experiments demonstrate that ZT-TrustFed outperforms standard FedAvg in terms of accuracy, F1-score, and robustness, while maintaining privacy guarantees. Statistical validation using paired t-test and Wilcoxon signed-rank test confirms that the performance improvements are statistically significant.

Outcomes of the project
1.High intrusion detection accuracy with strong class balance
2.Robustness against untrusted or malicious clients
3.Privacy-preserving training without raw data sharing
4.Statistically validated performance gains
