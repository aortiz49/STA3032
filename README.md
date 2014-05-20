 # STA3032 Notes

__Compiled by: Andy Ortiz__

![Statistics with Chen!](http://www.theproducersperspective.com/wp-content/uploads/2014/04/stats.jpg)

These notes are compiled from the textbook, and in-class powerpoint slides. 

_Disclaimer: This is not meant to replace your studying. It is only a supplement._
 
## Table of Contents

* [Introduction](#introduction)
	* [Concepts](#concepts)
	* [Statistics](#statistics)
		* [Sample Mean](#sample-mean)
		* [Sample Median](#sample-median)
		* [Sample Variance](#sample-variance)
		* [Sample Standard Deviation](#sample-standard-deviation)
		* [Sample Quartiles](#sample-quartiles)
* [Probability](#probability)
	* [Sample Space](#sample-space) 
	* [Event](#event)
	* [Set Operation](#set-operations)
		* [Complement](#complement)
		* [Union](#union)
		* [Intersection](#intersection)
	* [Mutually Exclusive Events](#mutually-exclusive-events)
	* [Probabilities](#probabilities)
		* [Axioms](#axioms)
		* [Fundamental Results](#fundamental-results)
		* [Calculating Probability](#calculating-probability)
	* [Counting Methods](#counting-methods)
		* [Permutation](#permutation)
		* [Combination](#combination)
	* [Conditional Probability](#conditional-probability)
	* [Independance](#independance)
	* [The Law of Total Probability](#the-law-of-total-probability)
		* [Baye's rule](#baye's-rule)
	
	
		


## Introduction
	UMAD?
	
### Concepts
* **Statistics** is a study of the collection, organization, analysis,
interpretation, and presentation of data.

* The **Population** is the entire collection of subjects about which the
information is of interest.
	* All UF students
	* All Florida residents
	* All gas stations in Florida

* A **Parameter** of a population is a numerical summary of the
population.
	* The mean amount of sleeping hours per week of all UF
students
	* The mean age of all Florida residents
	* The average gas price of all gas stations in Florida

* A **sample** is a subset of the population, containing the subjects or
outcomes that are actually observed.
	* All engineering major UF students
	* All Gainesville residents
	* All gas stations in Miami

		* _A sample that is **representative** of the population is a good sample_
* A **simple random sample (SRS)** is a sample chosen in a way such that each member of the population has an equal chance to be chosen.

---
### Statistics

* A **statistic** is a numerical summary of a sample taken from the population.

#### Sample Mean

Let X<sub>_1_</sub>, . . . ,X<sub>_n_</sub> denote a sample size _n_. The **Sample Mean** is defined to be 

<p align="center">
<img src="http://imgur.com/VjyEiNp.png" alt="Drawing" style="width: 150px;"/> 
</p> 

Symbollically, it is written as

<p align="center">
<img src="http://i.imgur.com/C7mdjhR.png" alt="Drawing" style="width: 110px;"/> 
</p> 

#### Sample Median

Let X<sub>_1_</sub>, . . . ,X<sub>_n_</sub> denote a sample of size _n_. The **Sample Median** is deﬁned to be a number that divides the ordered data in halves so that the upper half is separate from the lower half.

_**=** Example **=**_ 

	
Data Sample = {4, 6, 7, 8, 1, 2, 3, 5} 

=> _Median_ : 4.5
 
 * A recipe for finding a sample median:
 
 	_Step 1_ : Sort the sample in increasing order
 	
 	<p align="center">
 	<img src="http://i.imgur.com/HsHZaMJ.png" alt="Drawing" style="width: 240px;"/> 
	</p> 
	
   _Step 2_ :  Find a sample median 
	
   <p align="center">
   <img src="http://i.imgur.com/2w2mmcD.png" alt="Drawing" style="width: 340px;"/> 
	</p>  

#### Sample Variance 

Let X<sub>_1_</sub>, . . . ,X<sub>_n_</sub> denote a sample size _n_. The **Sample Variance** is defined to be 

<p align="center">
<img src="http://i.imgur.com/iEF37Dm.png" alt="Drawing" style="width: 260px;"/> 
</p> 

<p align="center">
<img src="http://i.imgur.com/w1N9tLY.png" alt="Drawing" style="width: 180px;"/> 
</p>

#### Sample Standard Deviation

Let X<sub>_1_</sub>, . . . ,X<sub>_n_</sub> denote a sample size _n_. The **Sample Standard Deviation** is defined to be 

<p align="center">

</p> 

_**=** Example **=**_ 

Data Sample = {4, 6, 7, 8, 1, 2, 3, 5} 

=> _Sample Mean_ : 4.5 

=> _Sample Variance_ :   <img src="http://i.imgur.com/Nkw34A7.png" alt="Drawing" style="width: 295px;"/> 

=> Sample Standard Deviation : 
<img src="http://i.imgur.com/HWfpOu6.png" alt="Drawing" style="width: 180px;"/> 


#### Sample Quartiles

	Too easy to put. Sorry. Will add this weekend..or at somepoint.
	
## Probability

	Insert general description of probability...stuff here. Problem? ;)
	
### Sample Space

* **Sample Space** denoted by _S_ is the set of all possible outcomes of a statistical experiment.

_**=** Examples **=**_ 

1. Toss a coin twice with outcome denoted by ( * , * )  
 _S_ = {(H, H), (T, H), (H, T), (T, T), (H, T), (T, T)}
2. Toss a six-sided dice once  
 _S_ = {1, 2, 3, 4, 5, 6}
 
 
---
### Event

* An **Event** is a subset of the sample space _S_.

_**=** Examples **=**_ 

1. Toss a coin twice and the event of seeing head on the ﬁrst toss    
 _E_ = {(H, H), (H, T)} belongs to the sample space _S_
2. Toss a six-sided dice once, then the event of seeing an odd number  
 _E_ = {1, 3, 5} belongs to the sample space S 


Any statistical experiement has two special events: sample space _S_ and empty set _null_.

---
### Set Operations

Like numbers, we can also deﬁne operations on sets. The following are three basic set operations:

#### Complement

<img src="http://i.imgur.com/VigdqwZ.png" alt="Drawing" style="width: 140px;"/> 


 The **Complement** of _A_ is the set of the outcomes in _S_ not belonging to _A_ and is denoted by _A_<sup>_c_</sup>.

 _Note: A is the complement of A_<sup>_c_</sup>.
 
 
#### Union

<img src="http://i.imgur.com/tBq3md6.png" alt="Drawing" style="width: 140px;"/> 
 
 * The **Union** of _A_ and _B_ is the set of the outcomes in _S_ belonging to _A_ or B and is 
 denoted by  
 _A_ <img src="http://i.imgur.com/4pM32Nt.png" alt="Drawing" style="width: 14px;"/>  _B_.

  
#### Intersection 

<img src="http://i.imgur.com/BAY6lLz.png" alt="Drawing" style="width: 150px;"/> 

 * The **Intersection** of _A_ and _B_ is the set of the outcomes in _S_ belonging to _A_ and _B_ and is denoted by  _A_ <img src="http://i.imgur.com/8HGSAO9.png" alt="Drawing" style="width: 14px;"/>  _B_, or simply AB.

_**=** Example **=**_ 

Toss a coin twice and _A_ is the event of seeing H on the ﬁrst toss and _B_ is the event of seeing H on the second toss, that is:

<p align = "center">
<i> A </i> = {(H, H), (H, T)} and <i> B </i> = {(H, H), (T, H)} 
</p>

* The complements of _A_ and _B_ are

<p align = "center">
<i> A<sup>c</sup> </i> = {(H, H), (H, T)} and <i> B<sup>c</sup> </i> = {(H, H), (T, H)} 
</p>

* The union of _A_ and _B_ is 

<p align = "center">
<i> A <img src="http://i.imgur.com/4pM32Nt.png" alt="Drawing" style="width: 14px;"/> B </i> = {(H, H), (H, T), (T, H)} 
</p>

* The intersection of _A_ and _B_ is 

<p align = "center">
<i> AB </i> = {H, H} 
</p>

---

### Mutually Exclusive Events

<img src="http://i.imgur.com/5rxnI4N.png" alt="Drawing" style="width: 190px;"/> 


* _A_ and _B_ will be said to be **Mutually Exclusive** if they have no outcomes in common, i.e. _AB_ = _null_.

---

### Probabilities

The *Probability* of an event is a quantitative measure of how likely an event is to occur. It is denoted by _P_(_A_). _P_(_A_) is the proportion of times that event _A_ would occur in the long run, if the experiment were to be repeated over and over again.

#### Axioms of Probability

The three axioms of probability are 

1. Let _S_ be a sample space. _P_(_S_) = 1.
2. For any event A, 0 ≤ _P_(_A_) ≤ 1. (Probabilities are between 0% and 100%)
3. If events _A_ and _B_ are mutually exclusive, then _P_(_A_ <img src="http://i.imgur.com/4pM32Nt.png" alt="Drawing" style="width: 14px;"/>  _B_) = _P_(_A_) + _P_(_B_).

#### Fundamental Results

The following can be shown with the three probability axioms:

1. _P_(_A_<sup>_c_</sup>) = 1 - _P_(_A_), for any event _A_ in _S.
2. _P_(_null_) = 0.
3. Let _A_ and _B_ be two events with _B_ belonging to _A_. If _AB_<sup>_c_</sup> is the set of all outcomes, then _P_(_AB_<sup>_c_</sup>) = _P_(_A_) - _P_(_B_)


<img src="http://i.imgur.com/YmRys9n.png" alt="Drawing" style="width: 1190px;"/> 


 _**=** Example **=**_ 
 
	 TODO! 
	 
#### Calculating Probability

Let _A_ be an arbitrary event on a sample space _S_ which is associated with a statistical exprt. The classical calculation of probability of _A_  is
<p align = "center">
<img src="http://i.imgur.com/bFm7LCN.png" alt="Drawing" style="width: 360px;"/> 
<p/>

---
### Counting Methods

Assume a task that contains _k_ operations to be performed. If there are _n_<sub>_1_</sub> ways to perform operation 1, _n_<sub>_2_</sub> ways for operation 2, . . . , _n_<sub>_k_</sub> ways for operation _k_, then the total number of ways to ﬁnish the task is

<p align = "center">
<img src="http://i.imgur.com/pc2jCyn.png" alt="Drawing" style="width: 220px;"/> 
<p/>

#### Permutation

* A **Permutation** is an ordering of a collection of objects.

* There are six permutations of letters A, B, and C: 
   _ABC , ACB , BAC , BCA , CAB , CBA_.

* The total number of permutations of _n_ objects is 
<p align = "center">
<img src="http://i.imgur.com/E6GcxyQ.png" alt="Drawing" style="width: 240px;"/> 
<p/>

* For choosing _k_ subjects from _n_ objects with order to be considered, the number of ways is

<p align = "center">
<img src="http://i.imgur.com/v9SMTQg.png" alt="Drawing" style="width: 70px;"/> 
<p/>

#### Combination

* Each distinct group of objects that can be selected, regardless of order, is called a **Combination**.

 
* There is ONE combination of letters A, B, and C: {A, B, C}
  
* Any different ordering of A, B, and C is just redundant.

* The total number of combinations of _k_ objects from _n_ objects is

<p align = "center">
<img src="http://i.imgur.com/ixvzrku.png" alt="Drawing" style="width: 170px;"/> 
<p/>









 



	
	
 	
 		





