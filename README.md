# FashionMLP


FashionMLP is an in-depth exploration of Multi-Layer Perceptron (MLP) neural networks applied to the Fashion-MNIST dataset. The project is structured to provide a holistic understanding of MLPs in both classification and regression contexts, emphasizing the impact of different activation functions, weight initialization strategies, and hyperparameter configurations on model performance.

### Objectives

1. **Data Preprocessing and Visualization**: 
   - Normalize the Fashion-MNIST data to ensure efficient training.
   - Visualize sample images to understand the dataset's structure and diversity.

2. **Classification with Various Activation Functions**: 
   - Train MLP classifiers using different activation functions (`logistic`, `tanh`, `relu`, `identity`).
   - Analyze and compare the performance of each activation function through training and validation loss curves.

3. **Hyperparameter Optimization**: 
   - Utilize grid search to identify the optimal hyperparameters (solver, learning rate, batch size) for the best-performing activation function.
   - Enhance model performance by fine-tuning these hyperparameters.

4. **Image Regeneration using MLP Regressor**: 
   - Design and train MLP regressors to regenerate input images, effectively learning to reconstruct the original data.
   - Compare the effectiveness of different activation functions (`relu`, `identity`) in the regeneration task.

5. **Feature Extraction and Enhanced Classification**: 
   - Extract meaningful feature vectors from the trained regressors.
   - Train smaller MLP classifiers on these feature vectors to evaluate whether reduced-dimensional representations can maintain or improve classification performance.

Dataset Link:https://drive.google.com/drive/folders/1bfxZ3Up1hAjBkbuPmp8A5Y0e0vV9HGKm?usp=sharing

