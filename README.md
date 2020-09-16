# Recommender System

## Questions
How are we receiving video recommendations on Youtube or product recommendations on Amazon?

## Assumption
By observing and analyzing preferences and shopping behavior of users (audiences/shoppers), we can find patterns and using those behavioral patterns, we can make recommendations to our users, what they might like as well.

## Key concept
**Popularity based recommendation**: What most people liked, may also be liked by our target user/customer/audience.

**Content based recommendation**: Recommend similar products. For ex. If a customer is checking the price of an Android phone (samsung), we can also recommend other android phones like Sony, HTC etc. And If an audience is watching an action movie, we can recommend another action movie.

**Collaborative filtering based**: It works in collaboration and relies on users past preferences as well as other users preferences.  For example, if customer1 liked products A and B earlier and those products were also liked by other customers such as customer8 and customer14. So there is a similarity of preferences between these customers. Let, recently customer8 and customer14 bought product K, so we can suggest product K to cusomer1 using collaborative filtering approach. Collaborative filters do not require item metadata.

## Data
For this project, we are going to use MovieLens Dataset, which is comprised of 26 million ratings and 750,000 tag applications, from 270,000 users on all the 45,000 movies. It can be accessed from the official [GroupLens website](https://grouplens.org/datasets/movielens/latest/).

*Note: in some portions, we will use a subset of the original dataset due to low computational resources.*


## Usage
To get recommendation, please run the get_recommendations() function with arguments. Here is an example:
```python
get_recommendations('GoldenEye', cosine_sim2)
```
Recommendations:

| Id        |        Movie Title        |
| ----      | ------                    |
| 1182      |              Dante's Peak |
| 1377      |      Tomorrow Never Dies  |
| 1930      |             First Blood   |
| 2417      |         Licence to Kill   |
| 7159      |           Transporter 3   |

#

## Hardware Requirements
At least 16 GB of RAM or more.

## Acknowledgments
This project uses other free kernels and tutorials from kaggle.com and datacamp.com, which can be reached from below

[1](https://www.kaggle.com/rounakbanik/movie-recommender-systems),
[2](https://www.kaggle.com/rounakbanik/the-story-of-film/),
[3](https://www.datacamp.com/community/tutorials/recommender-systems-python)


## Disclaimer
We have reproduced and adapted the code according to our needs for educational and learning purposes only.


## License
Completely free for educational use.



