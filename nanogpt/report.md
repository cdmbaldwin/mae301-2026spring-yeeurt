# nanoGPT Build Report - Team YEEURT

## 1. Objective
[Clearly state what you attempted to build/achieve, e.g., "Implemented a character-level GPT on Tiny Shakespeare dataset using a transformer architecture."]

## 2. Model Architecture
[Describe the architecture of your GPT-style language model. Include details on:]
*   **Embedding layer:** How tokens are converted into numerical representations.
*   **Positional encoding:** How position information is incorporated.
*   **Self-attention block:** Structure and components (query, key, value, multi-head attention).
*   **Feedforward network:** Layers and activation functions.
*   **Softmax layer:** How output probabilities are generated.
*   Any other relevant architectural details.

## 3. Training Setup
[Detail the environment and parameters used for training:]
*   **Dataset description:** Name of the dataset, its size, and characteristics (e.g., character-level, word-level).
*   **Train/validation split:** How the dataset was divided.
*   **Batch size:** Number of samples processed at once.
*   **Learning rate:** Step size for optimizer.
*   **Optimizer:** Algorithm used for weight updates (e.g., AdamW).
*   **Number of steps/epochs:** Total training iterations.

## 4. Experiments
[Present the results of your experimental configurations. Include a table summarizing key metrics:]

| Config Name | Layers | Heads | Embed Dim | Context Length | Dropout | Parameters (M) | Training Time | Best Val Loss |
| :---------- | :----: | :---: | :-------: | :------------: | :-----: | :------------: | :------------: | :-----------: |
| [Config 1]  | [e.g., 2]| [e.g., 2]| [e.g., 64]| [e.g., 64]     | [e.g., 0.1]| [e.g., 0.1]     | [e.g., 1h]      | [e.g., 2.5]   |
| [Config 2]  | [e.g., 4]| [e.g., 4]| [e.g., 128]| [e.g., 128]    | [e.g., 0.2]| [e.g., 0.5]     | [e.g., 2h]      | [e.g., 2.0]   |
| [Config 3]  | [e.g., 6]| [e.g., 6]| [e.g., 256]| [e.g., 256]    | [e.g., 0.3]| [e.g., 1.5]     | [e.g., 4h]      | [e.g., 1.8]   |

*   **Loss Curves:** [Include links or embedded plots of training and validation loss curves.]
*   **Final Validation Loss:** [List the final validation loss for each configuration.]

## 5. Qualitative Samples
[Provide example generated text samples for at least two configurations. Evaluate their quality.]
*   **Config 1 Samples:**
    *   [Generated Text Sample 1]
    *   [Generated Text Sample 2]
*   **Config 2 Samples:**
    *   [Generated Text Sample 1]
    *   [Generated Text Sample 2]

## 6. Analysis & Reflection
[Discuss what you learned from your experiments:]
*   **Over/Under-fitting:** Evidence of overfitting or underfitting.
*   **Capacity vs. Data Size:** How model capacity relates to the dataset size.
*   **Stability of Training:** Any issues with training stability.
*   **Inform MVP Model Design:** How these findings will influence the design of your MVP model.

---
**Data Tokenization Strategy:** [Describe how your input text was tokenized (e.g., character-level, Byte Pair Encoding, etc.).]
