# RoutePredictionAlgorithm

A Machine learning algorithm incorporating Ensembling model and Genetic algorithm

Initially using NYC taxi data, distance between two points is stored in a XG Boost ensembling model

We then combine weather data with the already present model using LightGBM model

Then , we use Genetic algorithm to find optimised route vector which then given on a UI presents optimal path for taxi vehicles.
