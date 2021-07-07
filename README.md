# IBM-Recommendations

An investigation of different recommendation methods for users of the [IBM AI Articles platform](https://developer.ibm.com/technologies/artificial-intelligence/articles/).
Methods of the following types are implemneted:
* Ranked-based
* User-User Collaborative Filtering
* Content Based
* Matrix Factorisation (SVD)



<h2> Files </h2>

1. Data:
    * articles_community.csv - Data on articles available on the platform - includes article ID; content; description; and title
    * user_item_interactions.csv - Record of user interactions with articles - entries consist of article ID and title, together with hash of the interacting user's email
2. Recommendations_with_IBM.ipynb - Jupytier notebook containg the project code

## Dependencies
This project uses Python 3.

The main packages used for the model and data loading are 
* numpy
* pandas
* sklearn
* NLTK

Matplotlib was also used for graphics.
