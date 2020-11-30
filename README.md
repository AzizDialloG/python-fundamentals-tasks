# Python-fundamentals-tasks

## 1. October 5th, 2020:
Write a Python function calledcountsthat takes a list asinput and returns a dictionary of unique items in the list as keys and the number oftimes each item appears as values.  So, the input['A','A','B','C','A']should have output{'A': 3,'B': 1,'C': 1}.
Your code should not dependon  any  module  from  the  standard  library1or  otherwise.
You  should  researchthe task first and include a description with references of your algorithm in thenotebook.

## 2. November 2nd, 2020:
Write a Python function calleddicerollsthat simulatesrolling dice.  Your function should take two parameters:  the number of dicekandthe number of times to roll the dicen.  The function should simulate randomlyrollingkdicentimes, keeping track of each total face value. It should then returna dictionary with the number of times each possible total face value occurred. So,calling the function asdiceroll(k=2, n=1000)should return a dictionary like:{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}
You can use any module from the Python standard library you wish and you shouldinclude a description with references of your algorithm in the notebook.

## 3. November 16th, 2020:
Thenumpy.random.binomialfunction can be used tosimulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if acoin is flipped many times then the number of heads is well approximated by abell-shaped curve. For instance, if we flip a coin 100 times in a row the chance ofgetting 50 heads is relatively high, the chances of getting 0 or 100 heads is relativelylow, and the chances of getting any other number of heads decreases as you moveaway from 50 in either direction towards 0 or 100.  Write some python code thatsimulates flipping a coin 100 times.  Then run this code 1,000 times, keeping trackof  the  number  of  heads  in  each  of  the  1,000  simulations. Select  an  appropriateplot to depict the resulting list of 1,000 numbers, showing that it roughly followsa bell-shaped curve. You should explain your work in a Markdown cell above thecode.

## 4. November 30th, 2020:
Simpson’s paradox is a well-known statistical paradoxwhere a trend evident in a number of groups reverses when the groups are combinedinto one big data set.  Use numpy to create four data sets, each with anxarrayand  a  correspondingyarray,  to  demonstrate  Simpson’s  paradox.   You  mightcreate  yourxarrays  usingnumpy.linspaceand  create  theyarray  for  eachxusing notation likey = a * x + bwhere you choose theaandbfor eachx,ypair to demonstrate the paradox.  You might see the Wikipedia page forSimpson’s paradox for inspiration
