# MemAE_AD

## Introduction
This project is a predictive maintenance AI model that utilizes data and machine learning to achieve efficient facility management. It was developed to overcome challenges in the manufacturing industry, such as the difficulty in identifying and addressing process issues, and the resulting increase in manufacturing losses.

## Developer
- **Seungje Seong** : [GitHub](https://github.com/Trouvler)

## Development Environment
- **Language** : Python
- **Framework** : PyTorch

## Key Features
- **Advanced Anomaly Detection**: Overcomes the limitations of traditional Auto Encoders—which often fail to distinguish anomalies that closely resemble normal data during reconstruction—by integrating a Memory Auto Encoder (MemAE) with adversarial learning.
- **Stable Training Architecture**: Resolves the training instability commonly found in GAN-based anomaly detection models by securely combining it with an AE-based structure.
- **Fast and Accurate**: Features a highly efficient and simple structure based on unsupervised learning, ensuring rapid processing speeds and high accuracy.
- **Manufacturing Optimization**: Readily applicable to various manufacturing processes in small and medium-sized enterprises. This helps businesses increase process management efficiency, prevent unexpected accidents, and boost overall profitability.


## Usage
1. **Download**
   Clone the repository to your local environment:
   ```bash
   git clone https://github.com/sng-j/MemAE_AD.git
   ```

2. **Run**
   Set up your environment with Python and PyTorch. Then, open and run the provided Jupyter Notebooks (`main.ipynb.ipynb` or `EDA.ipynb`) to explore the data, train the model, and perform evaluations.

## License
MIT License

## References
- Kingma, Diederik P., and Max Welling. "Auto-encoding variational bayes." *arXiv preprint arXiv:1312.6114* (2013).
- Gong, Dong, et al. "Memorizing normality to detect anomaly: Memory-augmented deep autoencoder for unsupervised anomaly detection." *Proceedings of the IEEE/CVF International Conference on Computer Vision*. 2019.
- Audibert, Julien, et al. "Usad: Unsupervised anomaly detection on multivariate time series." *Proceedings of the 26th ACM SIGKDD international conference on knowledge discovery & data mining*. 2020.
