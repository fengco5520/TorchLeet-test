# TorchLeet 90-Day Study Plan

**Dates:** October 12, 2026–January 9, 2027

**Scope:** Basics, LLM Learning Path, then Advanced

**Estimated effort:** About 87 hours total, averaging roughly 6.8 hours per week

The schedule combines shorter fundamentals at the beginning and gives more time to harder work later. To finish in 90 days, plan for about 5–6 hours per week early on and around 8–10 hours per week in the Advanced portion. At a strict 5 hours per week, expect to extend the plan.

Each bullet links to the original question notebook in this repository (not a solution notebook). When a question appears in multiple tracks, use the later listing as review rather than repeating the exercise.

## Week 1 · Oct 12–18 · Basics · ~4 hours

- [v1-1 · Implement Linear Regression](torch/basic/lin-regression/lin-regression.ipynb)
- [v1-2 · Write a Custom Dataset and DataLoader](torch/basic/custom-dataset/custom-dataset.ipynb)
- [v1-3 · Write a Custom Activation Function](torch/basic/custom-activation/custom-activation.ipynb)
- [v1-4 · Implement Custom Loss Function (Huber Loss)](torch/basic/custom-loss/custom-loss.ipynb)
- [v1-5 · Implement a Deep Neural Network](torch/basic/custom-DNN/custon-DNN.ipynb)
- [v1-6 · Visualize Training with TensorBoard](torch/basic/tensorboard/tensorboard.ipynb)
- [v1-7 · Save and Load PyTorch Model](torch/basic/save-model/save_model.ipynb)
- [v3-1 · Implement Softmax from Scratch](v3/classical-ml/softmax/softmax.ipynb)
- [v3-4 · Implement Logistic Regression with Gradient Descent](v3/classical-ml/logistic-regression/logistic-regression.ipynb)

## Week 2 · Oct 19–25 · Basics · ~7 hours

- [v1-8 · Implement a CNN on CIFAR-10](torch/easy/cnn/CNN.ipynb)
- [v1-9 · Implement an RNN from Scratch](torch/easy/rnn/RNN.ipynb)
- [v1-10 · Data Augmentation with torchvision.transforms](torch/easy/augmentation/augmentation.ipynb)
- [v1-11 · Add Benchmarking to PyTorch Code](torch/easy/benchmark/bench.ipynb)
- [v1-12 · Train an Autoencoder for Anomaly Detection](torch/easy/autoencoder/autoencoder.ipynb)
- [v1-13 · Quantize Your Language Model](torch/easy/quantize-lm/quantize-language-model.ipynb)
- [v1-14 · Mixed Precision Training with torch.cuda.amp](torch/easy/cuda-amp/cuda-amp.ipynb)
- [v1-15 · CNN Parameter Initialization](torch/medium/cnn-param-init/CNN_ParamInit.ipynb)
- [v1-16 · Implement a CNN from Scratch](torch/medium/cnn-scratch/CNN_scratch.ipynb)
- [v1-17 · Implement an LSTM from Scratch](torch/medium/lstm/LSTM.ipynb)
- [v3-2 · Implement K-Means Clustering in PyTorch](v3/classical-ml/kmeans/kmeans.ipynb)
- [v3-3 · Implement KNN in PyTorch](v3/classical-ml/knn/knn.ipynb)

## Week 3 · Oct 26–Nov 1 · LLM foundations · ~4 hours

- [v2-3 · Implement Byte Pair Encoding from Scratch](llm/Byte-Pair-Encoder/BPE-q3.ipynb)
- [v2-10 · Implement Sinusoidal Embeddings](llm/Sinusoidal-Positional-Embedding/sinusoidal-q7-Question.ipynb)
- [v2-11 · Implement ROPE Embeddings](llm/Rotary-Positional-Embedding/rope-q8-Question.ipynb)
- [v3-10 · Implement Temperature Sampling](v3/llm-decoding/temperature-sampling/temperature-sampling.ipynb)

## Week 4 · Nov 2–8 · Attention fundamentals · ~4 hours

- [v2-6 · Implement Attention from Scratch](llm/Implement-Attention-from-Scratch/attention-q4-Question.ipynb)
- [v2-7 · Implement Multi-Head Attention from Scratch](llm/Multi-Head-Attention/multi-head-attention-q5-Question.ipynb)
- [v2-8 · Implement Grouped Query Attention from Scratch](llm/Grouped-Query-Attention/grouped-query-attention-Question.ipynb)

## Week 5 · Nov 9–15 · Attention and decoding · ~4 hours

- [v3-12 · Implement KV Cache for Autoregressive Generation](v3/llm-inference/kv-cache/kv-cache.ipynb)
- [v3-13 · Implement Sliding Window Attention](v3/modern-architectures/sliding-window-attention/sliding-window-attention.ipynb)
- [v3-8 · Implement Top-k Sampling](v3/llm-decoding/top-k-sampling/top-k-sampling.ipynb)
- [v3-7 · Implement Top-p (Nucleus) Sampling](v3/llm-decoding/top-p-sampling/top-p-sampling.ipynb)

## Week 6 · Nov 16–22 · Build and fine-tune · ~5 hours

- [v2-12 · Implement SmolLM from Scratch](llm/SmolLM/smollm-q12-Question.ipynb)
- [v3-11 · Implement LoRA on a Linear Layer](v3/alignment-training/lora/lora.ipynb)
- [v3-14 · Implement DPO Loss from Scratch](v3/alignment-training/dpo/dpo.ipynb)

