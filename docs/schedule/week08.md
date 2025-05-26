# Week 8 - Method 2: Mapping

*We use maps all the time, whether we're finding our way in a new city or grabbing a bite to eat. But how do maps work? How do they tell stories? We’ll start by making maps by hand then move into data-driven maps.*

## Prep for Tuesday:
* [What is the Spatial Turn?](https://spatial.scholarslab.org/spatial-turn/what-is-the-spatial-turn/)
* [When Maps Lie](https://www.bloomberg.com/news/articles/2015-06-25/how-to-avoid-being-fooled-by-bad-maps)


## Tuesday, October 29
* icebreaker: 
* [DH tools](https://github.com/dh-tech/awesome-digital-humanities) & [Storyline](https://storyline.knightlab.com/)
* Project chat. Before we start, let's do a little free writing. Take out a piece of paper and address the following: 
    * How am I feeling about my project?
    * What research do I need to do before writing my proposal?
    * What analysis and visualization methods am I interested in? (data viz, mapping, text analysis, etc)
    * What questions do I have for Prof. Brooks?
    * What are my immediate next steps?
* Activity 9.1: To start thinking spatially, let's create a map from scratch.
	* Gather some blank paper and your favorite writing/drawing/coloring instruments.
    * Without consulting any existing maps, draw a map of campus.
    * In a small group, we'll compare our maps with each other. How are your maps similar or different? What choices did you make? How are your choices informed by your hobbies, extra-curriculars, personality, abilities, etc? What was challenging? What makes our campus hard/easy to map?
    * Now, let's look at the existing [campus map](http://campusmap.wlu.edu) as well as [images from the firm](https://wlu.app.box.com/file/1060929370759) redesigning some of our spaces on campus. How did they approach our campus? What did they privilege or ignore? Does this depiction of space match your own perceptions?
    * Finally, let's try out making a data-driven map of campus. How would you go about doing that? 
* Activity 9.2: Let's continue building on our [Coeducation Report data set](https://wlu.app.box.com/file/1667760246410) so we can use it to try out some mapping tools in the next activity. Our data set needs coordinates, not just location names, for it to be easily to process by the mapping tools. Before I tell you exactly how to add coordinates, spend some time on Google. What services are out there for converting location names to coordinates? How do they work? What formats do they accept or produce? Remember, while it might be possible to convert each location one at a time, this would not be practical if our data set was any bigger. Let's look for some more automated solutions. *Treat this as homework for Thursday if we don't finish on Tuesday.*


## Prep for Thursday:
* [Working with Spatial Data](https://lincolnmullen.com/projects/spatial-workshop/spatial-data.html)
* [ICE is Everywhere: Using Library Science to Map the Separation Crisis](https://www.wired.com/story/ice-is-everywhere-using-library-science-to-map-child-separation/) and look over [Torn Apart](http://xpmethod.columbia.edu/torn-apart/volume/2/index)
* Look through the [Persuasive Cartography](https://persuasivemaps.library.cornell.edu/) collection
* Check out [Maps That Changed Our World](https://www.loc.gov/ghe/cascade/index.html?appid=ddf9824ff56b4fb6a0f3e11515716738&loclr=blogmap&bookmark=150%20AD) and [Land and Legacy](http://landandlegacy.scholarslab.org/) for examples of a digital essays. 	
* [You Can't Shop Your Way Out of a Monopoly](https://pluralistic.net/2024/03/05/the-map-is-not-the-territory/) - Scroll down a bit to get to the meat of this post. This is a great example of the type of investigation that your digital essay could conduct.
* Project Proposal Draft is coming up
    * See [assignment description](../../assignments/#proposal). You should plan to write a complete draft as possible (250 words at least). You can ask a lot of questions, but you need to put in the time to really figure out what you're doing! We'll have individual consultations on Tuesday of Week 9 to chat about your project and get you ready to submit your final proposal. 



## Thursday, October 31 (Halloween!)

* icebreaker
* Project update > don't forget to [sign up for a meeting time](https://wlu.app.box.com/notes/1681724486018)! We will **not** meet as a class on Tuesday. 
* groups:
    * table 1: Cece, Sydney, Sahil 
    * table 2: Hadley, Graham, Greg, Fran
    * table 3: Evan, Ha, Antonio
    * table 4: Abbie, Clifton, Harris
* readings discussion
    * How do maps lie? Find your favorite example from the readings from Tuesday/today and share with the table. 
    * How do maps work? Each person should share 1 technical detail they learned about how maps work. 
* Activity 8.3: How do we find coordinates? [Geocode extension](https://workspace.google.com/marketplace/app/geocode_by_awesome_table/904124517349)
* Activity 8.4: Let's make a map together.
    * Make sure you have a copy of the data on your computer (with coordinates) or in Google Drive. 
    * Visit [Google My Maps](https://www.google.com/mymaps) and be sure you're logged in.
    * Click Create New Map. 
    * Under the text `Untitled Layer`, click `Import` to select our data.
    * Be sure to select which fields should constitute the addresses or coordinates. Google's pretty smart about this, but double check!
    * Select which field should be the title.
    * Use the paintbrush icon to style the pins by a certain field.
    * What else can you do? What can't you do? Does this answer our research question?
* Activity 8.5: Mapping tools! There are a lot of options for tools that will create maps. In this activity, we'll divide into groups and test out a platform or two. We'll use the Coeducation Report as the data source for our map.
    * Platforms:
        * [Palladio](http://hdlab.stanford.edu/palladio/) - you might need a [tutorial](http://hdlab.stanford.edu/doc/scenario-simple-map.pdf)
        * [ArcGIS Online](https://www.arcgis.com/home/index.html) - Note that you can create a [free public account](https://www.arcgis.com/sharing/rest/oauth2/signup?client_id=arcgisonline&redirect_uri=http://www.arcgis.com&response_type=token) or use the [StoryMaps](https://storymaps.com/) feature. We have an institutional license if you want to use ArcGIS longer term.
        * [DataWrapper](https://www.datawrapper.de/maps) (tutorial [here](https://handsondataviz.org/symbolmap-datawrapper.html))
        * [Tableau Public](https://public.tableau.com/app/discover)
    * In your groups, answer the following questions. Record your answers in a [Boxnote in this folder](https://wlu.app.box.com/folder/291427710663) so that other students can consult the information.
        * Who created this tool? Is it open source? Is it free?
        * How do I use it? Browser or download? OS preference?
        * How do I add data? What formats does it accept?
        * How do I add layers?
        * How do I add shapes or pins?
        * Can I add a historical map? How?
        * Where is the basemap from? (Google, OpenStreetMap, etc.) Can I change it?
        * What type of mapping project would suit this tool?
        * Can you find the documentation? Other tutorials?
        * Using the Coeducation Report data, create a map. You may need to alter the data to fit the requirements of the mapping tool.


## Week 8 Assignments - Due Tuesday at 12pm

### Blog post #8 

There are a lot of ways to use maps in research and scholarship! For this blog post, select a project from [this list of spatial projects](https://reviewsindh.pubpub.org/spatial-spatiotemporal-analysis) from the site [Reviews in Digital Humanities](https://reviewsindh.pubpub.org/review-process). Try to pick that has a web map, not just a timeline. In your write-up, try to concentrate on the ways the author uses the map to answer research questions (or fails to). Another angle: how does the map enable you to answer your own research questions? 

**Finally, and this is important:** try to avoid reading the review of the project until after you've looked at it yourself. Write your notes, then come back to the full review. What did they include that you overlooked? What did you notice that the review didn't touch on? 


**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* 300-500 words. 
* Free from grammatical errors, typos. 
* Credit and link out to sources when appropriate. I won't require that you use a certain citation style, but you should be in the habit of crediting sources and using in-text links. If you feel better about using a formal citation style, go for it! 
* Address the following:
    * Who created this project? What is their institutional home and who made up their team? (No need to list every name, just summarize the types of people involved). 
    * What is the map? Is it modern or historical? What is the source of the data? Is it something you can access and download yourself?
    * What are their research questions? Can you find them easily? If not, what can you surmise are the questions? 
    * What type of spatial analysis is being done? What does the map enable you to do to? 
    * What software is being used to present the map? How can you tell? 
    * How do you feel about the design of the website? What are its affordances? Are the data visualizations well-done? 
    * Finally, compare and contrast your review to the one in Reviews in DH. Where did you overlap or differ? 


### Activity log #8

Select a second mapping platform to explore (not the one you looked at in class). In 150-300 words, answer the same questions from our in-class activity, then provide additional commentary on the differences between this platform and the one you looked at in class. How do the affordances differ? Use the Coeducation Report data set to create a map, then embed it into your post. 

**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* 150-300 words that 1) answer the questions from our in-class activity and 2) comments on the differences between this platform and the one you looked at in class. 
* Embed the map you created in your post. In most cases, this should involve an `iframe` code, not just a screenshot.
* Free from grammatical errors, typos. 
* Credit and link out to sources when appropriate. I won't require that you use a certain citation style, but you should be in the habit of crediting sources and using in-text links. If you feel better about using a formal citation style, go for it! 
