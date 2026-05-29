# 📚 PersianILP: Construction and Evaluation of a Standard Persian Dataset for Inductive Link Prediction

## Abstract
<div align="justify">
Link prediction in knowledge graphs is a key task aimed at addressing the challenge of graph sparsity. In inductive link prediction, a model is trained on one graph and evaluated on another containing unseen entities. While twelve inductive datasets have been introduced for English to benchmark models in this domain, no such dataset exists for Persian. This study introduces **PersianILP**, the first Persian dataset designed for inductive link prediction. PersianILP is constructed through a purposeful combination of real-world data extracted from the Farsbase knowledge graph and synthetic data generated using the DeepSeek language model. To evaluate PersianILP, key criteria such as structural and semantic diversity, statistical alignment between synthetic and real data, and adherence to inductive evaluation principles were considered. The dataset is compared with twelve benchmark datasets, including WN18RR, FB237, and NELL995. PersianILP contains **191,415 semantic triples**, **49,951 entities**, and **2,728 unique relations**, exhibiting a highly sparse structure with a sparsity rate of **0.99**. Evaluation using a baseline inductive link prediction model confirms the dataset’s high quality and effectiveness. Statistical analyses further demonstrate that PersianILP meets all essential requirements for research in inductive link prediction and can serve as a standard resource for studies in Persian language processing, the semantic web, and recommender systems.
</div>

## ⚙️ Installation Requirements
<div align="justify">
Before running the code, please install the following libraries. Make sure to use the specified versions to ensure full compatibility with PersianILP:
</div>

```bash
pip install torch==2.2.0 torchvision==0.17.0 torchaudio==2.2.0
pip install dgl -f https://data.dgl.ai/wheels/torch-2.2/repo.html
pip install torchmetrics==1.2.1 transformers==4.38.0
pip install safetensors==0.4.1
pip install torcheval
pip install scikit-learn
pip install deep-translator
```

> 💡 Note: DGL must be installed using the provided link to match the PyTorch 2.2 version.
## 🧠 Key Features
- Supports inductive learning models for semantic graph analysis  
- Tailored for Persian language with linguistic-specific considerations  
- Suitable for link prediction, semantic reasoning, and conceptual translation tasks


## Publication
<div align="justify">
This dataset is presented and systematically evaluated in the following conference paper. If you use this dataset in your research or experiments, please cite the following publication:
<div>
  
```bibtex
@inproceedings{PersianILP,
  author    = {Mohammad Rahimi and Afsaneh Fatemi and Ahmad Baraani},
  title     = {PersianILP: Construction and Evaluation of a Standard Persian Dataset for Inductive Link Prediction},
  Conference = {2025 15th International Conference on Computer and Knowledge Engineering (ICCKE)},
  year      = {2025},
  doi       = {10.1109/ICCKE68588.2025.11273817},
  url       = {https://ieeexplore.ieee.org/document/11273817/}
}
```


## 📁 Project Structure
```
PersianILP/
│
├── Data/                # Dataset files
├── Scripts/             # Deep learning models
└── README.md            # Project documentation
```
