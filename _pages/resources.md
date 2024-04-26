---
layout: page
permalink: /resources/
title: Resources
description: 
nav: true
nav_order: 6
---

<h2> About this page: </h2>


<p style="font-size: 18px;">Starting and leading a research project can be daunting, especially if this is your first time to do so. We currently live in a time where there are many different data products, skills, and methods to approach research questions (and figuring out what to do and why is a skill itself!). This page is by no means comprehensive, but it could serve as a launching/ starting point for students (or researchers interested in dipping their toes in climate science) to find data/skill training relevant to their study questions. </p>

<p style="font-size: 18px;">Below you will find a collection of resources that have provided useful over the years, including places to find data, some online handbooks for learning R, and a vague outline of how I break a new/ large project into chunks to make it less overwhelming. I'm happy to update this page - let me know if there is something great you think I should be here! </p>


<hr />

<h2>Finding Data</h2>

There are many climate data sources, all in various formats and resolutions, and they are spread out all over the internet. This page could never contain them all, but should be a good resource to start your data digging process. I have predominantly organized things by the format most of the data from the source is available in (which determines what skills needed to work with it). In addition to those below, <a href='https://www.ncei.noaa.gov/access/search/index'>NCEI</a> and <a href='https://data.gov'>Data.gov</a> are huge collections of data that you can search by key words and file types. Some important concepts and specific data products are also described by the <a href='https://climatedataguide.ucar.edu/climate-tools'>NCAR Climate Data Guide</a>. 

<p><h4> No spreadsheets or coding required: </h4></p>
<div style="height: 225px; overflow: auto; border: 3px double #707070; box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);">
   <!-- Content goes here -->
<dl>
 
<dt> <a href='  https://climatetoolbox.org/'> Climate Toolbox </a> </dt>
 <dd>- A (huge) collection of web tools for visualizing past and projected climate and hydrology of the contiguous United States. There are so many things available here... If you go to "tools" and "variable lookup" you will be given a list of options for your variable of interest and what tools it is included in. Most of the graphics the tools make are pretty decent, and each tool has a mini tutorial included to make sure you know how to use it. Most of them also give you the option to download the data as well if you want to create your own graphics/ conduct your own analysis on it. You can also just go straight to "Data download" if you want to take the data elsewhere. </dd>

<dt> <a href=' https://www.climateengine.org/'> Climate Engine </a> </dt>
 <dd>- Free to use, needs a google account, works best with google chrome. Another tool that you can use to make graphics from a variety of datasets using many different variables/ covering various spatial and temporal resolutions. Like above, you can create and download graphics from specific points or polygons (aka, states/ regions). You can access both the images and a csv of the data after creation (if you want to take the data elsewhere). This one requires some pre-understanding of the variables; not much context is given on what each is/ how they are derived. </dd>


<dt> <a href=' https://psl.noaa.gov/data/composites/day/'> Daily Composites </a> </dt>
 <dd>- Plot daily composites (averages) of the mean or anomalies (mean - total mean) of variables from the NCEP/NCAR Reanalysis and other datasets. Long term means (climatologies) are based on 1991-2020. Data is available from Jan 1948 to previous current day for most variables.</dd>

<dt> <a href='https://psl.noaa.gov/cgi-bin/data/composites/printpage.pl '> Monthly Composites </a> </dt>
 <dd>- Plot seasonal composites (averages) of the mean or anomalies (mean - total mean) of variables from the NCEP reanalysis and other datasets. NCEP data is available from Jan 1948 to Mar 2024 . Other datasets have different time ranges. Note the climatology used for the anomaly and long term mean plots is now 1991-2020 to match the new climate normal time period.</dd>

<dt> <a href=' https://weather.us/radar-us/stormtracking.html/ '> Historical Doppler Radar Maps  </a> </dt>
 <dd>- Create maps of various Doppler products (as well as some satellite imagery) for specific times in the past (you set the date/ hours/ map location). </dd>

