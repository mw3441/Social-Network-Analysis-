# Social Network Analysis

Social network anlaysis has found utility is institutional, classroom and analyses of networked data in socially-based educational games. However, the utility of the method largely rests on being able to ascribe meaning to the **structure of the network**. Without meaningful interpretation of structure there is no added value to a networked model, you will find more suvccess simply regressing your outcome against student characteristics.  Understanding measures of centrality and network structure in SNA are therefore an important, though difficult, aspect of the method. As with all SNA work, the vocabulary can be daunting though the ideas are relatively intuitive.

## Goal of this project
In this unit we will be working towards building several social network diagrams (graphs/sociograms) of a school classroom and then analyzing both centrality measures and clusters within the network.

We will be using data from:

Representing Classroom Social Structure. Melbourne: Victoria Institute of Secondary Education, M. Vickers and S. Chan, (1981)

Available from the [Index of Complex Networks](https://icon.colorado.edu/#!/)

## Background of the data
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
We can graph the direct connection and visualize each of the graphs and color the nodes according to gender.

![social network analysis p1](./best_friends.pdf)

## Resources

## Videos

[Williams, N. (2014). Basics of Social Network Analysis.](https://www.youtube.com/watch?v=PT99WF1VEws)

[Complexity Labs. (2015). Social Network Analysis Overview.](https://www.youtube.com/watch?v=fgr_g1q2ikA)

[Complexity Labs. (2015). Network Centrality.](https://www.youtube.com/watch?v=NgUj8DEH5Tc)

[Complexity Labs. (2015). Network Clustering & Connectedness.](https://www.youtube.com/watch?v=2Oa7mef77nM)

## Knowledge Check
Once you have completed all tasks in the unit, please complete the [knowledge check](https://tccolumbia.qualtrics.com/jfe/form/SV_eJ0QJWNsklHsdro).

## Additional Materials
[iGraph. (2016). Get Started with R iGraph](http://igraph.org/r/#docs)

[Social Network Analysis with R - Examples](https://www.youtube.com/watch?v=0xsM0MbRPGE)

### Readings

[Bakharia, A., & Dawson, S. (2011). SNAPP: A Bird’S-eye View of Temporal Participant Interaction. In Proceedings of the 1st International Conference on Learning Analytics and Knowledge (pp. 168–173). Banff, Alberta, Canada:ACM.](https://doi.org/10.1145/2090116.2090144)

[Hanneman, R. & Riddle, M. (2005). Introduction to Social Network Methods. Riverside, CA:  University of California, Riverside](http://faculty.ucr.edu/~hanneman/)  
  * [Chapter 10: Centrality & Power](http://faculty.ucr.edu/~hanneman/nettext/C10_Centrality.html)  
  * [Chapter 11: Cliques & Subgroups](http://faculty.ucr.edu/~hanneman/nettext/C11_Cliques.html)  




