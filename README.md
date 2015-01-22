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

####1. Types of header `#, ##, ###,..., ######`:
#This is H1
##This is H2
###This is H3
####This is H4
#####This is H5
######This is H6

####2. Bold `use ** infront of a word`:  
*This is bold*

####3. Italics `use _use the word here_`: 
_This is italics_

####4. Strikethrough `use strikethrough ~likethis~`:  
This is ~~strike through~~

####5. Links `use as [Name of the link](actual link)`:
[google](www.google.com)  
[Reference link to bing.com] [refer1]  
[refer1]:www.bing.com

####6. Write code ` ```Within backtick```  `
```
int i=0;
int j=100;
cout<<"Data Engineering is awesome!!!!"
```
####7. Blockquote `Use block quote like this > Some paragraph`  
>This is how we write a block quote. The block quote is essential when specifying a paragraph.
This is also essential when we need to highlight a block of paragraph.

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



-----------------------

LEcture 3

REST is an architectureal style for web services 
* invented by ROy 
* REST is an aproach to developing web services that mimics the design of the web itself
* your service provides access to a linked set of resources.
* for each resoucem you can perform operations on ot similar to the main operations of the http specification.

Rest operation:
for each resource you can typically use atlease one of the following
* HTTP method:
* POST-> create a resoiurce
* get -> read a resource
* put -> update a resource
* delete-> delete a resource

Examples(1)
GET/api/1.0/users
Retrive a list of all users  

GET/api/1.0/users/0
->Retrieve details of user 0.
POST/api/1.0/users
->create a new user.

Examples(2)
PUT/api/1.0/users/0
Update user 0  

DELETE/api/1.0/users/0
Delete user 0  
GET/ api/1.0/search?q=tattersail
Perform a search with the query tattersail

-----------
DISCUSSION (1)
* Each operation may produce a result.
*  1. With RESTful services, JSON format is king
* POST and PUT methods typically end data
* 1. Also in JSON format
* 2. MAy be in the url or in the body of the HTTP Request
*  for GET, the data may appear as query params
* 

* Other formats are possible: HTML and xml are typically
* If a request needs to be authenticated
* * the authetication data appears in the HTT headers.
* 
Discussion (2)
How do you think operations on two resources are handeled?


ISSUES:
* Security: HOw do you autheticate users?
* Identity: How are ids assigned to resources?
* Failure:How do we handle failure situations?
  1. We see how its done is json
  2. we could have used 404,500 etc
  3. most services will use a combination of both.
* Persistance: How are resources stored?
* 


###Lecture 3  
Topics:
* Workflow
1. Untracked
* Theseare not yet in the repository.
1. Initialise your repository.
2. Add existing items to the repositiory.
3. 

clone:
get clone remote_address

1. git branch
2. gtit branch new_beanch_name
3. git branch -d new_beanch
checkout:
git checkout branch_name
git checkout commit

add:
git add _file_

usuage:
git commit -m "commit message"

merge:
git merge branch_name

pull:
git poull [remote_repository

[branchname]

push:
git push [reomte repostirory]
Everything about and github
