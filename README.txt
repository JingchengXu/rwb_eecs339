URL:http://murphy.wot.eecs.northwestern.edu/~jxb687/rwb_1/rwb.pl
To log in the account with full permission please type in
name:root
password:rootroot

Team Member: JingchengXu Yuetong Zhao Siyi Wang

Instruction
Extending Query: Using Checkbox to implement the choice of cycle and function when a user owns the right to query 
opinion , there shows four checkbox including "Committees, Candidates, Individuals, Opinions" Otherwise "Committee,Candidate
Individuals" You can check any of them in any cycle.


Crowd Sourcing: We first implement the invite user , when type in a email address, the program will send a one-time used link which
could be used only once, and a user could select the permissions he would like to give to the invited person. A person with
the query-opinion permission will see the opinion option, otherwise he will not.

Aggregated View: In this part we print out the summary of comm to comm comm to cand, the color will change according to which 
party receives more money. For the individual part, if one person belongs to a certain committee, we assume his donations is the 
same as the committee's affiliation. If there are less than 20 points in a certain view, we will add 0.1 on the coordinate, to avoid
the problem of while loop which will definately use many processes, I use the "if" to judge whether to add or not. 

Extra Credit

Security: We store the password in the database with the function crypt, in that case the password can not be seen in the database

Deeper Analysis: We add the function which calculate the average ,max, minemum of the committee to candidate in the map view, and print 
them out in a form. It could help us know more about the monetary side of electioneering for national offices.(There is more information on 
the table , but the querying speed is slowed down)

Intergrating Voting Data: After recording the data on the website, we create another table which includes the informaion about the winning 
president in each cycle year, we print them out in a form combined with the monetary ,we can check the influence of money in the global view.

Note: With many expanded query the process could be very very very slow, so please be patient. 



 
