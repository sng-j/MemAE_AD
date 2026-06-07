Introduction
This project is a predictive maintenance AI model utilizing a Memory Auto Encoder (MemAE) and Adversarial Learning for unsupervised anomaly detection. It is designed to overcome the difficulties of identifying process issues and taking action, ultimately reducing manufacturing losses and promoting efficient facility management for small and medium-sized manufacturing enterprises.

Key Features
Advanced Anomaly Detection: Overcomes the limitations of traditional Auto Encoders—which often fail to distinguish anomalies that closely resemble normal data—by integrating adversarial learning.

Stable Training Architecture: Resolves the training instability commonly found in GAN-based anomaly detection models by combining it securely with an AE-based structure.

Fast and Accurate: Features a highly efficient, simple structure based on unsupervised learning, ensuring rapid processing speeds and high accuracy without the need for labeled data.

Manufacturing Optimization: Readily applicable to various manufacturing processes, helping businesses increase management efficiency, prevent unexpected accidents, and boost overall profitability.

Development Environment: Built entirely with Python and the PyTorch framework.

Usage
Download: Clone the repository to your local environment.

Bash
git clone https://github.com/sng-j/MemAE_AD.git
2. **Run:** Install the required dependencies and execute the training/evaluation scripts.

## License
MIT License

---
**References**
*   Kingma, Diederik P., and Max Welling. "Auto-encoding variational bayes." *arXiv preprint arXiv:1312.6114* (2013).
*   Gong, Dong, et al. "Memorizing normality to detect anomaly: Memory-augmented deep autoencoder for unsupervised anomaly detection." *Proceedings of the IEEE/CVF International Conference on Computer Vision*. 2019.
*   Audibert, Julien, et al. "Usad: Unsupervised anomaly detection on multivariate time series." *Proceedings of the 26th ACM SIGKDD international conference on knowledge discovery & data mining*. 2020.
