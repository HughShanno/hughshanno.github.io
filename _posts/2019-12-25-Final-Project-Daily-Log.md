---
layout: post
Title: Final Project Daily Log
---

Below is a log of my daily progress, including:

1.) What I worked on today

2.) What I learned

3.) Any road blocks or questions that I need to get answered

4.) What my goals are for tomorrow

**January 7th**
Today Ethan and I researched various methods of reading in music to a Jutyper notebook. After much trial and error and learning that many programs were out of date, we finally managed to download some installers, but as we were about to test them the fire alarm went. However, we did learn that programs exist that will read in a music file and break it down into several components, allowing us to edit it and analyze it. We will need to work on streamlining the read in process. My goal for tomorrow is to effectively read in and analyze a song, and possibly begin to analyze more components of the song.

**January 8th**
Today Ethan and I worked on importing our first piece of music and converting it into a workable format. We researched all of the various plugins that we would need in order to actually import and manipulate the files. Usually what would happen is we would import a plugin, think it was what we needed, and then realize in the subsequent error message that we needed to download another one. We installed home-brew in our computers and then used that to install more packages. The culmination of all of this installation was that we were able to read in the mp3 file of Uproar by Lil Wayne, and then convert it into a .wav file so that we could later analyze the file. Then, when we attempted to begin analyzing the file, we ran into more plugin issues, and learned that we would have to manually find the proper location for the latest plugin to go. We are currently still attempting to figure out where the plugin should go within the vast file network of anaconda. We have learned today how many different aspects of python requires plugins and that if we are going off the beaten track at all, to factor in a lot of time. Tomorrow we hope to fix our issues with the latest plugin and actually begin analyzing the song that we have.

**January 9th**
Today Ethan and I, with much help from Lauren, finally managed to get all the plugins in the right place and learn what was going wrong. Following that, we managed to get what code we had working, and managed to generate a weird sort of graph. Now, we can focus on importing more plugins to vamp and using them to analyze our song. Tomorrow, we hope to move forward in our analysis and get a good amount of data for our song, then start looking for more songs in a usable format.

**January 10th**
Today we explored more plugins for analyzing our songs that work through vamp and began playing around with several of them, including the bbc plugins, the nils plugins, and a few other plugins. So far, the plugins that we have allow to extract many different aspects of the song in quantitative data, so now we have to figure out which exact data is relevant and which plugins will get us that specific data. For example, knowing when each note happens and what note it is is helpful, but it is not data that can be analyzed easily or will make much sense when analyzed. Rather, it would be more helpful to know the most common notes and the fluctuation between notes, and how often these notes occurred and the general groupings of the timestamps. This data can likely be obtained through further manipulation of data already collected, or there may be plugins that can do this for us. Also, we learned that the computing power required to run all of this data is somewhat vast, likely beyond what our computers can handle in any reasonable time, so we are working on ways to access my PC remotely so we can run the code through that. Or we will use the google cloud. Tomorrow we aim to continue making headway and beginning to filter the useful data and plugins so that we can begin constructing a data frame.

**January 13th**
Today we continued to explore different plugins and pathways in order to analyze the data. We managed to get sonic annotator to work, which is particularly useful because it can analyze several songs at once and give us a file containing the data collected from different plugins for every song. We experimented by creating a few files for the songs that we had available, then began to create functions that could read in the files and create a data frame from the results that contained the information we wanted. We also began to explore different ways of manipulating/using the data, such as using timestamps of beats to determine how often on average beats happen and how often there are major gaps in the music, or when there are a flurry of notes and how often that occurs. We also decided to analyze the notes to see which ones were the most common and the variation between notes. Tomorrow we hope to keep building these functions in order to analyze the data and perfect all of them. Once the functions are complete and we have significant data for each song, we can try to construct a data frame. Once that is complete, we can attempt to export the files to my computer at home, which will have the power to analyze the data much quicker.

**January 15th**
Today we continued our work in creating files using the data provided by the songs and creating functions that allow us to read the files and manipulate them into usable data, then create data frames. We learned that not every plugin gives us back useful data, and not to fixate on trying to make a useless and confusing plugin work. Tomorrow we hope to keep working and creating functions to make data frames from as much useful data as possible.

**January 16th**

**January 17th**