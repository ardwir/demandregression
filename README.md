# Demand Management Prediction

Dataset from: https://www.aiforsea.com/traffic-management

Prediction using linear reggression model


The given dataset contains normalised historical demand of a city, aggregated spatiotemporally within geohashes and over 15 minute intervals. The dataset spans over a two month period. A brief description of the dataset fields are found below:

- **geohash6**  : geohash level 6, 
Geohash is a public domain geocoding system which encodes a geographic location into a short string of letters and digits with arbitrary precision. You are free to use any geohash library to encode/decode the geohashes into latitude and longitude or vice versa.

- **day**        : day, where the value indicates the sequential order and not a particular day of the month

- **timestamp**  : start time of 15-minute intervals, in the following format: <hour>:<minute>, where hour ranges from 0 to 23 and minute is either one of (0, 15, 30, 45)

- **demand**     : aggregated demand normalised to be in the range [0,1]

#this is the FGA project