## Week 7 · Nov 23–29 · Alignment · ~4 hours

- [v3-15 · Implement PPO for RLHF](v3/alignment-training/ppo-rlhf/ppo-rlhf.ipynb)
- [v3-27 · Implement GRPO (DeepSeek-R1 Algorithm)](v3/alignment-training/grpo/grpo.ipynb)

## Week 8 · Nov 30–Dec 6 · Advanced foundations · ~8.5 hours

- [v3-9 · Implement Beam Search for LLM Decoding](v3/llm-decoding/beam-search/beam-search.ipynb)
- [v3-5 · Implement Contrastive Loss (InfoNCE) + CLIP Training Loop](v3/modern-architectures/contrastive-loss-clip/contrastive-loss-clip.ipynb)
- [v3-6 · Implement 2D Positional Embeddings](v3/modern-architectures/2d-positional-embeddings/2d-positional-embeddings.ipynb)
- [v3-13 · Implement Sliding Window Attention](v3/modern-architectures/sliding-window-attention/sliding-window-attention.ipynb) *(review)*
- [v3-29 · Implement Knowledge Distillation](v3/modern-architectures/knowledge-distillation/knowledge-distillation.ipynb)
- [v1-22 · Write a Custom Autograd Function (SILU)](torch/hard/custom-autograd/custom-autgrad-function.ipynb)

## Week 9 · Dec 7–13 · Advanced architectures · ~8.5 hours

- [v1-26 · Write a Transformer from Scratch](torch/hard/transformer/transformer.ipynb)
- [v1-27 · Write a GAN](torch/hard/GAN/GAN.ipynb)
- [v1-28 · Sequence-to-Sequence with Attention](torch/hard/seq-seq/seq-to-seq-with-Attention.ipynb)
- [v1-31 · Explainable AI (GradCAM/SHAP)](torch/hard/xai/xai.ipynb)

## Week 10 · Dec 14–20 · Advanced training and vision · ~8.5 hours

- [v3-16 · Implement Gradient Checkpointing](v3/alignment-training/gradient-checkpointing/gradient-checkpointing.ipynb)
- [v3-20 · Implement DDPM from Scratch](v3/modern-architectures/ddpm/ddpm.ipynb)
- [v3-21 · Implement DDIM Sampling + Classifier-Free Guidance](v3/modern-architectures/ddim-cfg/ddim-cfg.ipynb)
- [v3-22 · Implement Selective State Space Model (Mamba)](v3/modern-architectures/mamba/mamba.ipynb)
- [v3-23 · Implement Vision Transformer + MAE Pretraining](v3/modern-architectures/vit-mae/vit-mae.ipynb)

## Week 11 · Dec 21–27 · Advanced inference systems · ~10 hours

- [v3-18 · Implement Speculative Decoding](v3/llm-inference/speculative-decoding/speculative-decoding.ipynb)
- [v3-19 · Implement Continuous Batching for LLM Inference](v3/llm-inference/continuous-batching/continuous-batching.ipynb)
- [v3-28 · Build a Complete LLM Inference Engine](v3/llm-inference/inference-engine/inference-engine.ipynb)
- [v3-12 · Implement KV Cache for Autoregressive Generation](v3/llm-inference/kv-cache/kv-cache.ipynb) *(review)*

## Week 12 · Dec 28–Jan 3 · Advanced GPU systems · ~9 hours

- [v3-24 · Write a Fused Softmax Kernel in Triton](v3/gpu-systems/triton-fused-softmax/triton-fused-softmax.ipynb)
- [v3-25 · Implement FlashAttention-2 in Triton](v3/gpu-systems/flash-attention-triton/flash-attention-triton.ipynb)
- [v3-26 · Implement FSDP from Scratch](v3/gpu-systems/fsdp/fsdp.ipynb)
- [v3-30 · Implement Ring Attention for Long Contexts](v3/gpu-systems/ring-attention/ring-attention.ipynb)

## Week 13 · Jan 4–9 · Review and capstone · ~9 hours

- [v3-17 · Implement Mixture of Experts Layer](v3/modern-architectures/mixture-of-experts/mixture-of-experts.ipynb)
- [v3-11 · Implement LoRA on a Linear Layer](v3/alignment-training/lora/lora.ipynb) *(review)*
- [v3-14 · Implement DPO Loss from Scratch](v3/alignment-training/dpo/dpo.ipynb) *(review)*
- [v3-15 · Implement PPO for RLHF](v3/alignment-training/ppo-rlhf/ppo-rlhf.ipynb) *(review)*
- [v3-27 · Implement GRPO (DeepSeek-R1 Algorithm)](v3/alignment-training/grpo/grpo.ipynb) *(review)*
- Continue testing, reviewing, and completing [the LLM inference engine capstone](v3/llm-inference/inference-engine/inference-engine.ipynb).

## Meetup rhythm

Meet twice a week, with individual practice between meetups. Try each question independently before meeting; use the meetup to compare approaches, tensor shapes, assumptions, edge cases, and tests. Combine several short exercises early. For hard and expert questions, focus on making progress on one implementation at a time rather than racing through the list. Use TorchLeet's progressive hints and check prerequisites when stuck.
