# Movie-Recommendation-Using-GNNs
Developed movie recommender system using Graph Neural Networks (GCN, GraphSage) on Netflix Prize data.

Objective :


To analyse and perform various tasks such as classification, prediction, clustering and recommendation on the Online streaming platform(OTT) Dataset using Graph Machine Learning Models.

Methods:

The aim is to develop a graph-based recommendation system for the Online streaming platform (OTT) Dataset to provide personalized movie recommendations by leveraging the underlying graph structure of user-item interactions. Here are the methods that can be utilized to achieve this goal:
- Graph Representation: Representing the OTT Dataset as a graph, where users and movies are represented as nodes and interactions (ratings) as edges. This graph representation captures the relationships between users and items, enabling the exploration of user-item interactions in a graph-based framework.
- Graph Embeddings: Employing graph embedding techniques such as DeepWalk, Node2Vec, or Graph Convolutional Networks (GCNs) to learn low-dimensional representations of users and items in the graph. These embeddings capture the structural information and latent features of users and items, facilitating recommendation tasks.
- Neighborhood-based Recommendation: Utilizing graph-based similarity measures to identify similar users or items based on their connectivity in the graph. Neighbourhood-based recommendation methods such as collaborative filtering can recommend items liked by similar users or items with similar attributes to those liked by the user.
- Random Walks and Link Prediction: Performing random walks on the user-item interaction graph to explore the graph structure and uncover latent relationships between users and items. Link prediction techniques can predict missing or future interactions between users and items, enabling the recommendation of relevant items to users.
- Graph Neural Networks (GNNs): Leveraging GNNs to aggregate information from the user-item interaction graph and make personalized recommendations. GNNs can capture higher-order graph structures and learn complex user-item interactions, leading to improved recommendation performance.
By employing these graph-based methods and leveraging the rich connectivity information in the OTT Dataset, we can develop a recommendation system that provides accurate and personalized movie recommendations tailored to individual user preferences, thereby enhancing the overall movie-watching experience.

Expected Results:


Overall, our analysis and predictions on the OTT Dataset will contribute to the development of advanced recommendation systems, enabling more accurate, personalized, and engaging movie recommendations for users, thereby improving satisfaction and retention on the Netflix like OTT platforms.

Dataset:


We plan on using Netflix Prize dataset from Kaggle. The dataset contains two files.
The training dataset file "training_set.tar" contains 17,770 files, each corresponding to a movie. Each file begins with the movie ID followed by a colon. Subsequent lines in each file represent ratings from customers, along with the rating value and date in the format:

The "movie_titles.txt" file contains movie information in the format: MovieID,YearOfRelease,Title.
url: https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data
