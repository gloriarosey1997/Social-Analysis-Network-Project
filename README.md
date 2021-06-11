# Social Network Analysis Project

Social network analysis is the process of investigating social structures through the use of networks and graph theory. The purpose of this project is to analyze classroom social structure.

## Preparation and Task

* Data Wrangling
  Manipulate datasets (best.friends.csv, get.on.with.csv, work.with.csv) to make them suitable for social analysis. 
  
* Task
  1. Who do you get on with in the class?  
  2. Who are your best friends in the class?  
  3. Who would you prefer to work with? 

## Visualize the Networks

According to the gender, visulize networking in the class based on three questions above. We can see some sudents have strong connection while some have weak. For example, students with ID number 18 and 25 are at the outer edge of the network.
![1](https://user-images.githubusercontent.com/70673374/121748469-a5488880-cace-11eb-8e37-21b532bf69fa.png)
![2](https://user-images.githubusercontent.com/70673374/121748488-b2657780-cace-11eb-835a-e5939fcb3229.png)
![3](https://user-images.githubusercontent.com/70673374/121748496-b5606800-cace-11eb-94bb-f141e72eb07f.png)

## Centrality Measures

By analyzing degree centrality, we can see three students with ID number 11, 8, 6 are the people get the highest scores in corresponding question. Student 11 is the one the most of times each student was chosen by others to get along well with. Student 8 is the one the most of times each student was chosen by others as best friends. Student 6 is the  one the most of times each student was chosen by others as most wanting to work with.

By analyzing betweeness centrality, we can see who are the people can influence others the most. Degree centrality counts the number of links incident upon a node; Betweeness centrality is a method of determining how often a node influences the flow of information in a graph. It's often used to find nodes that act as a link between two parts of a graph.

## Simple Sturcture

By using dyad to analyze connections between a pair of people. Then triad is used to perform a triad census of a directed network. 

dyad census can classify dyad in a graph.It measures the relationship between pair of vertices in 3 status: mutual, asymmetrical, non-existent.Get on with has highest mutual connection which means students tend to choose get on with others than become best friends or prefer work with.

Triad census counts the different subgraphs of three vertices in a graph.

## Conclusion

In the analysis, we can see student with id = 8 has the highest closeness centrality in best friend part and get on with part. This means this student is popular among peers.From simple structure part, we can see there are 280 non-existent connection in best friend part, it seems like a group of students is exclusive, I recommend teacher to encourage students to strengthen communication between each other.

To improve the analysis, the variable I want to know is the ethnic group. It may help us to analyze social network from the other perspective.


## Tools 

R
![1](https://user-images.githubusercontent.com/70673374/121748463-a37ec500-cace-11eb-8f8f-1b3fafaf1109.png)

RStudio

## Materials

[iGraph. (2016). Get Started with R iGraph](http://igraph.org/r/#docs)

[Social Network Analysis with R - Examples](https://www.youtube.com/watch?v=0xsM0MbRPGE)

[Bakharia, A., & Dawson, S. (2011). SNAPP: A Bird’S-eye View of Temporal Participant Interaction. In Proceedings of the 1st International Conference on Learning Analytics and Knowledge (pp. 168–173). Banff, Alberta, Canada:ACM.](https://doi.org/10.1145/2090116.2090144)
