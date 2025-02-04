# SemiSuperTSC

# **Efficient Graph-Based Semi-Supervised Time Series Classification**  
### *A Scalable Alternative to SimTSC using Series2Vec*

---

## **Overview**  
This project presents a novel **graph-based semi-supervised time series classification** framework that efficiently propagates features from unlabeled samples to labeled ones using a **similarity graph constructed with Series2Vec embeddings** instead of the computationally expensive **DTW distance** used in SimTSC.  

This work enhances the **practical application of semi-supervised time series classification** by providing a **scalable framework** suitable for **large-scale datasets**. The significant reduction in computation time facilitates its use in real-world scenarios, such as **healthcare** and **systems monitoring**, where timely insights are critical, and labeled data is scarce.

By leveraging a combination of **Series2Vec, ResNet, and Graph Convolutional Networks (GCNs)**, this approach significantly **reduces the computational burden** while maintaining **comparable classification performance** on large time series datasets.

---

## **Key Features**  
✔️ **Faster Graph Construction**: Uses **Series2Vec similarity-preserving embeddings** instead of **DTW**, achieving **up to 86x speedup** in graph construction.  
✔️ **Semi-Supervised Learning**: Utilizes a **graph-based framework** to effectively leverage both **labeled and unlabeled** data.  
✔️ **Scalability**: Suitable for **large-scale datasets**, reducing computation time while maintaining **classification accuracy**.  
✔️ **Deep Learning Integration**: Combines **ResNet for feature extraction** and **GCN for feature propagation**.  

---

## **Installation**  
To set up the project environment, follow these steps:

### **1. Clone the Repository**  
```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
