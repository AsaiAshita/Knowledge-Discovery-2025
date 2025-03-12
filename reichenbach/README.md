# WRITTEN PROBLEMS
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
  c] For simplicity's sake, we assume that <br />
**[4]** <br />
  a] <br />
  b] <br />
  c] <br />
**[5]** <br />

**[6]** <br />
  a] <br />
  b] <br />
  c] <br />
**[7]** <br />
  a] <br />
  b] <br />
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

