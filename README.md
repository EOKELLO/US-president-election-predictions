# US-president-election-predictions
assuming that we have been asked to help a candidate to become US president. The winner of the election will be the candidate winning the most grand electors. 

Grand electors are attributed at the state level: in each of the 51 states, there is a given number of grand electors to win (roughly, but not exactly, proportional to the size of the state) and the presidential candidate receiving the most local votes wins ALL the Grand Electors in that state.

Because the number of grand electors is not exactly proportional to the population, some states can be prioritized to increase the return on investment of the campaign. We assume here there are only 2 candidates, and no history (no trend of certain states to vote for a particular candidate or party). Hence, each vote is equally "expensive" to get, but some states grant more grand elector per capita.

You are provided with 2 tables: one giving the number of Grand Electors per state, the other the population per state.

You are asked to identify the states that should be prioritized to win the election, with a smart but simple algorithm (brute force computation of all possibilities to find the absolute optimum is not accepted, as it would be to computationally expensive). It is ok not to find the overall optimum, we just want a strategy that makes sense.

we shall embark on this project using the SQL language.

we shall analyse the data and come up with a possibilty if any to help a given candidate to win the election.
