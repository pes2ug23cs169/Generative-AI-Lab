Notebooks
1. Advanced RAG & Retrieval
Why Naïve RAG fails: vocabulary mismatch and top-K noise (live demo)
Sparse Retrieval (BM25): TF-IDF evolution, BM25 formula, rank_bm25 library
Dense Retrieval (SBERT): sentence embeddings, bi-encoder architecture
ColBERT: token-level late interaction, MaxSim scoring (built from scratch)
Hybrid Retrieval (BM25 + SBERT + RRF): Reciprocal Rank Fusion with worked numericals
2. Re-Ranking & Query Expansion
Cross-Encoder Re-Ranking: bi-encoder vs cross-encoder, 2-stage retrieval strategy
HyDE (Hypothetical Document Embedding): LLM-generated hypothetical answers as queries
Multi-Query Retrieval: LangChain's MultiQueryRetriever with Gemini
Full Pipeline: Query Expansion → Hybrid Retrieval → Re-Ranking → LLM Generation (LCEL)
3. Generation Enhancement
Fine-Tuning Decision Tree: Prompt vs RAG vs Fine-Tune vs Pre-Train
LoRA / PEFT: Low-rank adaptation math, peft library, trainable parameter count demo
Data Precision: FP32 vs FP16 vs BF16 vs INT8 — memory and accuracy trade-offs
Quantization: Linear quantization math, INT8 worked example, model size comparison table
