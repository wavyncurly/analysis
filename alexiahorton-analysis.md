---
layout: page
title: Hospitality through the eyes of the Egyptian Gazette
author: Alexia Horton
---
Introduction
The Egyptian Gazette is made up of a wide variety of information. If you were sit down and read it in one sitting, it would without a doubt be overwhelming. The week I was assigned for this class was February 19, 1906 through February 24, 1906. Uniquely, my week consisted of eight pages everyday unlike majority of the other weeks only comprised of six. The major difference noticed when briefly scanning through my week was that almost every page seven was a “Vade Mecum” page. Vade Mecum is a phrase that represents a handbook or a guide of important information. In the case of the Egyptian Gazette, the vade mecum page comprised of travel information ranging from shipping routes, to hotel advertisements, and important information regarding each location. The vade mecum pages only appear on a handful of days throughout the year, so to have it appear on five out of the six days of my week is absolutely questioning. It raised my curiosities as to what events occur that makes traveling so prominent around this time. The vade mecum pages all identical and if not, they are extremely similar, therefore observing that page would not provide me with enough information to conduct a grand serial analysis. Thus, I will be observing the Calendar of Coming Events. This portion of the Egyptian Gazette provides a list of events that will be taking place throughout the next couple months within various locations. The question I would like to pose is what events are occurring at hotels in Alexandria through the Calendar of Coming Events, and how this plays a role in travel patterns via the Vade Mecum.

Background Information
This class called for the use of Microfilm. In order to obtain the information needed to conduct and perform this serial analysis, all students were instructed to go to the library to use the microfilm machines. The machine was called ScanPro 2000; which allowed us to take scans of each page of the week we were assigned from The Egyptian Gazette. This process alone was very time consuming because the actual films images were not very clean, and precise. Therefore, we had to take smaller clips of each page; within each clip you had to crop and make edits. It was a very tedious task getting the scroll wheel to stay in the exact you needed for the clip, focusing and adjusting the brightness to the perfect setting, and the list can go on and on for a while. All of this was necessary in order to get the clearest image to make the next step in the encoding process easier. The next step for the pages that did not have advertisements, such as page threes, was to run the clipped images through Cisdem OCR Wizard, a program that allows you to convert images into text word documents. OCR alone was a huge time saver so we did not have to write out all the text but it still came with a great deal of issues. Some of which included miss reading certain letters such as “c” and “o”, mistaking blotches in the images as exponent words, changing of fonts, sizes, and text boxes. As these steps were what we did majority of this semester, it truly was a lot of work and speaking on behalf of myself I am still working on this process.

Queries
In order to conduct my XPath query, I went to the how to tab located within our course website to piece together multiple queries to help narrow down my search results. A basic element used in all of my searches was the use of //div; this tells Oxygen to only search under the divs. From there, we have numerous routes to go down; based on the fact that my serial question deals with one specific “advertisement” I decided to search using the type and element settings. My full query look as follows:
	//div[@xml:id="deg-el-coce01"]

I also had to use the following queries in order to export specific words.
//div[@xml:id="deg-el-coce01"]cell[contains(.,"Hotel")]
//div[@xml:id="deg-el-coce01"]//row[@role="label"]//cell[@cols="2"]


Procedures
After running my queries, I extracted specific words, such as hotels, theatres, club, and hall, through a markdown software called Atom. This allowed me to take mass results and key in on portions of the files I was observing to gain the data needed to make my visual aids and conduct further analysis.

Problem
This project was not very smooth sailing; I have encountered numerous issues throughout this analysis. The first of which was actually obtaining the actual functioning XPath query. It was all about trail and error to find a readable query that produced enough results to conduct an analysis. Although I did come up with one to that produced results, I was only able to get 43 files that used the proper structural tags or used the actual template that was provided for this advertisement online.

Below are the following dates in which the //div[@xml:id="deg-el-coce01"]produced results.

Surprisingly, when running a query containing a specific word, more results were produced. My results went from roughly 43 to around 76. Now, this could simply be because the word appears more than once in each file but this was not the case for all; some were completely new files meaning some files did not have the proper structural tags.

Conclusion
