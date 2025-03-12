# WRITTEN PROBLEMS
NB: the comma is used in the following to separate thousands. <br />
**[1]** <br />
  a] Using the permutation rule, and knowing that every person can only appear once, we have 10*9*8*7*6*5*4*3*2*1 = 10! = 3,6288,00 possible combinations. <br />
  b] Because we know that two people need to always stick close, we can consider the two of them as a unique choice when accounting for the number of possible combinations and multiply the total by 2, due to the fact that there is no imposed ordering in which the two man can sit, which means there are a total of 2*1 = 2 different combinations they can sit. Because of this, there are a total of (9*8*7*6*5*4*3*2*1)*2 = 9!*2 = 725,760 possibl combinations. <br />
  c] In order to respect the constraint, we just need to alernate our choice between the two groups, which we can eaily do as shown before by using the permutation rule and alternating the choice between the two groups. This means that there are 5*5*4*4*3*3*2*2*1*1 = 5!*5! = 14,400 posible combinations. <br />
  d] Using the same reasoning we did in answer b, we consider the various couples as a single entity, hence we are considering only a set of 5 elements. As before, every couple can be sit in 2 different ways, hence we need to multiply the number of combinations with the number of possible ways the couples can sit in order to account for this. Using again the permutation rule, we have that there are a total of 5*4*3*2*1 = 5! = 120 possible combinations for a single seating pattern. Considering that we have a total of 2*2*2*2*2 = 2^5 = 32 possible seating patterns, we have a total of 120*32 = 3,840 possible combinations  <br />
**[2]** <br />
  This is a combinatory problem, where we are trying to pick k numbers that are lower or equal to n (the contraint does not pose a problem, because combinations are unordered). Because of this, the number of possible combinations is equal to n!/(k!*(n-k)!) <br />
**[3]** <br />
  a] We have n*m squares and we want to know how many paths there exist between (1,1) and (n,m). Because we can only move down or right, we will reach the (m,n) square in at least (n-1) + (m-1) moves (for example, if you always go down and then right once you can't do it anymore, you traverse n + m - 2 cells). As a consequence, if we want to find all possible paths, we want to know in how many different ways can we arrange these n + m - 2 moves. We can do so as such: (n+m-2)!/((n-1)!*(n+m-2-n+1)!) = (n+m-2)!/((n-1)!*(m-1)!) <br />
  b] The same as above, but we have a constraint on the first move, so, instead of -2, we have a -3 (due to the fact that, instead of making m-1 possible moves, we will make m-2), so the formula is as follows: (n+m-3)!/((n-1)!*(m-2)!) <br />
  c]  [under construction...] <br />
**[4]** <br />
  a] First, choosing 5 cards out of 52 is equal to the binomial (52,5), which is equal to 2,598,960 combinations. Then we need to calculate how many possible card combinations for the same seed there are for a hand of 5 cards and we need to multiply it by the number of possible seeds, so 4. This equals to binomial (13,5)*4 = 1287 * 4 = 5,148 possible combinations, which includes both flush and straight flush. Now we can calculate the probability for one of these two possibilities as such: 5,148/2,598,960 = 0,00198 = 0,198%. <br />
  b] Firt, we choose the values for which we want the couples, so which amounts to having binomial (13,2) = 78 possible combinations. Then we choose the suit for the first and for the second couple, with both values being equal to binomial (4,2) = 6 and then we select the fifth card between the other values, which equals to having binomial (11,1) = 11 possible choices of binomial (4,1) = 4 possible selections of a seed. Combining all of these, we get that the probability for having two couples is: 78*6*6*11*4/2,598,960 = 0,04754 = 4,75%  <br />
  c] First, we have 13 possible values for such an outcome and we need to have all the seeds, so in this case we would have binomial (4,4) = 1. Then, as above, we get a card between all the 12 possible available values (binomial (12,1) = 12) and of one between the 4 possible seeds (binomial (4,1) = 4). Because of this, we obtain that the probability of a four of a kind is: 13*1*12*4/2,598,960 = 0,00024 = 0,024% <br />
**[5]** <br />
  [under contruction]
**[6]** <br />
  a] There are a total of binomial(8,3)*binomial(6,3) = 56 * 20 = 1,120 possible combinations. <br />
  b] Like in question 1, we consider the two elements as a unique value (because we can either choose one, the other, or neither), thus we get that we have a total of binomial(7,3)*binomial(6,3) = 35 * 20 = 700 possible combinations. <br />
  c] We can subtract from all the possible combinations the ones in which the two are present, which means total_combinations - (binomial(7,2) * binomial(5,2)) = 1,120 - (21*10) = 1,120 - 210 = 910 possible combinations are still valid. <br />
**[7]** <br />
  a] We need to use the divider method: considering that we need to invest in all of four - meaning that we remain with 20-(4+3+2+1) = 10 million to invest - we have that: binom(10+4-1, 10) = 286, so we have 286 different ways to proceed. <br />
  b] Like above, we use the divider method for the 4 possible scenarios: (1,2,3), (1,2,4), (1,3,4), (2,3,4), and then we add the possible strategies we have calculated before, as they are also viable in this scenario. This is possible because we don't care about the order of the elements. As such, we obtain that:<br />
  binom(14+3-1,14) + binom(13+3-1,13) + binom(12+3-1,12) + binom(11+3-1,11) + 286 = 120 + 105 + 91 + 78 + 286 = 680 possible strategies. 
**[8]** <br />
  a] <br />
  b] <br />
  c] <br />
**[9]** <br />
  a] <br />
  b] <br />
**[10]** <br />
  a] <br />
  b] <br />
**[11]** <br />
**[12]** <br />

