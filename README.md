# Ego-Model

This repository contains selected code samples demonstrating my research on **self-supervised world model learning from egocentric video**, where agents learn **object-centric representations** and **temporal consistency** guided by **depth priors**.

## 🧠 Highlights
- Depth-aware proto-object discovery  
- Temporal consistency loss for object permanence  
- Egocentric video pretraining using Vision Transformers (ViT-S/16)   

## 🧩 Structure
```text
ego-world-model/
├── depth_module/          # depth-guided proposal network
├── proto_object_vit/      # object-centric ViT backbone
├── temporal_consistency/  # cross-frame alignment loss
├── utils/                 # training utils, configs
└── demo.ipynb             # example visualization notebook
```

## 🧪 Environment
- Python 3.10  
- PyTorch 2.2  
- OpenCV, NumPy, Matplotlib  

## 🖇️ Contact
Created by **Yuting Tan **  
Master’s Student, Communication University of China  
🌐 [https://kristinat8.github.io/Yuting-Tan](https://kristinat8.github.io/Yuting-Tan)
