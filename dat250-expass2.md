# Software Technology Experiment Assignment 2

In this assignement I have succesfully done some initial experimenting with JPA, set up a database using Apache Derby and studied object-relational mapping. 


Derby 10.14.2.0 was installed and tested by completing the tutorial given in the assignement:

## Derby setup

1.
![derbysetup](https://github.com/h181214/250_EXP_2/blob/master/pics/Skjermbilde%202020-09-02%20kl.%2000.54.11.png)

2.
![derbysetup](https://github.com/h181214/250_EXP_2/blob/master/pics/Skjermbilde%202020-09-02%20kl.%2001.10.20.png)

## Eclipselink:

![EclipseLink](https://github.com/h181214/250_EXP_2/blob/master/pics/Skjermbilde%202020-09-03%20kl.%2014.30.33.png)

## JUNIT

![Junit success](https://github.com/h181214/250_EXP_2/blob/master/pics/Skjermbilde%202020-09-04%20kl.%2013.44.54.png)

Note: I had an unresolved issue were if I used Junit 5, an error message conatining: <i> No test found using Junit 5 </i> , changing to Junit 4 is a temporary solution. 


## Other unresolved issues

Trying to inspect the database and table created with JPA and Eclipselink, ij was and still is unable to recognize todo as a table, even though ij sees it with the 'show' command. I tried to create a new schema and table through ij in the same database, and then it worked. But the table created with JPA is still inaccessible.

issue with ij and JPA:
![issue_pic](https://github.com/h181214/250_EXP_2/blob/master/pics/inspeksjon%20av%20db%20feil.png)
