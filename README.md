# **Financial Machine Learning Laboratory**

A comprehensive machine learning laboratory for financial time series analysis and cryptocurrency price prediction using BTC/USDT 1-hour candlestick market data.

> **Note**:
This is an educational project focused on demonstrating modern financial ML workflows rather than providing a production trading system.

## **Project Structure**

```bash
finml-lab/
├── notebooks/  # Jupyter notebooks with complete ML pipeline
├── data/       # Processed datasets (created during execution)
└── models/     # Trained models (created during execution)
```

- Each notebook contains detailed comments explaining every step of the process, making it easy to follow along and understand the implementation details.
- If you're only interested in the dataset, check out the dataset on [Hugging Face Hub](https://huggingface.co/datasets/Sierra-Arn/finml-lab-data).
- If you want to experiment with the models, see the trained model on [Hugging Face Hub](https://huggingface.co/Sierra-Arn/finml-lab-xgboost).

## **Quick Start**

### **Prerequisites**
- [Pixi](https://pixi.sh/latest/ ) package manager.
- [Data Wrangler](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.datawrangler) extension for VS Code by Microsoft (optional, for data exploration). 

### **Setup and Execution**

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sierra-Arn/finml-lab.git
   cd finml-lab
   ```

2. **Install dependencies**
   ```bash
   pixi install
   ```

3. **Execute the notebooks sequentially in numerical order**

## **License**

This project is licensed under the [BSD-3-Clause License](LICENSE).