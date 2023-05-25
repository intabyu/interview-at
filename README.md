# interview-at

[![Python](https://img.shields.io/badge/Python3.11-Python?style=for-the-badge&logo=Python)](https://www.python.org/downloads/release/python-3110/)
[![Linter](https://img.shields.io/badge/Codestyle-Black-black?style=for-the-badge)](https://github.com/psf/black)
[Rye](https://github.com/mitsuhiko/rye)

## Exercise

Given a set of two-dimensional points P (e.g. [(1.1, 2.5), (3.4,1.9)...]; the size of set can be 100s), write a function that calculates simple K-means. The expected returned value from the function is

1. a set of cluster id that each point belongs to, and
2. coordinates of centroids at the end of the iterations

Please use Python with standard libraries like numpy or pandas, but do not use Scikit-learn's k-means or any other k-means library, the idea is for you to implement k-means from scratch. Feel free to research and look up any information you need, but please note plagiarism will not be tolerated. You may spend as much time as needed, but as a frame of reference, an hour would be the maximum time frame. If more time is required, please send over the intermediate code at the one hour mark.

You may start the assignment whenever you are ready. Once you have completed this task, get back to us along with the code and how long it took you. Please feel free to get in touch with me if you encounter any questions or problems.

### Requirements

Minimum: implementation of the k-means function/class

Expected:

- Implement an interface similar to Sklearn (subset is fine)
- Test code
- Visualisation

### Deliverable 

Notebook with explanation and HTML output. Try to organise it with the following suggested sections:

- K-means function/class
- Test
- Visualisation

## Solution

Based on [https://en.wikipedia.org/wiki/K-means_clustering#Algorithms](https://en.wikipedia.org/wiki/K-means_clustering#Algorithms)
