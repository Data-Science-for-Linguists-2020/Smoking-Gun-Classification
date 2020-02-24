## Project Plan<br>
Sean Steinle | sts137@pitt.edu
___
1. **cleaning/prepping data**, loading into a DF, all that jazz.
	- I understand this will be harder than I'm making it sound, but I'm not sure what the exact steps are.
___
2. undergo **basic sentiment analysis** on all Enron emails
	- general plan:
		1. use pre-loaded, simple tagger (likely just Naive-Bayes)
	- questions:
		1. how to partition?
		2. I need tags(i.e. "blah blah blah happy email here", "POS"), right?
			1. get tags from pre-loaded tagger
			2. manual?
___
3. customize **base ML model**
	- general plan:
		- tweak the original sentiment analysis model with my own features
			- I'm almost certainly at the mercy of the best-fitting model out there... right?
	- questions:
		1. which feats?
			1. should I be reading books about Enron for more domain specific knowledge?
			2. unsupervised ML (Jevon mentioned this)
		1. which technique of ML would be most effective (and practical??)
___
4. **data analysis**
	- general plan:
		1. basic metrics:
			1. classifier accuracy
			2. classifier confidence accuracy (I would really like a probabilistic rating schema for each email, 1-10 or something with 10 being incriminating)
		2. effectiveness on other email corpora?
			1. this is probably very hard if at all possible, but it would be really cool.
	