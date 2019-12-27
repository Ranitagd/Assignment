# Assignment

I have tried to put together a solution to for the "E-Voting System" and for the "Space Talker (#ST)" questions. These are some draft versions from my end and have much scope of modification if needed.
I would like to add below mentioned explanations and assumptions for my attached code:

** E-Voting System
A Spring Boot application (EVotingSystemSpringBoot-1) developed on eclipse and tested with POSTMAN.
It has primarily 5 different REST URIs in the controller "VoterController.java".
1. localhost:8080/register (POST method for registration using Voter Card Number of voter using bean Voter)
inputPayload should have objects of the Bean "Voter.java"
2. localhost:8080/districtList (GET list of Districts where election is taking place)
No request Param
3. localhost:8080/expDist (GET method to explore districts based on district name along with list of parties)
It has district name as request Param and based on the input district the reponse data is generated
4. localhost:8080/voting (POST method for submitting vote by voter)
inputPayload should have objects of the Bean "Election.java"
5. localhost:8080/ElectResults (GET method to see results based on district)
It has district name as request Param and based on the input district the reponse data is generated
All data have been statically set just for demo purpose and it can be made dynamic easily using a DBMS if required.

** Space Talker (#ST)
I have tried to design a simple standalone java program which takes Roman NUMERAL format input and converts it into hindu arabic numeral as per the formula provided in the problem statement.


I have attached the zipped formats of the code with this mail.
The E-Voting system in particular is a very rough draft and I would be glad to make modifications if needed.
