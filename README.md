# Movie_KnowledgeGraph_QA

#### Description:
 
The task here is to given a knowledge base of the WikiMovie we create a KnowledgeGraph.
The KnowledgeGraph is used to do QA.

The KnowledgeBase sample stored in 'wiki_entities_kb.txt' are as follows:
```
Kismet directed_by William Dieterle
Kismet written_by Edward Knoblock
Kismet starred_actors Marlene Dietrich, Edward Arnold, Ronald Colman, James Craig
Kismet release_year 1944
Kismet in_language English
Kismet has_tags bd-r
Kismet has_plot Hafiz, a rascally beggar on the periphery of the court of Baghdad, schemes to marry his daughter to royalty and to win the heart of the queen of the castle himself.
```

#### KnowledgeGraph
KnowledgeGraph is created using 'networkx'. 
Networkx provide a good visualisation of the KnowledgeGraph. 
DirectedGraph is used to preserve capture the proper relation.
Information is stored in triplet form (subject, relation, object)


#### Question Analysis:
<b> Case 1 </b>: 
< question_word > < attribute > < Name >  
Example: who directed the movie Kismet ?
  
<b> Case 2 </b>:
< question_word > < Name > < attribute >  
Example: when was Kismet released?
  
<b> Case3 </b>:
< Name > < attribute > < question_word >   
Example: Kismet directed by whom? 
  

#### Sample Question Answer Pair
<b>Question:</b> what movies did Temuera Morrison act in   ?  
<b>Answer:</b>     
Tracker  
Once Were Warriors  
River Queen  
#### =================
  
#### Run the Code:  
Python version: 3 and above  
Install the following Python Libraries:    
1) Networkx :  
```python
pip install networkx
```
2) nltk:  
```python
pip install nltk
```
3) sklearn: 
```python
pip install sklearn
```

#### References:
KnowledgeBase is taken from WikiMovies   
WikiMovies : https://arxiv.org/abs/1611.09823
  
  
For more information feel free to contact :  
<b> Rohit Mishra: </b> rohitpro129@gmail.com , phc2014002@iiita.ac.in  
<b> Soham Dwivedi: </b> sohamdwivedi2012@gmail.com 


