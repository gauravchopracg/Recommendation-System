# Recommendation-System

This is the code for a basic Recommender System using python library. The code uses the [lightfm](https://github.com/lyst/lightfm) recommender system library to train a hybrid content-based + collaborative algorithm that uses the WARP loss function on the [movielens](http://grouplens.org/datasets/movielens/) dataset. The movielens dataset contains movies and ratings from over 1700 users. Once trained, our script prints out recommended movies for whatever users from the dataset that we choose to terminal.

## Dependencies

* numpy (http://www.numpy.org/)
* scipy (https://www.scipy.org/)
* lightfm (https://github.com/lyst/lightfm)

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

## Usage

Once you have your dependencies installed via pip, run the script in terminal via

```
python movie_.py
```

**Note** If the lightfm dependency doesn't work for you via pip, just install it from source by running these two commands.

```
git clone git@github.com:lyst/lightfm.git
```
```
cd lightfm && pip install -e .
```

If you still have dependency version issues, use [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/). 

## Credits

Learn Python for Data Science #3' by @Sirajology on [YouTube](https://youtu.be/9gBC9R-msAk).
