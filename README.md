# Euclidean Distances - Angles for finding similarities between buildings. A first insight in ML classification ideas...

## Description

This program implements the Euclidean distance (https://en.wikipedia.org/wiki/Euclidean_distance), along with the angles between two vectors (https://en.wikipedia.org/wiki/Dot_product#/media/File:Tetrahedral_angle_calculation.svg). The purpose of this program is to show how we can implement the concept of "vectorization" to perform classifications tasks. In particular, in this implementation we provide fictional data of different buildings, and compare how similar they are, via the Euclidean distance, and the angle between the vectors that describe the buildings.

## Attributes

The attributes (fictional data) considered in this implementation is:

1. Number of floors in the building
2. Number of rooms in the building
3. Number of bathrooms in the building
4. Number of elevators in the building
5. Number of pools in the building
6. Number of movie theaters in the building

## Execution of the program

In your terminal run the command: python EuclideanDist.py

And the program will show the "Euclidean distance similarities" along with the "angles opening similarities".

## Relevant classes:

1. Buildings_similarities -> Class that implement the attributes we consider relevant of a building. This class implements a vectorization method, so we can show explicitly how any object can be understand via some of its internal attributes built upon a vector in the field of Real numbers.

## Relevant functions:

1. euclidean_dist -> Compute the Euclidean distance of two input building vectors.
2. vect_norm -> Compute the norm of the input building vector.
3. normalized_build_vector -> Normalize all of the building vectors passed in the input list.
4. compute_cos_angle -> Compute the angle between the two input building vectors.

