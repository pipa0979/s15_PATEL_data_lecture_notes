# s15_PATEL_data_lecture_notes

###Lecture 1  
---
I have just created a new repository for data engineering class.  
######**Example of big data**:  
---
* Data analytics  
* Storage  
* Social networks  

######**Discussion about NO sql**:  
---
* Document
* Graphs
* Key values pairs
* Collections
* Tags
* Non-visible Metadata
* Directory hierarchies

_"Data modelling is 'wicked hard'"_-  
In a big data system, it becomes **very hard and time consuming/expensive** etc... However doable
If we write data in the wrong format, we might end up with terabyte of data in the wrong format, now we may have to to invest months of time to get it right.

One of the important questions to ask:  
* Where is the data coming from?
* Is the data clean?
If its not, trigger batch job that does the _cleaning_ and then store it again.
Twitter delivers data in json format and handing in json parsers.
The most used twitter clients is the webbrowser. Twitter uses utf -8 and not use ascii because it allows to use more characters around the world.

**Data lifecycle:**
It starts with collection:
-generatiion: data generated via sensors etcc...
* Cleanup
* Storage
* Processing/analysis
* Qwery/visulaization/act

How do we start collecting data?
* Curation: collect data
* Triage

Interation with big data:  
* Web interface (google)

######Careful design in request response cycles:  
---
###Lecture 2:
Presentation:
######Markdown languages
-------
It is a type of markup language plain text formatting. easily converted to html. Plain text-->rich text types:
* Standard markdown.
* Github flavored markdown(gfm)

####1. Types of header:
#This is H1
##This is H2
###This is H3
####This is H4
#####This is H5
######This is H6

####2. Bold:  
*This is bold*

####3. Italics: 
_This is italics_

####3. Italics: 

This is ~~strike through~~


LInks can done like this
[google](www.google.com)

code by using """ code """


table involves:
| ---- :


LIne:
---
***
___

''' code '''

--------------
Get
post
delete (be extra clautious)
put

There could be scripts within the script that allows to send request again and agiain. and a good website can do all these in a couple od secs.


In amazon, there coiuld be 100's of services each second, 
rest is a narchitecture in this an approach for building architecture based

crud operations or create and rad updateand destruct


get-> rad,
post->create a new user (create data)
put->update on a particular user id. i.e. new version of user.
delete->destroy that user

some things to do:
what databse i am gonna use?
id?
what input?
what output?
how do we handle the error?




