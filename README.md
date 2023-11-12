**DashtoonTask Implementation Overview:**

**Paper Reference:** [A Learned Representation For Artistic Style](https://arxiv.org/abs/1610.07629)

**Content Dataset:** MSCOCO 2014 train

**Style Images:** 10 styles from the './style' directory

**Training Details:**
- **Model Type:** Neural Style Transfer
- **Iterations:** 25000
- **Batch Size:** 2

**Challenges Faced:**
- Hardware limitations affecting model performance.
- Suboptimal results due to training constraints.

**Key Features:**
- The model has the ability to learn and transfer various artistic styles.
- Current training includes 10 distinct style images.

**Results and Limitations:**
- The obtained results are deemed suboptimal, partially attributed to hardware limitations.
- Further improvements planned to enhance model capabilities.

**Planned Enhancements:**
- Implementation of AdaIn Blocks.
- Aim: Enable the model to generalize better to unseen artwork styles.
  
**Conclusion:**
Despite hardware constraints, the implemented model demonstrates potential for style transfer across various artistic representations. The planned integration of AdaIn Blocks is expected to significantly enhance the model's ability to interpret and apply previously unseen artistic styles.
