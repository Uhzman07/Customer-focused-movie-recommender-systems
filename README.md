# Customer-focused-movie-recommender-systems
This is a simple recommender systems directed towards learning! - Contains extensive explanations as followed by Spencer Pao (Youtube). Here is the link for an overview -> https://youtu.be/G4MBc40rQ2k?si=1roxDnZyZpN01RUC

## 🚀 Features
- Matrix Factorization using PyTorch
- Custom Dataset Loader for user-item interactions
- GPU/CPU-compatible training loop
- Embedding visualization and clustering with KMeans
- Popular movie surfacing per cluster 

## 📦 Tech Stack
- Python
- PyTorch
- NumPy
- Pandas
- scikit-learn
- tqdm -> Simple progress bar

## 📊 How It Works
1. **Data Loading**: Ratings are loaded and indexed for efficient training.
2. **Model Training**: A matrix factorization model learns user and item embeddings. (Embedding layers)
3. **Loss Optimization**: Mean Squared Error (MSE) is minimized using the Adam optimizer.
4. **Clustering**: Learned item embeddings are clustered using KMeans to reveal latent groupings.
5. **Interpretation**: Top-rated movies per cluster are surfaced to interpret themes.

## 🧠 What I Learned
- How to build a recommender system from scratch
- Embedding layers and matrix factorization
- Gradient-based optimization and backpropagation
- Clustering learned representations for insight

## 🙋‍♂️ Author
** Usman Sadiq** — Student, builder, and machine learning enthusiast.
