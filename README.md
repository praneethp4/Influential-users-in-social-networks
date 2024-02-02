# Influential-users-in-social-networks
Our objective is to analyze and understand the dynamics of influence in the social media landscape.

## DATASET
This dataset consists of 'circles' (or 'friends lists') from Facebook.
This anonymized dataset includes node features (profiles), circles, and ego networks.
The edges are undirected .
10 ego-networks, consisting of 193 circles and 4,039 users.
Features of various nodes are described in the following format:[Type]:[Subtype]:attributeName
 

## PROPOSED SYSTEMS
In this project, we propose an approach for identifying influential users in social networks using social network analysis techniques. We first analyse the network connections between users to identify the nodes with the highest centrality measures
#### Closeness Centrality :
###### Core idea: A central node is one that is close, on average, to other nodes.
###### Input: Graph and a node
###### Output: value [0,1] after standardization (1 being highly central)
#### Betweenness Centrality :
###### Core Idea: A central actor is one that acts as a bridge, broker or gatekeeper.
###### Input: Graph and a node
###### Output: value [0,1] after normalization (1 being highly central)

#### Eigenvector centrality :
###### Core Idea: A central actor is connected to other central actors.
###### Input: Graph
###### Output: value [0,1]

#### USING ASSOCIATION RULE LEARNING 

It is a data mining technique used to discover interesting relationships or patterns within a dataset.
While it is not typically used directly to find the most influential user in social networks, These patterns can provide insights into the influence or impact a user may have within their network.
##### Steps:
###### Date preparation
###### Association rule mining (Apriori Algorithm)
###### Rule Evaluation
###### Influence Assessment
###### Additonal Analysis


#### RESULTS
The output list contains the following information:
The name of the user.
The names of the interests that the user shares with other users.
 
 
