# scBERT-Plus
scBERT-Plus: An Enhanced and Interpretable scBERT Framework for Single-cell Analysis
This project builds upon the pioneering scBERT (TencentAI Lab) to provide an improved and more accessible toolkit for cell type annotation.

**Key Improvement: Enhanced Scalability with Linformer**
We replaced the original Performer encoder in scBERT with a Linformer architecture. This upgrade significantly reduces the computational complexity of the self-attention mechanism from O(n²) to O(n), enabling our model (scBERT-Plus) to efficiently handle much larger single-cell datasets with lower memory consumption, while maintaining competitive performance.
