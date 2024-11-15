Overview

This project demonstrates a content-based movie recommendation system built using Natural Language Processing (NLP) techniques. The system recommends movies based on textual similarity of movie descriptions (overviews) from the popular TMDB 5000 Movies Dataset.
Features

    TF-IDF Vectorization: Converts movie overviews into numerical representations.
    Multiple Similarity Measures:
        Cosine Similarity
        Euclidean Distance
        Jaccard Similarity
    Modular Design: Easy to extend and experiment with other similarity methods or datasets.
    Interactive Recommendations: Input a movie title to get the top recommendations based on the selected similarity method.

How It Works

    The movie dataset is preprocessed to extract titles and overviews.
    Textual data is vectorized using TF-IDF to generate feature matrices.
    Pairwise similarities between movies are calculated using chosen similarity metrics.
    Recommendations are generated by ranking movies based on similarity to the input title.

Dependencies

    pandas: For dataset manipulation.
    numpy: For numerical operations.
    scikit-learn: For TF-IDF vectorization and similarity computations.