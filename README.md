##Smoking-Gun-Classification##
*Sean Steinle* | *sts137@pitt.edu*

**Brief**:<br>
This repository acts as my term project for LING1340: Data Science for Linguists. 
In this project, I'll be working on building a classifier that can sort through emails to flag useful information for investigators.
The data set that I will be training my classifier on is a set of released emails from around 150 users--mostly senior employees--at former American
energy company Enron. These emails are significant for various different types of natural language processing, but the unique situation of these
emails being sourced from a notoriously corrupt company allows for the domain specific training that I'm looking for.

Inspiration: <br>
I was inspired to take this on when I was looking through a catalogue of large data sets. The interesting thing though, 
is that most of these emails aren't really what you would expect out of the lore that surrounds insider trading or cooking the books. 
They're mostly like, "my kid wants a football for christmas." But I, like most people, want the juicy stuff! So I want to make a classifier that
can separate the signal from the noise effectively.

Data Specifications:<br>
- version: May, 2015
- size: 1.7GB, nearly 3,500 folders, over 500,000 emails
- history: The dataset was originally published by the Federal Energy Regulation Commission during their investigation of Enron. The data was then
worked on by the CALO (A Cognitive Assistant that Learns and Organizes), an organization within the AIC (Artificial Intelligence Center), that
is a part of the SRI (Stanford Research Institute). The data was later purchased and remodeled by researchers at MIT in the 2010's. I accessed and
found the data through former Carnegie Mellon professor William M. Cohen's website, linked below.
- organization: 
	relative path: maildir/~lastname-firstinitial~/~email directory, as per user~
		ex: maildir/arora-h/all_documents, maildir/arora-h/deleted_items, maildir/arora-h/discussion_threads, etc.
	other notes: per William Cohen
			'The dataset here does not include attachments, and some messages have been deleted 
			"as part of a redaction effort due to requests from affected employees". 
			Invalid email addresses were converted to something of the form user@enron.com whenever possible 
			(i.e., recipient is specified in some parse-able format like "Doe, John" or "Mary K. Smith") and to no_address@enron.com when no 
			recipient was specified.'


Resources:<br>
- to read more about the Enron scandal: https://en.wikipedia.org/wiki/Enron#2001_Accounting_scandals
- to access the data set: http://www.cs.cmu.edu/~enron/
