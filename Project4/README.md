Project4
===
```
.
├── Data
│   ├── actor_name_id_map.txt
│   ├── movie_id_map.txt
│   ├── movieid_actid.txt
│   ├── movieid_rate.txt
│   └── pagerank.Rdata
├── README.md
├── mergefile.sh
├── question10_R.ipynb
├── question10_hist_R.ipynb
├── question11_R.ipynb
├── question12_13.ipynb
├── question1_py.ipynb
├── question2_py.ipynb
├── question2_r.ipynb
├── question3_py.ipynb
├── question4_5_py.ipynb
├── question4_r.ipynb
├── question5_r.ipynb
├── question6_py.ipynb
├── question6_r.ipynb
├── question7_8_R_new.ipynb
├── question8c_py.ipynb
├── question9_R.ipynb
├── question9_hist_R.ipynb
├── question9_movie_id_rate_py.ipynb
└── rating_bipartite.ipynb
```
Introduction
---
This project contains to part to study various properties of Internet Movie Database.

1. explore the properties of a directed actor/actress network.
2. explore the properties of an undirected movie network.

Data Resource
---
https://ucla.app.box.com/s/z45q3g5zrpay8b8gtbql6ojaecb7kj2u

Instruction
---
1. We move all data to Folder Data, change every read file data to Data/file.
1. mergefile.sh is for merging file, run it before start!
2. question{x}\_{R/py}.ipynb represents for the code for the question x in R or in python. For most of the time, we use python to do the data preprocessing, such as mapping the movie name to the movie id. We use R to analysis the graph. Thus, if there two files for one question, run the python file first to generate the required file (such as edgelist.txt, movieid\_genre.txt, or movieid_rating.txt) and then run the R file to do the operations on the graph. 
3. We map the actors' name and movies' name to the ids. The details of mapping can be found in the movie\_id_map.txt and actor\_name\_id\_map.txt

