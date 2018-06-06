Project4
===

Data Resource
---
https://ucla.app.box.com/s/z45q3g5zrpay8b8gtbql6ojaecb7kj2u

Instruction
---
1. mergefile.sh is for merging file, run it before start!
2. For all the questions, run the question1_new.ipnyb first to get the preprocessed.txt
	The format for preprocessed.txt is as following:
	"actor/actress Id\t\tmovieName1\t\tmovieName2....."
3. question{x}_{R/py}.ipynb represents for the code for the question x in R or in python. For most of the time, we use python to do the data preprocessing, such as mapping the movie name to the movie id. We use R to analysis the graph. Thus, if there two files for one question, run the python file first to generate the required file (such as edgelist.txt, movieid_genre.txt, or movieid_rating.txt) and then run the R file to do the operations on the graph. 
4. We map the actors' name and movies' name to the ids. The details of mapping can be found in the movie_id_map.txt and actor_name_id_map.txt

