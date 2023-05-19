# Movie Recommendation System
This movie recommendation system suggests movies based on age, genre, and cast. It utilizes cosine similarity to provide personalized recommendations from a dataset of movies.

## Dataset
The dataset used for movie recommendations is stored in a CSV file named Dataset.csv. The dataset contains the following columns:

ID: Incremental identifier for each movie.
Name: The name of the movie.
Genre: The genre of the movie.
Cast: The cast members of the movie.
Age: The age range associated with the movie.

## Prerequisites
To run the movie recommendation system, you need to have the following dependencies installed:

#### Python 3
#### pandas
#### scikit-learn

You can install the required dependencies using the following command:
## pip install pandas scikit-learn

## Usage
1. Make sure you have Python 3 installed.
2. Download or clone the repository containing the code.
3. Place the Dataset.csv file in the same directory as the Python script.
4. Open a terminal or command prompt and navigate to the directory containing the script.
5. Run the following command to execute the movie recommendation system:
6. Enter your age, preferred genre, and preferred cast member when prompted.
7. The system will recommend a list of movies based on your input.

## Example
Here's an example usage of the movie recommendation system:

User Input:
Enter your age: 18+
Enter your preferred genre: Action
Enter your preferred cast member: Dwayne Johnson

Recommended movies:
1. Jumanji: The Next Level
2. Fast Five
3. Jumanji: Welcome to the Jungle
4. Furious 6
5. Fast & Furious 7
