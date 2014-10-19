ContactiveClone
===============
Introduction

ContactiveClone is a service that provides information based on a phone number.
Just image, when you get a call from a unknown number, what should you do?
Maybe it is a harrasing call or from some guy you do not want to answer.
ContactiveClone gives you the change to get rid of this situation. In this
situation ContactiveClone will automatically provides you more information associating
to this certain phone number, like the name of the owner, address of the owner, webpages
including this phone number and its owner, etc. All the information are gathered from the
Internet, including webpages, facebook, tweeter, tumblr, etc.

Technology
In building this project, many kinds of popular technologies and software are used.
The front end part is build with php, js, css, html, bootstrap. Apache is chosen as the server.
The whole service will be deployed on Amazon EC2. We will design and write several very efficient
and accurate crawler with php to get the interesting information. In addition, we will collecting
information from facebook, tweeter, etc with the APIs they provides. With this data collected, we will
use bigdata technology like Hadoop, MapReduce, Pig, etc to deal with it. The result willl be stored
in NoSQL database as key-value pairs, here we use DynamoDB.

To Do List,
-get the developing emvironment done
    build a ec2 server, install apache, mysql, php on it, build DynamoDB, install hadoop, etc.
-build front end part
    design the front end pages and build them.(if possible, build an ios app)
-learn the api of facebook and tweeter, get familiar with the data structure facebook and tweeter
returned.
-write screwler to get information from pages.
-write MapReduce to deal with all the data collected and persist the result in DynamoDB.
-write backend code to process the quering requests from the frontend, to interact with DynamoDB,
MapReduce code, screwler.
-documentation and test.

Need to learn,
-MapReduce, python screwler, php coding knowledgy, facebook API, tweeter API, pig, Hive, DynamoDB,
Amazon EC2.
.......





