# task2


DESCRIPTION :

Create an image with jenkins installed using dockerfile

Launching this image should start jenkins services

Create a chain of jobs and display them using build pipeline

JOB1 : Pull the github repo automatically as soon some developer push the code

JOB2 : By examining the code language (html,php) the container should start the respective language image container (i.e. if the code is of html then jenkins should start the container that support html ) . JOB3 : Test the website working or not .

JOB4 : If the website is not working then notify through sending an email to the developer .

JOB5 : This will be the extra job to monitor all the jobs and restart from where any one of the jobs failed .
