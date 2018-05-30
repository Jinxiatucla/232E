Project4
===

Data Resource
---
https://ucla.app.box.com/s/z45q3g5zrpay8b8gtbql6ojaecb7kj2u

Instruction
---
1. Name: as question{x}.ipynb, no space and other words!
2. mergefile.sh is for merge file, run it before start!
4. For all the questions, run the question1_new.ipnyb first to get the preprocessed.txt
	The format for preprocessed.txt is as following:
	"actor/actress Id\t\tmovieName1\t\tmovieName2....."
3. For questions after Question 6, if movie graph is needed, run question6_py.ipynb first to generate the edgelist file.(The edgelist file is about 1.5G, taking about half an hour to generate)


Useful tips for the following questions
---
1. When generating the graph for movies or actors, remember to use a suitable data structure...
(At first, I used the intersection and union function, it takes me more than 12+ hours to generate the only half of the graph...)T.T
2. In the edgelist for the movie graph, I used the index to represent the movie. The map for movie-id can be derived by running question_py.ipynb. (only run from the start to "generate movie-id map file" step)
3. Some useful movies and their ids: (Minions (2015), 100855), (Mission: Impossible - Rogue Nation (2015), 48390), (Batman v Superman: Dawn of Justice (2016), 12596)