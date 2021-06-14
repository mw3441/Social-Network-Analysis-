# Social-Network-Anlysis
Social network anlaysis has found utility is institutional, classroom and analyses of networked data in socially-based educational games. However, the utility of the method largely rests on being able to ascribe meaning to the structure of the network. Without meaningful interpretation of structure there is no added value to a networked model, you will find more suvccess simply regressing your outcome against student characteristics. Understanding measures of centrality and network structure in SNA are therefore an important, though difficult, aspect of the method. As with all SNA work, the vocabulary can be daunting though the ideas are relatively intuitive.
## Goal of this project
In this unit we will be working towards building several social network diagrams (graphs/sociograms) of a school classroom and then analyzing both centrality measures and clusters within the network.

We will be using data from:

Representing Classroom Social Structure. Melbourne: Victoria Institute of Secondary Education, M. Vickers and S. Chan, (1981)

Available from the [Index of Complex Networks](https://icon.colorado.edu/#!/)
## Baclground of the data
The data were collected by Vickers & Chan from 29 seventh grade students in a school in Victoria, Australia. Students were asked to nominate their classmates on a number of relations including the following three "layers":  

1. Who do you get on with in the class?  
2. Who are your best friends in the class?  
3. Who would you prefer to work with?  

We then have three data set for each of these questions: 

best.friends.csv, get.on.with.csv, work.with.csv.
## Procedure
### Data wrangling
Before we do any further analysis, we would manipulate each of the data sets so that it is suitable for building a social network using iGraph.

We load these three csv data set in table by order as D1, D2, D3.

Then we can use count and select functions to get the edge and vertex for each table.
### Visualize the Networks
