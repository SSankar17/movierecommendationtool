# Sanjana's Movie Recommendation Tool!

In this project, I am building a movie recommendation tool!

### Inspiration!
The phrase “decision fatigue” is unanimously associated with streaming platforms. My sister and I love watching movies together, but we always spend over 30 minutes trying to pick something to watch. To solve this, I created a Movie Recommendation Tool, a project designed to simplify movie nights by using data-driven suggestions to narrow down our choices. The goal is to reduce the time spent deciding and spend more time actually enjoying the movie.

### Programming Tools Used
* Python
    * SentenceTransformer
    * pandas
    * scikitlearn
    * seaborn
    * numpy
    * matplotlib


#### Data Overview 

`movies_metadata.csv` contains the following columns: 

- `movie_id`: Unique identifier of each movie. 
- `title`: Title of the movie. 
- `overview`: Short description of the movie. 
- `vote_average`: Average score the movie got.
- `vote_count`: Total number of votes the movie got. 

`ratings` contains the following columns: 

- `user_id`: Unique identifier of the person who rated the movie. 
- `movie_id`: Unique identifier of the movie. 
- `rating`: Value between 0 and 10 indicating how much the person liked the movie. 

#### Usage

In the final cell of the Jupyter notebook, there are instructions on how to use this! Happy movie watching
