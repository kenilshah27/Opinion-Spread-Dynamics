# Opinion-Spread-Dynamics

**Voter Model** - In this model, each of the individuals has an opinion {-1,1} in the beginning. Now with time people interact with their neighbors and start to take up opinions of their neighbors. This model is based on this fact and takes this interaction into consideration. Each timestep we pick one person at random and then assign him/her the opinion of one of its randomly picked neighbors. 
This is a basic concept on which this model works. 

**Sznajd** - This is also an interaction model where each of the individuals have an initial opinion of {-1,1} . A pair of neighboring agents is picked and if they have a similar opinion , each of their neigbour takes up that similar opinion. If they do not agree with each
other, no changes happen in the model. This is based on the fact that if many people have a certain opinion, people tend to take up that
opinion. But if an individual has some opinion, people generally do not start taking up his/her opinion.

**Majority Rule Model** - In a social setting, people would have some opinion {-1,1} initially. In each step, a random group of members is selected, and each of the memeber in the group , takes up an opinion that is the majority opinion of the group. SO if in a group 6 people have a positive opinion and 2 have a negative opinion, after interaction each of them will have a positive opinion. A variation of this model is that, an individual is selected and he takes up the opinion that is majority among its neighbours. So if a person has a negative opinion, but 6 out of 8  of its neighbors has a postive opinion, he would end up taking the positive opinion.

**Hegselmann_Krause model** - This is similar to Deffuant model in which a pair of individual interact, and takes up opinion that is an average of their opinion. What happens in Hegselmann_Krause model is that instead of taking one of its neighbors, it selects all of its neighbors. The opinionthat is the average of all the opinions of its neighbors is then adopted by the individual in question. 
