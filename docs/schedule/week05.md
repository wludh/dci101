# Week 5 - Data
*Sure big data is nice, but have you ever tried handcrafted artisanal data? This week we’ll learn how data is made by creating it from scratch.*

## Read for Tuesday: 

* [Data](https://mackenziekbrooks.github.io/humanities-data/data/) - DCI 102 Coursebook
* [Defining Data for Humanities](http://journalofdigitalhumanities.org/1-1/defining-data-for-humanists-by-trevor-owens/) - Owens
*  [What Gets Counted Counts](https://data-feminism.mitpress.mit.edu/pub/h1w0nbqp/release/3) - D'Ignazio and Klein

## Tuesday, October 8
* icebreaker: do you have a collection?
* [slides](https://docs.google.com/presentation/d/1uWw_RaWDpX_NeucAcF3r7o26vQwWZUqyPs3W57BkU_w/edit?usp=sharing) + readings
* Activity 4.1 - let's make some data! 
	* Start with the [Alumni Coeducation Correspondence, May 10, 1984 (report)](https://wlu.app.box.com/file/1667743907209) from the [W&L Digital Archive](https://digitalarchive.wlu.edu/). Take some time to read through the report, making note of the content and how it is presented. How are the first few pages different than the rest?
    * Create your data model (a list of the fields you want to include and how to express those values) in a Box note for your group in [this folder](https://wlu.app.box.com/folder/288135496687). Look over all the types of information included in the report. Choose what fields you think you should include. Why are you choosing those fields? How would these fields be useful in exploring/visualizing the data? Will your data collection enable certain research questions? Is there anything you can leave out?
    * Once your model is set up, go ahead and start transcribing the data. Each team will be assigned a few pages to transcribe into [this Google spreadsheet](https://docs.google.com/spreadsheets/d/1jbP4je-Z1j-j8l9JL9i_-weOIVi6X3GUqVw32cdas7M/edit?usp=sharing). Try to avoid looking at other team's sheets. We want to be able to compare the differences at the end of this activity.
	* After we come back from the small groups, compare your data model to that of other groups and answer the following questions.
        * How are the models different?
        * What did your group include that others didn't and vice versa?
        * How do your fields change the questions you can ask the data?

* Activity 4.2
    * Let's practice making some visualizations with this data. Here's a more complete dataset: [Coeducation data](https://wlu.app.box.com/file/1667760246410). 
    * First, let's make a hand-drawn data visualization the paper/pen provided. 
    * Then we can move into making it in Excel or Google Sheets if there's time. If not, we'll cover next week!
    * Here are some instructions in **Excel**: 
        * First, we need to make a **PivotTable**. This creates a version of the data that be more easily summarized for the charts. 
        * Select all the columns in your spreadsheet.
        * Go to `Insert` then select `PivotTable`. 
        * Complete the wizard. You'll want to `add to new worksheet`. 
    * Let's make a basic bar graph that shows the breakdown of support for coeducation. 
        * First, add the `PivotChart` box to your sheet. It's in the middle of the Insert menu.
        * In the pane on the right called `PivotChart Fields`, select `opinion`. You should a count of all the opinions in a single bar. Sure okay, but not quite what we want. 
        * Drag the `opinion` field to the `Axis (Categories)` window. Now we see each category broken out on the X axis. Ta da! 
        * Can you figure out how to make this a pie chart? 
    * What about a stacked bar graph that shows both the opinion and who they wrote to? Try it first before reading the instructions.
        * Select the stacked column chart type. 
        * Add `opinion` to the `Values` box.
        * Add `opinion` to the `Axis (Categories)` box.
        * Add `addressee of letter` to the `Legend (Series)` box.
    * In **Google Sheets**:
        * Select the column(s) you want to visualize. 
        * From the menu, go to Insert > Chart. A window pops up and makes suggestions for you. Spend some time with these options!


## Thursday, October 10 - READING DAYS

* No class, get some rest! 

## Week 5 Assignments - Due Tuesday at 12pm

### Blog post #5 - data viz interrogation
Let's make sure you can think critically about data and data visualizations that are designed to persuade. This blog post focuses on the audience and argument of data and data visualizations. Go out into the wilds of the internet and find a data visualization that speaks to you. It doesn't have to be on the topic of your future project, but this might be a nice way to get started on research. Answer the following questions:

* What is this visualization trying to convey? Is it successful? Does it convince you? Why or why not? Would the piece work without the visualization?
* Does the style suit the data? How so? What other visualization styles would work?
* Who made this visualization? What is their background?
* Who is the audience and what is the context (publication, website, etc.)?
* What is source of the data of this visualization? Can you find the original data set? Try hard! Where did you look? What format is it in?
* How might this data be subject to the biases of its authors? Where are the binaries or hierarchies? 
* What else could be done with this data set? Other research questions? Other visualizations?


**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* 300-500 words.
* Be sure to link/embed the data viz of your choice.
* Free from grammatical errors, typos.
* Credit and link out to sources when appropriate. I won't require that you use a certain citation style, but you should be in the habit of crediting sources and using in-text links. If you feel better about using a formal citation style, go for it!


### Activity log #5 - new old data 

This week we went through the process of creating a data set from scratch, determining some research questions, then creating data visualizations. We also read a chapter about "What Gets Counted Counts" and the ways that bias can affect the results of any data-driven projects. For this activity, I'm going to hand you a new data set and it's your job to make sense of it. What can you determine about its creation? What are some of its issues? What research questions might it inspire? Can you create a basic data visualization? What silences or gaps are in this data set? Spend some time just browsing around before you dive into answering the questions. 

[Data set link](https://wlu.app.box.com/file/1666810984520)

[Oak Grove Cemetery website](https://sjcemetery.wlu.edu/)

[Old cemetery website in Internet Archive](https://web.archive.org/web/20210303113101/https://sjcemetery.wlu.edu/)


**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* No word count, but be thorough! You can write this as a list or with headings. 
* Answer the following:
    * Who created this data set? 
    * What does this data contain? Provide a narrative summary and the data model (list of the fields and the data type).
    * What are some issues with this data? What inconsistencies do you notice? Why might these be an issue? 
    * What research questions does this data set prompt? How might different disciplines approach this data differently? Give an example or twos.
    * What further research might you need to do to make sense of this data? What websites or sources would be useful? Give an example. 
    *  Create 1-2 data visualizations using this data set. You should definitely only use a small subset of the data. You almost certainly will have to clean up the data a little bit (give Open Refine a whirl). You can use Excel or any of the other platforms we talked about in class OR you can draw them by hand. The point is not to master the visualization software, but to start thinking in terms of what a visualization should express. Embed these visualizations on the page.

