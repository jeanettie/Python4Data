# Python4Data

To Run the code:

You will need to install Anaconda. To run the notebook, Download/Clone the repository. In the command line from the folder Python4Data launch the jupyter notebook by entering:

jupyter notebook

Once the notebook opens in the browser, open the file InjectionWells.ipynb. A new tab should open with the jupyter notebook. Feel free to 
browse the code and notes but to run the entire notebook: select Run All from the Cell dropdown.  The bokeh visualization will open
in a new tab and at the bottom of the file. If you run all cells more than one time, you will need to uncomment out two of my drop table commands to drop tables because the tables will have already been created and will throw errors. 

The Data: 

I found this dataset on Kaggle. The first set is from the Oklahoma Corporation Commission and holds all the "active" saltwater 
injection wells in Oklahoma and is current as of September 2017. The information ploted is the yearly count of approved new active saltwater injection wells from the begining of the dataset in 1936 to September 2017. So the sum of each year's plotted count is all the acitve saltwater injection wells. Total active injection wells in Oklahoma as of September 2017 is 11,125.

The second set is from the Untied States Geological Society and lists all seismic activity in the  Oklahoma region since 1977 ending in September 2016. It does include seismic activity from the surrounding states. I took only Oklahoma earthquakes from this data. I chose to use all magnitude quakes not just a set magnitude and up so there is no minimum magnitude. I did include 2016 in the visualization but want to note that the data ended in September of 2016 so it is not complete. I ended the x axis at 2016 since it was the last year of complete data for the active injection well dataset as well. 

Analysis:  

From the data, I believe there is a strong likely hood that the increase in injection wells and fracking is definitely 
related to the increase in earthquakes in the state of Oklahoma.  While the actual fracking isn't supposed to induce large magnitude earthquakes, the wastewater byproducts being injected into these deep wells is thought to. It seems that an individual anaylsis of each quake would better determine whether it's the fracking or the wastewater by product disposal wells from the fracking that is the culprit 
for Oklahoma's recent rise in earthquakes.  However, unless it's magnitude is over 3.0 or it's a significant quake above a 5.0 it seems
there is little to no interest, information, and mapping done to determine the specific fracking induced cause. Until recently, this data hasn't been openly available. 

The graph shows the start of  a substantial rise in earthquakes after 2008 with a slight down trend in 2011 before skyrocketing after 2012. After 2007, the amount of new injection wells per year steadily increased and then doubled. During the nine year period from 2007-2015 there were 2,975 new injection wells. Three of those years, 2011-2014, accounted for half of the new injection wells during those 9 years with 1681 new wells.

('2007', 275), ('2008', 234), ('2009', 246), ('2010', 293), ('2011', 438), ('2012', 448), ('2013', 403), ('2014', 392), ('2015', 246)


