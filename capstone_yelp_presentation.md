
Go West, (Gluten-Free) Young Man
========================================================
author: sdbj2063
date: November 16, 2015

## Gluten-Free Restaurants on Yelp.com Follow the United States Population Migration to the West of the Mississippi River

### Coursera / Johns Hopkins University Capstone Project
### Data Science Specialization


Why Gluten-Free Eateries? /2
========================================================
![Gluten Free:](figures/gluten-free_logo_scaled.png) Our family has been gluten-free for **eight years**. We struggle to find restaurants that understand our dietary needs. Eating out is a challenge for my spouse, who travels for work.  

![Question:](figures/icon-with-question-mark-hi_scaled.png) Could Yelp.com be a reliable resource to find GF eateries?  

![Key Performance Indicator:](figures/kpi_logo.png) Key Performance Indicator:  Does the Yelp.com data follow the U.S. population trend to migrate west? 


Background and Hypothesis / 3
========================================================

The Huffington Post reported in 2013 that more U.S. cities west of the Mississippi River than east of the River had gluten-free delivery orders or menu items.   [Gluten-Free Takeout: Which Cities Have The Most G-Free Friendly Restaurants?](http://www.huffingtonpost.com/2013/07/16/glutenfree-takeout-which-_n_3599652.html)

![Yelp.com vs River:](figures/brand_guidelines_yelp_scaled.png) Test geographic divide against the Yelp.com dataset 
* H0 : Same number of businesses east and west of the Mississippi River
* Ha : Greater number of businesses west than east of the Mississippi River  


Methodology with Plots / 4
========================================================

* Calculate the random sample size for each group using pwr.t.test()  
* Select all U.S. businesses
    + Select a random sample and split into east and west 
* Select all gluten-free U.S. restaurants  
    + Select a random sample and split into east and west 

![Reject the Null Hypothesis:](figures/pdf_report_page_graphs_cropped.png)   


Conclusion: Reject the Null Hypothesis / 5
========================================================

![More businesses:](figures/green-check-mark-hi_scaled.png) More U.S. businesses west of the Mississippi River than east  

![More GF restaurants:](figures/green-check-mark-hi_scaled.png) More GF U.S. eateries west of the Mississippi River than east

![Yelp.com is a Go:](figures/brand_guidelines_yelp_scaled.png) Yelp.com is a viable resource for finding GF restaurants!  

#### All logos belong to their respective owners.  
