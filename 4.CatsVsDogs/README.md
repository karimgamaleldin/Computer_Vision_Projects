# Cats vs Dogs Image Classification Project

Welcome to our Cats vs Dogs Image Classification Project! In this project, we explored and experimented with various deep learning models trained on the popular Cats vs Dogs dataset from Kaggle.

## Project Overview

In this notebook, we conducted several experiments to build and train models on the Cats vs Dogs dataset. Each experiment involved different model architectures and techniques, and we documented our findings and results for each experiment.

### Experiments and Results

1. **Experiment 0 (model_0):**
   - Model: One block VGG architecture.
   - Validation Accuracy: ~72%
   - Training Accuracy: ~92%
   - Notes: Model_0 showed signs of severe overfitting.

2. **Experiment 1 (model_1):**
   - Model: Two block VGG architecture.
   - Validation Accuracy: ~76%
   - Training Accuracy: ~99%
   - Notes: Model_1 exhibited severe overfitting as well.

3. **Experiment 2 (model_2):**
   - Model: Three block VGG architecture.
   - Validation Accuracy: ~78%
   - Training Accuracy: ~99%
   - Notes: Similar to previous experiments, overfitting was observed.

4. **Experiment 3 (model_3):**
   - Model: Three block VGG architecture with dropout layers.
   - Validation Accuracy: ~78%
   - Training Accuracy: ~84%
   - Notes: Model_3 showed promising generalization on the validation data.

5. **Experiment 4 (model_3):**
   - Model: Extended training of model_3.
   - Validation Accuracy: ~81%
   - Training Accuracy: ~96%
   - Notes: Model_3 started overfitting after additional epochs.

6. **Experiment 5 (model_4):**
   - Model: Model_3 with data augmentation layer.
   - Validation Accuracy: ~77%
   - Training Accuracy: ~78%
   - Notes: Model_4 exhibited reasonable generalization on training data.

7. **Experiment 6 (model_4):**
   - Model: Extended training of model_4.
   - Validation Accuracy: ~82%
   - Training Accuracy: ~85%
   - Notes: After 50 epochs, model_4 showed good generalization.

In these 6 experiments, we were able to surpass our baseline of 80% validation accuracy, reaching up to ~82%.

### Additional Testing

We further validated the effectiveness of our best model by testing it on a custom image. The model correctly classified the image, providing us with accurate results.


## Future Directions

While we achieved promising results, there are several avenues for further exploration:

1. Train for more epochs to monitor longer-term model behavior.
2. Acquire additional data to improve model generalization.
3. Implement weight decay regularization for better control of overfitting.
4. Utilize learning rate scheduling to fine-tune the model's performance.
5. Consider incorporating transfer learning techniques for enhanced accuracy.
