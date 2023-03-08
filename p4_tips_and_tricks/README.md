# P4 Tips and Tricks

## Overview

1. Running and Closing a Flask App
2. Headers and Content-Type
3. `jsonify` and `to_dict`
4. AB Testing
5. General Tips

## Running and Closing a Flask App

While it may seem intuitive, we can easily lose our Flask applications if we accidentally close a terminal or our terminal stops responding. We will take a look at [`demo.py`](./demo.py) to learn how to properly run and close our Flask app, even if we lose access ot the terminal we ran it from.

## Headers and Content-Type

We will visit Meena's website to see an example of how information is rendered in the web. We will learn about how response headers (or incorrect response headers) impact how information is rendered. Additionally, we will learn about how we can add custom information to our response headers by adding to [`demo.py`](./demo.py).

## `jsonify` and `to_dict`

We will discuss how to properly use `jsonify` and `to_dict` for the individual portion of P4 by adding data to our [`demo.py`](./demo.py). The data we are using is a subset of the dataset found [here](https://data.wisc.edu/instruction/) which looks at the classes with the highest enrollment at Wisconsin during Fall 2021 and Spring 2022.

## AB Testing

This section will discuss what AB testing is and how to implement in with our flask app. In this example, we will be taking the role of a CS advisor who is looking to boost the enrollment in CS 320. We will test two different ways of trying to boost the number of students who are enrolling in CS 320 to see which version will allow us to best boost enrollment.

## General Tips

We will finally discuss some general tips for P4. As always, start early, work with your group, and ask questions!