<dt> <a href='  https://www.ncei.noaa.gov/access/billions/'> Billion Dollar Weather Events</a> </dt>
 <dd>- Create maps and histograms/ calculate trends in costly weather events (nationwide or statewide). Graphics produced can be downloaded directly, OR you can download the data used to make the graphic and use another software to make your own.). </dd>

<dt> <a href='  https://www.ncdc.noaa.gov/cag/'> NOAA Climate at a Glance</a> </dt>
 <dd>- The tool provides near real-time analysis of monthly and annual temperatures (globally, nationally, statewide, regions, and counties) and is intended for the study of climate variability and change. You can create maps, look at time series, create Haywood plots, look at rankings, etc. All data to make graphics can ALSO be downloaded for analysis in other environments. </dd>

<dt> <a href='  https://www.climate.gov/'> Climate.gov </a> </dt>
 <dd>- This resource is both educational/ informative (it has decent descriptions for some of the climate tools presented) but it also has maps and paths to various climate data available (things like teleconnection and drought indices, sea ice change, sea level rise, among many others).</dd>

<dt> <a href='  https://charts.climate.lsu.edu/mly'> Climate Charts </a> </dt>
 <dd>- You can choose a state (or climate division) and create monthly precipitation and temperature (compared to the 30-year mean) plots as well as climate trends charts of temperature and precipitation. </dd>

<dt> <a href='  https://hazards.fema.gov/nri/map'> FEMA Hazards Index </a> </dt>
 <dd>- Create maps (or download data) of risky, vulnerability, expected losses, and community resilience to various weather hazards across the US. The maps look nice, but the data used to make them can also be downloaded for use in a variety of formats.</dd>









</dl>
</div>



<p><h4> Spreadsheets required: </h4></p>

<div style="height: 225px; overflow: auto; border: 3px double #707070; box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);">
   <!-- Content goes here -->
<dl>
 <dt> <a href='https://cas.okstate.edu/department_of_geography/'>Department of Geography</a> </dt>
 <dd>- I enjoy working with undergraduates who are excited about learning the ins and outs of research.  Please reach out if you have interests in atmospheric science (climatology/ meteorology) or more general environmental science and climate interactions (especially if you are a previous student of mine!). There are a couple opportunities on campus that could fund your research activities (like the AURCA program in the College of Arts and Sciences) or you could potentially get research course credits if you are looking to get more hours for graduation.  </dd>

</dl>
</div>

<p><h4> Coding/ GIS required: </h4></p>

<div style="height: 225px; overflow: auto; border: 3px double #707070; box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);">
   <!-- Content goes here -->
<dl>
 <dt> <a href='https://cas.okstate.edu/department_of_geography/'>Department of Geography</a> </dt>
 <dd>- I enjoy working with undergraduates who are excited about learning the ins and outs of research.  Please reach out if you have interests in atmospheric science (climatology/ meteorology) or more general environmental science and climate interactions (especially if you are a previous student of mine!). There are a couple opportunities on campus that could fund your research activities (like the AURCA program in the College of Arts and Sciences) or you could potentially get research course credits if you are looking to get more hours for graduation.  </dd>

</dl>
</div>


<hr />



<h2>Coding in R</h2>


Many climate data products need something beyond spreadsheets to work with them. This often means either learning to code (R or Python, typically) or using ArcGIS. Personally, once I became comfortable coding, I never used ArcGIS anymore. Thankfully, it is easier now to learn to code than ever… there are numerous help guides online, tons of help forums, and AI can even help troubleshoot simple code (don’t always trust it, though...). Below is a basic “starter kit” for R, my preferred programming language. 


<div style="height: 225px; overflow: auto; border: 3px double #707070; box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);">
   <!-- Content goes here -->
