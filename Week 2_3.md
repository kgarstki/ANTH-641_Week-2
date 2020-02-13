# Week 2 – Exercise 3 Jupyter Notebooks 
Some of the digital work we’ll be doing this semester will be through an open notebook, one that connects directly to your GitHub repository. 
1.	Log into your GitHub account. Go to the ODAT notebooks repository [here](https://github.com/o-date/notebooks). In the top right corner you’ll see the Fork button. Click on that. 

You should now have a repo in your account that mirrors the one from ODAT
2.	First, go to the Settings tab in the upper right side of the notebooks repository and rename it “Week 2_notebooks.”
3.	Read through the readme document that should be the default file to come up. 
4.	Follow those instructions to create your own Jupyter notebook. 
5.	When you have your mybinder link to your Jupyter notebook create a new file in your notebook GitHub repository 
6.	Name it “Last name_notebook.md”
7.	Edit the new markdown file you just created to include the new link you made in #3 ([![Binder](https://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/yourgithubusername/notebooks/master)
8.	In addition to the link you embedded in your readme file in the forked notebook repository, you can now use this to easily access your notebook in mybinder! 
## Creating an R Notebook 
R is a programming language that is open and has a very active ecosystem of researchers creating useful packages that do various things. This ecosystem is peer-reviewed. Once a package has been peer reviewed, we can install it in R with the command install.packages("name-of-the-package"). This text is taken from [ODAT 1.4](https://o-date.github.io/draft/book/open-notebook-research-scholarly-communication.html). 

1.	Return to your Jupyter notebook in mybinder. 
2.	Click on the “Welcome” notebook and read through the contents, trying out some of the features.  Note that you can use the same Markdown language you learned in previous exercises. 
3.	Return to your home Jupyter page. Create a new R notebook. 
4.	Rename the file “Last Name_Exercise3a” by clicking on the “Untitled” name at the top of the page. 
5.	In an R notebook, code blocks may be added with the + and repositioned with the up and down arrow buttons. Press Run to execute the code in that block. Markdown blocks are added the same way, but change the type of block by clicking the dropdown and selecting markdown.
6.	R comes pre-loaded with many datasets. Let’s try to visualize some right now. In the first link type in “UScitiesD” and press Run. 
 
7.	You should see a table of data distances between different US cities. This is one way to look at the data. Another way is through a graph or plot. On the next line type “plot(UScitiesD).”
 
8.	You should see a scatter plot of the distances between cities. In the next line, change it to a Markdown block using the dropdown menu on the toolbar. Write a few sentences about what patterns you see (if any!). 
9.	Next, let’s look at the data of people who survived the Titanic. In your next line, type “Titanic” Note: capitalization matters. 
10.	Then plot the data using “plot(Titanic)”.
11.	Again, create a Markdown box and give a few sentence about what patterns you see.
12.	When you’re done, go to File and seletc Download as -> Notebook 
13.	Upload this Notebook into your Week 2_notebooks GitHub repo. 
## More complex data in R
As ODAT mentions in 1.4, sometimes we want to use packages that someone has developed themselves or that you have created. The following exercise was created as part of [ODAT 1.4 exercises](https://o-date.github.io/draft/book/open-notebook-research-scholarly-communication.html). 

1.	Create a new R notebook. Title it “Last Name_Exercise3b”
2.	Right now, we would like to install a useful package by archaeologist Sebastian Heath called ‘cawd’ (“Collected Ancient World data sets for R.”). In the first cell of your new R notebook, type the following:
install.packages("devtools")
devtools::install_github("sfsheath/cawd")
install.packages("sp")

3.	Select the cell, and hit the run button.  
4.	Let’s visualize some of this data. Create a new cell. We’re going to tell R to use this new library (this new package) we installed, and we’re going to look at some data in it.
5.	Type the following into the cell:
library("sp")
library("cawd")
par(mai=c(0,0,0,0))
plot(awmc.roman.empire.200.sp)

This should plot a map of the Roman Empire’s extent in 200. 
6.	Let’s see what other data sets are in here. Type:
	data()

Any of the datasets you see that end with .sp can be plotted the same way as we did above.
7.	Play around with the data. Visualize the data (ending with .sp) in the same way as above, or look at the data as a table. Add Markdown cells and make notes about what kind of data you’re coming across. More information about the cawd see Sebastian Heath’s repo [here](https://github.com/sfsheath/cawd). Because you know how to add links to your markdown, you can also link your work to articles in JSTOR for instance, or other websites - library permalinks, data repositories, and so on.
8.	When you’re done, go to File and seletc Download as -> Notebook 
9.	Upload this Notebook into your Week 2_notebooks GitHub repo. 
 
