# Movie Recommendation using MovieLens Dataset

![Movie_Recommendation](https://img.shields.io/badge/Movie_Recommendation-Using_Machine%20Learning-blue
)

## Overview

This project demonstrates how to build a movie recommendation system using the MovieLens dataset. The system recommends movies to users based on their past movie ratings and the ratings of similar users. It employs collaborative filtering and K-Nearest Neighbors (KNN) to provide movie recommendations.

## Table of Contents

- Dataset
- Project Structure
- Installation
- Usage
- Approach
- Results
- Future Improvements
- Contributing
- License

## Dataset

The MovieLens dataset used in this project contains information about movie ratings, user profiles, and movie details. The dataset includes 100,000 ratings from 943 users on 1,682 movies.

- Dataset Link: [MovieLens Dataset](https://github.com/Leni-Nikitaa/Movie-Recommendation/tree/main/MovieLens-Dataset)

## Project Structure

The project is organized as follows:

- [`Movie_Recommendation_using_Movielens_dataset.ipynb`](https://github.com/Leni-Nikitaa/Movie-Recommendation/blob/main/Movie_Recommendation_using_Movielens_dataset.ipynb): Jupyter Notebook containing the code for building the recommendation system.
- [`MovieLens-Dataset`](https://github.com/Leni-Nikitaa/Movie-Recommendation/tree/main/MovieLens-Dataset): Directory containing the MovieLens dataset files.
- [`README.md`](https://github.com/Leni-Nikitaa/Movie-Recommendation/blob/main/README.md): This README file.

## Installation

To run this project locally, you'll need Python and the following libraries:

- numpy
- pandas
- matplotlib
- scikit-learn

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Clone this repository to your local machine.
2. Download the MovieLens dataset from the provided link and extract it into the `MovieLens-Dataset` directory.
3. Open the Jupyter Notebook `Movie_Recommendation_using_Movielens_dataset.ipynb`.
4. Follow the instructions in the notebook to execute the code and generate movie recommendations.

## Approach

The project follows these major steps:

1. Data Loading and Preprocessing: Load the MovieLens dataset and preprocess it to create user-movie rating matrices.

2. Collaborative Filtering: Implement collaborative filtering using K-Nearest Neighbors (KNN) to find similar users.

3. Recommendation: Recommend movies to a given user based on their similarity to other users and their past ratings.

## Results

The project provides movie recommendations for users based on their past ratings and the ratings of similar users. Users can specify the number of similar users to consider and the number of movies to be recommended.

## Future Improvements

Future improvements for this project may include:

1. Implementing more advanced recommendation algorithms, such as matrix factorization techniques.
2. Incorporating user feedback and user profiles to enhance recommendations.
3. Developing a user-friendly web or mobile application for users to interact with the recommendation system.

## Contributing

This project is maintained by [Leni Nikitaa](https://github.com/Leni-Nikitaa) and was created with contributions from several individuals, including [Revan Bairav](https://github.com/Revan-Bairav). We welcome and appreciate contributions from the community to make this project even better. If you have ideas for improvements or new features, please feel free to open an issue or submit a pull request.

### How to Contribute

1. Fork the project to your GitHub account.
2. Create a new branch with a descriptive name for your contribution.
3. Make your changes and improvements within the branch.
4. Test your changes thoroughly to ensure they work as expected.
5. Submit a pull request, explaining the purpose and details of your contribution.
6. Your pull request will be reviewed by the project maintainers, and feedback may be provided.
7. Once your contribution is accepted, it will be merged into the project.

By contributing to this project, you are helping to make it more valuable for everyone in the community. Thank you for your support and collaboration!

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/Leni-Nikitaa/Movie-Recommendation/blob/main/LICENSE) file for details.