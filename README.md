# differential-privacy-on-IMDB-Dataset
## What the Project Does:
  The project aims to utilize differential privacy techniques to protect the privacy of individuals while querying a public dataset such as the IMDb database. Differential privacy is a concept that helps in preserving the privacy of individuals by adding noise to the data. The PyDP library provides an easy-to-use interface to implement differential privacy methods in Python. By using PyDP library to query IMDb database, we can ensure that the data queried does not reveal sensitive information about individuals. This project also provides ways to evaluate the privacy and utility tradeoff. Differential privacy methods can add noise to the data, which can affect the accuracy of the results. The project provides ways to evaluate the privacy and utility tradeoff by measuring the accuracy of the results before and after adding noise to the data. This repository include 5 query function for the IMDB dataset, each query function have a differential private version and a non-dp counterpart.

## Why the Project is Useful:
  In today's world, where data breaches and privacy violations are on the rise, it is essential to ensure that individuals' privacy is protected while using public datasets. Using differential privacy techniques with the PyDP library can help in achieving this goal. This project can be useful for researchers, data analysts, and anyone who wants to use public datasets while ensuring privacy.

## How Users Can Get Started with the Project:
  To get started, there are a few library needs to be downloaded before you can run the project. The 3 library needed to run this project is numpy,panda and pydp which can be downloaded using (assume you have python and pip already installed) pip install numpy panda python-dp.
  
