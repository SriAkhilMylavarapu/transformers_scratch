# transformers_scratch
## Implementing Transformers from scratch with the paper "Attention is all you need" as reference
Used only basic modules from PyTorch and created classes for PositionalEncoding, MultiHeadAttention, PositionWiseFeedForward, EncoderLayer, DecoderLayer, and the Transformer 

![title](imgs/Model_Arch.png)

## Results

### Addition of Two Two-Digit Numbers
The transformer model achieves the following performance:

| Metric          | Accuracy |
|-----------------|----------|
| **Validation**  | 98.89%   |
| **Test**        | 96.20%   |

This demonstrates strong generalization capabilities for arithmetic operations while maintaining high precision on unseen data.

| <img src="imgs/Loss_Acc_Curves.png" alt="Loss Accuracy Graphs" width="100%"> | <img src="imgs/Test_Res.png" alt="Test Results" width="100%"> |