<dl>
 <dt> <a href='https://posit.co/download/rstudio-desktop/'>R and R Studio</a> </dt>
 <dd>- The first step in working with R. This is a free and easy download. Studio is the "Environment" that you interact with R in (basically, where you will do your writing, running, and troubleshooting, etc.). There are other IDEs out there, but Studio is pretty good and very intuitive to learn and get used to.  </dd>
 <dt> <a href='https://environmentalcomputing.net/about-this-site/'>Environmental Computing</a> </dt>
 <dd>- An online textbook utilizing R for environmental data analysis. The book starts very basic/ beginner friendly and uses examples that are relevant/ could transfer to atmospheric sciences.   </dd>
 <dt> <a href='https://mgimond.github.io/Spatial/index.html'>GIS and Spatial Analysis</a> </dt>
 <dd>- Explains/ teaches how many different GIS tasks can be done in R through a series of walkthroughs and example code. </dd>
</dl>
</div>


<hr />

<h2>Starting a Research Project</h2>

Integrating ideas, thinking across disciplines, and condensing many seemingly separate studies to have some sort of holistic understanding of a field/ gaps in the literature is not easy. You must learn how to be systematically and strategically curious and to make connections across fields that there is a good chance you are very new to. Then, once you have a good idea... it turns out someone has done it already. Time to come up with something new!

Sounds easy, right?? Maybe not.. and it shouldn't be! But like most things, breaking the process down into steps can make it much better. 


<div style="height: 225px; overflow: auto; border: 3px double #707070; box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);">
   <!-- Content goes here -->
<dl>
<dd>Some steps I think are important: </dd>
<dd>1. Conduct a literature search on the general topic that interests you (use key words that cover the topic, the geography, the field, etc., and try many different combinations of AND/EITHER/OR while adding/ removing different phrases if in Scopus/ Web of Science) </dd>
<dd>2. Read, read, read... but also make sure you are keeping track of what you have read (annotating/ making notes/ etc.)
Also read stuff that is more adjacent/ less specialized (I call this the funnel down approach, start "big picture" and get more specific as you go, eventually honing in on the niche of interest)</dd>
<dd>3. Develop an annotated bibliography of the literature - this should be detailed and organized by theme</dd>
<dd>4. THINK and ANALYZE - what knowledge gaps exist within this body of work? What hypothesis could aid in filling that gap (aka, what could YOU do?)</dd>
<dd>5. Write an essay to justify (justify being a KEY word - cite ample literature here that makes what you are proposing make sense) the hypothesis you propose to test (this becomes an excellent Introduction to a proposal!)</dd>
<dd>6. Write a lengthy description of what type of data you will collect (and WHY), including from where (metadata - strengths/ weaknesses), how much (temporal period/ spatial coverage, etc.), and how you will analyze it with an emphasis on WHY the methods were chosen (this will be a great draft of your Data and Methods section of your proposal/ eventual manuscript)</dd>
<dd>7. Get the data (or create it!) and do any necessary pre-processing (be sure to document everything you do in detail for reproducability)</dd>
<dd>8. Analyze data like you said you would; if you change any plans, be sure to document them and why</dd>
<dd>9. Digest the results of analysis (do they make sense??) and put in context of previous literature (would this make sense to others/ is it consistent with what you have read?)</dd>
<dd>10. Assuming everything seems good, check to make sure no more work on this topic has been published since you started (keep your literature base up to date)</dd>
<dd>11. Prepare a manuscript draft - clean it up so it is easy to read, but accept that it may still be ugly at this point</dd>
<dd>12. Send manuscript to at least one person you trust to give the first round of constructive feedback (advisor, other professors, colleagues, peers, etc.)</dd>
<dd>13. Revise, send it to other trusted individuals</dd>
<dd>14. Revise, revise, revise (never put "_final" at the end of a doc... you are lying)</dd>
<dd>15. Submit, eventually.</dd>

<dd>Creating new knowledge is a never ending cycle. Be prepared to have your views challenged and scrutinized - this is normal. Keep it up, and with time, the whole process will become second-nature.</dd>
</dl>
</div>

