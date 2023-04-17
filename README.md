# Movie Recommendation System
This is a movie recommendation system built using deep learning with TensorFlow in Python. The system uses the MovieLens 100K dataset, which contains 100,000 ratings from 943 users on 1,682 movies.

## Getting Started
### Prerequisites
- Python 3.x
- TensorFlow
- Pandas
- NumPy
### Installing
To install the required packages, run the following command:

```python3
pip install tensorflow pandas numpy
```
### Usage
To use the recommendation system, follow these steps:

1. Download the ratings.csv and movies.csv files from the MovieLens 100K dataset.

2. Clone this repository:
```python3
git clone https://github.com/your-username/movie-recommendation-system.git
```
3. Place the ratings.csv and movies.csv files in the data directory of the cloned repository.

4. Follow the prompts to enter a user ID and get movie recommendations.

## Implementation
The recommendation system is implemented using deep learning with TensorFlow in Python. The model architecture consists of two embedding layers, one for the user IDs and one for the movie IDs, followed by a concatenation layer and two dense layers. The model is trained using the mean squared error loss function and the Adam optimizer. Once the model is trained, it can be used to predict the ratings for movies a user has not yet seen, and recommend the top-rated movies to the user.

## Results
![image](https://user-images.githubusercontent.com/65499285/232461994-c646ae25-abb0-403b-b829-50c3d99a3f93.png)

The recommendation system was evaluated using a validation set of 20% of the ratings in the dataset. The mean squared error on the validation set was 0.79. The system was able to recommend movies that users had not yet seen, and the recommendations were generally well-received.


## Authors
Marinto Richee J
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
This project was inspired by the MovieLens dataset and the TensorFlow tutorial on matrix factorization.
