# Week 7 - Method 1: Reading at scale
*How can computers help us read? How do we make sense of millions of tweets, documents, or books? We’ll examine scholarly text analysis projects and learn a few tools for conducting our own analysis.*

### Prep for Tuesday:

* Read [Text Analysis Coursebook](http://walshbr.com/textanalysiscoursebook/) - read sections Issues in Digital Text Analysis, Close Reading, Cyborg Readers, Reading at Scale
* just a heads-up: [A showdown over solar is coming to Virginia](https://cardinalnews.org/2024/10/21/a-showdown-over-solar-is-coming-to-virginia/) - great local news source discussing local energy issues around data centers and AI. See the reports and data they point to. The Goldman Sachs report is a nice example of data viz.

## Tuesday, October 22

* icebreaker: what was the first book that left an impression on you as a kid? 
* homework recap > your essay proposal is due in two weeks! how are you feeling about your topic? 
* WordPress work
* Activity 7.1: Ways to Read (Taylor's Version)

### Prep for Thursday:
* Read: [Text Analysis Coursebook](http://walshbr.com/textanalysiscoursebook/) -  sections Topic Modeling, Supervised Classifiers, Sentiment Analysis
* [Argument Clinic](https://web.archive.org/web/20220122103133/http://scottbot.net/argument-clinic/) - this should be helpful for thinking about your proposal too!


## Thursday, October 24

* icebreaker: 
* rest of semester preview!
* Let's brainstorm some research questions before we embark on these tech challenges today.

* Text analysis methods and tools 
	* Activity 6.2 - How to build your corpus
		* [Ring-tum Phi dataset](https://github.com/wludh/dataset-RingtumPhi) 
		* Browse the RTP in the [Digital Archive](https://digitalarchive.wlu.edu/islandora/ring-tum-phi)
	* Activity 6.3 - a quick diversion into the command line 
		* On your computer, search for a program called `terminal` or `cmd.exe` (Windows).
		* Type `pwd` then hit enter. What do you see? 
		* Type `ls` then hit enter. What files/folder do you see? 
		* Type `cd Desktop` then `pwd`. Did you make it to your Desktop?
		* Use `cd [foldername]` and `cd ..` to navigate through your file structure to get to the RTP folder.
		* Navigate into a folder full of text files. Type `ls`. What if you wanted to combine all of them into one file? Try `cat *.txt > newfile.txt` - what happens? 
		* Interested in learning more? Check out this [tutorial for Mac](http://programminghistorian.org/lessons/intro-to-bash); this tutorial for [Windows](http://programminghistorian.org/lessons/intro-to-powershell); this [tutorial](https://learnrubythehardway.org/book/appendixa.html) covers either. 
	* Activity 6.4 - a quick diversion into Regular Expressions
		* Open the text file from one issue and copy the text.
		* Visit [http://regex101.com](https://regex101.com/) and paste your text in the "test string" section.
		* Refer to the Quick Reference section in bottom right to see how to match patterns in text. 
		* Can you figure out how to match the four digits of a year? What about a the Volume #? 
	* Activity 6.4 - Let's keep trying out text analysis tools
		* Practice getting some segment of the RTP into Voyant. 
		* Want to try out topic modeling? Download and install this [Topic Modeling Tool](https://github.com/senderle/topic-modeling-tool).
		* Have some text to clean up? [Lexos](http://lexos.wheatoncollege.edu/upload) has tools for cleaning it up, visualizing, and even some more advanced statistical analysis. 
		* [Google NGram Viewer](https://books.google.com/ngrams) might be a good one if you want to play around with big trends over time. [HathiTrust Analytics](http://analytics.hathitrust.org/) is another option for working with books. We're also trialing [JSTOR Constellate](https://constellate.org/) right now.



## Week 7 Assignments - Due Tuesday at 12pm


### Blog post #7
Let's take time to do a deep dive into one specific text analysis project. Select from the following list:

* [America's Public Bible](https://americaspublicbible.org/)
* [Robots Reading Vogue](http://dh.library.yale.edu/projects/vogue/)
* [Dash Amerikan](http://dashamerikan.scholarslab.org/)
* [Mining the Dispatch](https://dsl.richmond.edu/dispatch/)
* [Project TwitLit](https://twitlit.github.io/)

**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* 300-500 words. 
* Free from grammatical errors, typos. 
* Credit and link out to sources when appropriate. I won't require that you use a certain citation style, but you should be in the habit of crediting sources and using in-text links. If you feel better about using a formal citation style, go for it! 
* Address the following:
	* Who created this project? What is their institutional home and who made up their team? (No need to list every name, just summarize the types of people involved). 
	* What is the corpus? What is the source of the data? Is it something you can access and download yourself?
	* What are their research questions? Can you find them easily? If not, what can you surmise are the questions? Think back to the Argument Clinic article from this week. Can you see a hypothesis? Their testing? Their contextualization? 
	* What type of text analysis is being done? Are they counting words, doing topic modeling, or sentiment analysis? How do you know? 
	* How do you feel about the design of the website? What are its affordances? Are the data visualizations well-done? 

### Activity log #7 

Now that you're comfortable with Voyant, let's return to the [Ring-tum Phi](https://github.com/wludh/dataset-ringtumPhi) and compare it to another corpus: the [Alumni Magazine](https://github.com/wludh/dataset-AlumniMagazine). Select similar portions of time from both the Ring-tum Phi and the Alumni Magazine. You probably don't want to start with the entire decade - it's often best to start with a small bit of data and move up from there.

Assemble your corpus. Now that you're familiar with Voyant, what makes the most sense for each file? How many years should go in each file aka what is the "granularity?" How do you need to structure the corpus to balance the granularity of each file? IE: if one text file contains an entire year and another file contains just one month, how will that affect your graph?

Upload your corpus to Voyant. To add a multiple files, find the Documents tab in the lower left corner. Press the Modify button, then Add, then Upload, to add more text files to Voyant. Make sure your files are named in a way so that they will be easy to distinguish from one another.

Try out the various visualizations in Voyant. Which work best for a comparison between these two corpora? What can you learn about how these two publications cover the same topics? 

**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* Embed 3 visualizations (either images or iframes). Your visualizations should be comparing the RTP to the Alumni magazine. Don't forget to title/caption them! 
* Write 300-400 words that addresses the following:
	* Which visualization styles work best for a comparison between these two corpora?
	* What can you learn about how these two publications cover the same topics?
	* What potential research questions could you form based on this corpus? 
	* How might you use text analysis methods in your own project?
