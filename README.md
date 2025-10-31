This project implements an attention-enhanced hypergraph neural network (HGNN) for provenance-based intrusion detection, designed to identify anomalous behaviors in DARPA Cadets provenance graphs.
By modeling higher-order relationships through hyperedges and incorporating attention-based pooling, this system achieves more expressive feature aggregation and context-aware anomaly detection compared to traditional graph-based IDS approaches.

**Key Highlights**

Hypergraph-based modeling: Captures multi-entity dependencies in provenance data beyond pairwise edges.

Attention mechanism: Dynamically weighs node contributions within each hyperedge for improved representation learning.

Performance boost: Achieved a 5% improvement in F1-score compared to baseline GNN and FLASH-style models.

Lightweight & interpretable: The model maintains real-time feasibility while improving anomaly localization accuracy.


**Features**

Node embedding → Hyperedge attention pooling → Edge-to-node aggregation

End-to-end PyTorch implementation (with PyTorch Geometric)

Works on DARPA CADETS and compatible provenance graph datasets

Evaluation metrics: F1-score, precision, recall, ROC-AUC.
