##Progress Reports
Sean Steinle | sts137@pitt.edu
___
**Progress Report #1**:<br>
*February 4th, 2020*

*Brief*: This week, I finished polishing up my ideas for my project. I started my GitHub repository and filled the README, project-ideas, and progress-report files.
I also gathered details about the history and organization of the dataset, as well as a list of relevant resources for visitors to my project.
___
**Progress Report #2**<br>
*March 16th, 2020*

*Brief*: As of today, my big accomplishment is making a function that can create DataFrames given a user and a range of emails in the all_documents folder to check.
That being said, this is relatively buggy and it also has many flaws as I pointed out. I have a nice little summary (#3) in my notebook. I'm going to try to take steps
to fix these problems and make the algorithm work on a larger portion of my dataset, but this is a step forward to work off of. Going to definitely need advice
for my EDA phase though.

*Sharing Data*: I'll be sharing one of the user's(cash-m) email directory, as well as linking the original source for where I downloaded the corpora. I picked this user as it
is a prototypical file directory for the rest of the corpus. This certainly falls under fair use, but I'm hesitant to release any more because Cohen (the professor) whose website
I downloaded the corpus from) did not specify a license. In short, I gave visitors a slice of the cake and a link to the cake shop.

*License*: This project will be licensed under the MIT License. I want a simple and open-sourced license that allows users to add onto my finished product.
___
**Progress Report #3**<br>
*April 14th, 2020*

**Brief** I've finalized my means of reading through the corpus! I'm able to read through the majority of the corpus with great coverage to scan in useful tags and information.
Let's break it down into a data summary and future directions.<br><br>
**Data Summary**:
The shortened DF I create ends up looking pretty useful, with only a few misalignments. There are a few final considerations I have in reading through all of my emails:
	1. My kernel dies around the *s* users. Not 100% sure why this is, although it dies on the same directory every time, and the directory it dies on seems to be the most complex
	directory out of any user.
	2. I'm really hope to use the CRC to remedy this problem, but using the CRC comes with another roadblock: my data can't be accessed from the CRC. Lame.
	3. Finally, my traversal is very specific to this dataset and does systemically disregard nested folders. Essentially, **I make an assumption that no user will have folders inside of folders**,
	as it simplifies the entire traversal by orders of magnitude.<br><br>
**Future Directions**
I've started on my Data Exploration and Analysis, but I have a bit of an embarassing problem: I'm not sure what to do with my data now. My data isn't annotated, so I can't do our usual LING1330/1340
treatment of making a simple classifier and tweaking parameters. There are a few different things I can try instead:
	1. *Annotate The Data*: In this case I would be able to achieve my original goals while also providing a very useful resource for future email-interested data scientists like myself. Unfortunately,
	I'm not going to be able to annotate 500,000 emails, and even 10,000 would be a huge committment. I think this is something I'd come back to if the next point doesn't work out.
	2. *Unsupervised Learning*: This is what I was expecting to do from the start, although now it's a little more daunting. Most of our training has been in supervised learning or in unsupervised learning *about*
	annotated data (like GridSearchCV).<br><br>
**Updated Data**: While I didn't update my data, I found that my data_sample was missing from my corpus, so I fixed that. Also, I checked to make sure that my data_sample reflects some of difficulties in file hierarchy
that I encountered in the final stages of data processing--it does!
___


