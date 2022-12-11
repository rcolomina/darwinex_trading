# Darwinex Trading

Project dedicated to develop trading systems and bots over Forex, in particular the Darwinex platform. 

Phases of development:

* Data collection
* Data analysis
* Build RL bots
* Exploitation

## Data Collecting

Darwinex FTP is a good place to take Forex data sub-second tick a tick. It is recommended for such a resolution of data a plugin to handle large time series. In postgres there is db timescale which increases dramatically operations on large table indexed by timestamp. 

## Data Analysis

Historical data is very useful, but it needs to be processed, analysed and summarized to make it useful

## RL Bots

Bots are automatic ways to enter and exit the market 24/7, but they need to be smart. For this RL bots trained on simulated environments based on real data will help to create such a bots

## Deployment & Monitoring

Bots have to be used, to close the development loop. Production feedback is the key to iterate the development making the bots profitable with enough experience.

## Closing the loop: Best Possible Designs

Bots require an economic hypotesis before to define any rule over them. Economic ideas can be proved or disproved using bots. Those non profitable ideas will be discarted. Darwin would say, that an espice only will thrive in is able to adapt to its environemnt being able to survive. 


