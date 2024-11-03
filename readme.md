This project developed a film recommender using data from TMDB.
The aim is to recommend movies to users according to certain film characteristics.
It began by selecting the necessary columns in the dataset, such as genre, rating, runtime, cleaning the dataset, and removing unnecessary columns containing irrelevant data or columns filled with zeroes.
Key steps included the extraction of the primary genre, the grouping of languages and genres, and the removal of unnecessary columns.
Normalization of the dataset was done; categorical features were encoded for better model performance.
In clustering, the K-Means algorithm divided the movies into 15 clusters so that at least one movie can be included in a cluster.
Finally, the recommended system suggests five movies from these clusters based on three user-inputted films and visualizes them through a user interface.
Such an approach provides relevant recommendations with the aid of movie features and cluster similarities.
