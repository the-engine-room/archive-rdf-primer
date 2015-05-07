---
layout: page
title: "Working with existing data"
category: getting-data
date: 0000-04-03 13:20:10
---

Even if your project is not the one that actually collects and creates new data, there are a number of important issues to consider in terms of dealing with data responsibly. Once you have identified appropriate data sets that will support your project activities, there are **three primary areas of responsibility** to consider:

1. How the data is evaluated for use
2. How it is managed
3. How it is presented

##Evaluating Existing Data

###Understanding the context

While working with existing data, it is important to remember that data was collected by someone else for specific purposes and to address certain needs, which probably don't match yours. This can lead to **biases and gaps**: since the producers of this data already had an understanding of what they wanted and how they wanted it formatted and distributed, they may not have explicitly included information about the context in which it was produced. Unless you're lucky, neither will they highlight steps in the data cycle that were problematic. It is important to try and gain some insight and understanding of the context of the data before using it, through considering the following questions. You might not be able to answer all of them to the extent that you would like, but taking the time to work out which ones are essentials, and talking through the others with your team, is important.

* Is there enough **contextual information** documented by the originator of the data for you to be able to judge its usability? ie. do you know why it was collected, when, with whom, under which circumstances.
* Who **published**/licensed the data? Are they the same actor that collected the data? How much control did they have over the data collection process?
* Who **funded** the process? If the funder is known for pushing a particular agenda, bear this in mind when interpreting the data.
* What **biases** might the data hold? It may be useful to think of gender, geographic area, ethnicity, age, income level, internet access, at risk populations, etc
* What **methods** were used to collect the data? Where they appropriate? Are the limitations of those methods appropriately referenced in the way the data is presented?
* Are there any **social factors** that should be taken into account when interpreting the data?
* Is the data **inclusive**? Think of issues like gender, region, etc...
* Was **active engagement** ensured for the data subjects in the project design and data collection process? Was there an informed consent process? Was the data validated by data subjects?

##Managing Existing Data

Data should be usable as well as useful. Data will need to be machine readable for most types of analysis. Some datasets will not be in analysable formats, however, and would need to be transformed to be usable. This raises questions of intellectual property (am I allowed to modify the dataset?) More importantly, it introduces a transformative process (moving data from one format to another) that needs to be planned and executed carefully, so as not to lose information or inadvertently manipulate the data. Make sure to keep versions of the data, and clearly document your steps so that if you need to you can go back a step and see where you started from.

Some considerations for the licensing regimes and legal obligations governing existing data are:

* Will re-use or re-publication of the data violate any copyrights or other rights holders?
* How should these rights be considered in light of the responsible data challenges identified in the project risk assessment and in light of the project objectives?
* Do the licenses or permissions on the data limit the formats in which the data can be manipulated and reproduced?
* Does use of the data violate any terms of service?

###Who is hidden in the data?

All data reflects on people. Even when it is de-identified, anonymized or aggregated so that individuals are not immediately apparent, the possibility to re-identify individuals is always there, especially when combining that data with complementary sources of information. This is a phenomenon called the Mosaic effect: http://e-pluribusunum.com/2013/05/20/open-data-mosaic-effect/.

>CASE STUDY: “I know what you watched last summer”

>In 2006, the movie streaming company Netflix published 10 million movie rankings by 500,000 of its customers with the aim of developing a better way of ranking the movies that it recommends. The data was supposed to be anonymised by replacing customer names with random numbers and removing personally identifiable information.
However, researchers cross-referenced the Netflix Data with the public information available on the Internet Movie Database website – where users publicly enter movie rankings under their own names. By comparing the two datasets for a small sample of users, it thus became possible to de-anonymise many of the people and understand their movie choices.
Reference:
“Why 'Anonymous' Data Sometimes Isn't”: http://archive.wired.com/politics/security/commentary/securitymatters/2007/12/securitymatters_1213

Even without identifying individuals, however, data about "things" or events can reflect the activities and habits of people and groups when combined with the right contextual knowlege. A dataset displaying water access points can, for example be used to infer information about population size, consumption habits and socio-economic status that could support discriminatory policies or exacerbate social tensions.

It's worth spending some time trying to identify types of people reflected by data, even when they are not readily apparent.  Some areas to think about could include:

* What does this data say about individuals? Who could be left out?
* How could this data be combined with other datasets to provide more information?
* Could this data be used to reveal any sensitive information about people or groups?

This exercise could be organized as a brainstorming exercise with the project teams, to try and work out as much as possible about the people behind a found data set, and then to use those intuitions to consider relevant responsibilities when using that data.

>Collecting anonymised metadata on mobility of groups of persons on the basis of mobile phones may seem rather innocuous and certainly has helped making humanitarian aid more efficient in times of crises. However, depending on the context, this kind of information can have damaging effects on data subjects. As researcher Linnet Taylor puts it in her study of data science challenge involving African mobile data:
"(...) human mobility is becoming legible in new, more detailed ways (...) this carries with it the dual risk of rendering certain groups invisible and of misinterpreting what is visible. Thus this emerging ability to track movement in real time offers both the possibility of improved responses to conflict and forced migration, but also unprecedented power to surveil and control unwanted population movement."
Source:
https://www.academia.edu/7502204/No_place_to_hide_The_ethics_and_analytics_of_tracking_mobility_using_mobile_phone_data

##Presenting existing Data

When presenting existing data, it is critical to include information about the data's provenance and the context in which it was produced. This includes all of the information uncovered when evaluating and managing the data, but it also implies being transparent about what is not known about the data. Being explicit about the data's contextual unknowns is essential for enabling others to manage your project's data responsibly.

An easy way of thinking through the contextual information that might need to be presented is via the questions listed above, underneath 'Understanding the Context". You might want to present the answers to some of these questions together with your analysis of the data.

##Further Resources:

Organizations that may be able to help you further on issues you may encounter:

Geeks without Bounds - http://gwob.org
Datakind - http://www.datakind.org
