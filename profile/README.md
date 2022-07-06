# Crypto Currency Portfolio Management from Natural Language Data

This organization contains all code connected to my master's thesis: "Crypto Currency Portfolio Management from Natural Language Data".

To make it more easily understandable the project is split into 4 parts which each have their own repositories which can be seen below.

The performance of the different models with varying parameters can be found on Weights and Biases via the following links:

1. Text Extraction Evaluation
    - [GRU with sentiment extraction](https://wandb.ai/masterthesis/dictRnnApproaches_final/sweeps/gbafpdxe)
    - [Average pooling with fine-tuned BERT-based sentiment extraction](https://wandb.ai/masterthesis/nnApproaches_final/sweeps/hhidikec)
    - [W2V with Average Pooling and GRUs](https://wandb.ai/masterthesis/w2vsumRnnApproaches_final/sweeps/hxr1ulfj)
    - [W2V with GRUs](https://wandb.ai/masterthesis/w2vRnnApproaches_final/sweeps/zz149zoz)
    - [Fixed BERT hidden states with GRUs](https://wandb.ai/masterthesis/bertRNNSeperateApproaches_final/sweeps/9azvhzrd)
    - [Fine-tuned BERT hidden states with GRUs](https://wandb.ai/masterthesis/bertRnnApproaches_final/sweeps/fo9fkcvy)
    - [Transformer hidden states with GRUs](https://wandb.ai/masterthesis/bertRnnApproaches_final/sweeps/fo9fkcvy)
    
2. Portfolio Construction Evaluation
    - [Rule-based portfolio construction](https://wandb.ai/masterthesis/bertRNNSeperateApproaches_final/sweeps/9azvhzrd)
    - [Neural-network-based portfolio construction](https://wandb.ai/masterthesis/bertRNNSeperateApproaches_pf_indep_final/sweeps/mpt2jj5l)
    - [Reinforcement learning-based portfolio construction](https://wandb.ai/masterthesis/bertRNNSeperateApproaches-RL/sweeps/fyew2ofj)