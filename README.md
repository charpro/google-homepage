##INSTRUCTION ON HOW TO CREATE REPO ON LOCAL 
MACHINE AND PUSH ON GITHUB 

#CREATED FOLDER ON THE LOCAL MACHINE (the_odin_project)
 $ touch the_odin_project

#CHANGE INTO NEW FOLDER TO SAVE ALL FILES

 $ cd the_odin_project

#CREATE A NEW REPOSITORY FOR THE PROJECT ON THE GIGHUB.COM CALL IT  google-homepage THEN MOVE THAT REPO ONTO LOCAL MACHINE USING github SSH 

 $ git clone git@github.com:(github username )/google-homepage

#cd  INTO  google-homepage  ON LOCAL MACHINE 

 $ cd google-homepage 

#CREATE A FILE AND WRITE A BRIEF INSTRUCTION OF THE PROJECCT INSTRUCTION 

 $ touch README.md 

#LOAD OR ADD EVERYTHING FROM PROJECT FOLDER ON LOCAL TO GIGHUB.COM
 $ git add . 
 $ git commit -m " your message " 

#RUN COMMAND TO PUSH THE LOCAL REPO TO GIGHUB

 $ git push origin master

#CHEDK THE STATUS AND LOG HISTORY 

 $ git status
 $ git log
 
#END OF THE PROJECT INSTRUCTION 


 