# cop4656group3

So to summarize, I made some activity/fragment skeletons so we could start working


BUT BOY HOWDY, did it take a while to get git working.  TLDR, the git integration in AndroidStudio is super confusing, 
I have no idea how it works.
I spent like an hour on it before giving up entirely.

So instead I manually pushed the java and res folders along with the androidmanifest.xml, since that's easier.

to import this 'project' into androidstudio:
  
  * create new project
  
  * manually download the uploaded files and put them into the cop4656group3/app/src/main folder
  
  * clean/rebuild project
  
  
This *should* allow you to relatively easily import the project.

*****************
STATUS OF PROJECT
*****************

MainActivity:
  contains frame layout 'main_container', defaults to LoginFragment
  
PlayActivity:
  contains frame layout 'play_container", defaults to PlayFragment
  
******
TO DO
******

* Add login with google etc to LoginFragment

* pair logged-in users together in a lobby

* 'confirm' selected throw when phone is shaken when on 'PlayFragment'

etc etc

basically:
https://cdn-images-1.medium.com/max/1121/1*ozIXKg02Vo4Quss9Fq2DBw.png
