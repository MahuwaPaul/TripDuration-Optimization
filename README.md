# Trip Duration Optimization
A common problem in the road infrastructure of metropolitan cities around the world is intense traffic congestion. Many of these problems can be addressed by shared economy. One individual can use another’s resources for a short period of time to gain immediate benefits. Recently some countries use vehicle sharing as a necessity. One of the most interesting ways of sharing is either car or taxi sharing. Finding efficient vehicle routes is also an important problem. The reduction of delivery time and length is a challenging issue. Here, we handled the trip duration optimization problem for taxi vehicles. Traveling Salesman Problem framed here as a well-known research problem. The objective is to find the shortest route that visits a set of locations. Optimization techniques are required to intelligently search the solution space and ﬁnd near-optimal solutions. Firstly, for every pair of pick-up and drop-off locations XGBoost model  used  to predict trip duration between them. Ant colony and genetic evolutionary algorithm used to find the best travel itinerary for the vehicles.
# Requirements
1. python3
2. numpy
3. pandas
4. xgboost
5. matplotlib
Our coding was done in an online environment Collaboratory or “Colab” which is a free Jupyter Notebook environment that runs entirely in the cloud. In “Colab” the Jupyter Notebook, the above requirements already privided so we don't need to install anything separately.
# Dataset
The NYC Taxi and Limousine Commission Trip Record data used in the project, which can be accessed at this URL: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page. The dataset has 11 attributes with 1.5 million trip records in the year 2016. 
# Data Visualization
DataVisualization.ipynb used for to visualize the data and ﬁgure out the best features to be used for the machine learning model at the next step.
# Machine Learing
XGBOOST.ipynb used to predict travel times between pickup and dropoff locations.
# Ant Colony Optimization
The ant colony algorithm is a meta-heuristic algorithm whose working method is to simulate the foraging process of ants. We tried to minimize our travel cost by ACO.ipynb with varing different setting of the parameters.
# Genetic Evolution
Genetic Evolution is biologically inspired meta-heuristic that takes its steps from the process of evolution. Execution of GE.ipynb for different setting choose the best path for every generation.
