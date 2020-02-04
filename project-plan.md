Project Plan
Sean Steinle | sts137@pitt.edu

1. cleaning/prepping data, loading into a DF, all that jazz.
	a. I understand this will be harder than I'm making it sound, but I'm not sure what the exact steps are.

2. undergo basic sentiment analysis on all Enron emails
	general plan:
		a. use pre-loaded, simple tagger (likely just Naive-Bayes)
	questions:
		a. how to partition?
		b. I need tags(i.e. "blah blah blah happy email here", "POS"), right?
			1. get tags from pre-loaded tagger
			2. manual?
3. customize base ML model
	general plan:
		a. tweak the original sentiment analysis model with my own features
			1. I'm almost certainly at the mercy of the best-fitting model out there... right?
	questions:
		a. which feats?
			1. should I be reading books about Enron for more domain specific knowledge?
			2. unsupervised ML (Jevon mentioned this)
		b. which technique of ML would be most effective (and practical??)
4. data analysis
	general plan:
		a. basic metrics:
			1. classifier accuracy
			2. classifier confidence accuracy (I would really like a probabilistic rating schema for each email, 
							1-10 or something with 10 being incriminating)
		b. effectiveness on other email corpora?
			1. this is probably very hard if at all possible, but it would be really cool.
	