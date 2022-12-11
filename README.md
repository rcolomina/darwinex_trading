# Darwinex Trading

Project dedicated to develop trading systems and bots over Forex, in particular the Darwinex platform. 

Phases of development:

* Data collection
* Data analysis
* Build RL bots
* Deployment
* Monitoring
* Closing the Loop 
* Working Hypothesis

## Data Collecting

Darwinex FTP is a good place to take Forex data sub-second tick a tick. It is recommended for such a resolution of data a plugin to handle large time series. In postgres there is db timescale which increases dramatically operations on large table indexed by timestamp. 

## Data Analysis

Historical data is very useful, but it needs to be processed, analysed and summarized to make it useful

## RL Bots

Bots are automatic ways to trade in the finantial markets without stop 24-7. But there is a caveat on the bots. These have to be smart, something that is achieved using curated market data. RL stand for reinforcement learning, which is a way of machine learning that uses rewards to improve itself. RL bots are trained on simulated environment built from real data collection. This will help to work on automatas that will be adapted to the reality.

## Deployment & Monitoring

Bots have to be used, to close the development loop. Production feedback is the key to iterate the development making the bots profitable with enough experience.

## Closing the Loop & Working Hypothesis: 

Bots require an economic hypotesis before to define any rule over them. Economic ideas can be proved or disproved using bots. Those non profitable ideas will be discarted. Darwin would say, that an espice only will thrive in is able to adapt to its environemnt being able to survive. 


