The programm is built with jdk 9.0.4 considering the towns A, B,C,D and E.
Download the code as zip from https://github.com/hussain534/fisa01
Extract fisa01(inside the fisa01-main) from fisa01-main.zip and copy fisa01 in ur local folder.
If fisa01 is copied in folder "test" in G drive
cd G:\test

NOTE:
TryMe is the java program that has the logic to compute the distance along a certain route, the number of different routes between two towns, and the shortest route between two towns
TestRunner is the Junit java test program for TryMe and can be used to test the inputs and all the 10 cases


G:\test>G:\Hussain\softwares\jdk-9.0.4\bin\java -jar fisa01/trainroute.jar fisa01/TryMe
G:\test>G:\Hussain\softwares\jdk-9.0.4\bin\java -jar fisa01/testcases.jar fisa01/TestRunner

NOTE:
AssignSlots is the java program to assign sessiones in tracks.
G:\test>G:\Hussain\softwares\jdk-9.0.4\bin\java -jar fisa01/AssignSlots.jar fisa01/AssignSlots

Example of execution.

G:\test>G:\Hussain\softwares\jdk-9.0.4\bin\java -jar fisa01/trainroute.jar fisa01/TryMe
*****************************************************************
Welcome to TRY-M (Customised Application based on DIJKSTRA ALGORITHM).
I have towns by NAME A, B,C,D,E.
I will help you to compute the answers for the following conditions:
The distance of the route A-B-C
The distance of the route A-D.
The distance of the route A-D-C.
The distance of the route A-E-B-C-D.
The distance of the route A-E-D.
The number of trips starting at C and ending at C with a maximum of 3 stops.
The number of trips starting at A and ending at C with exactly 4 stops.
The length of the shortest route (in terms of distance to travel) from A to C.
The length of the shortest route (in terms of distance to travel) from B to B.
The number of different routes from C to C with a distance of less than 30.
*****************************************************************
Enter 1, if is allowed visiting of Cities more than once. Else enter 0:1
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:AB5
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:BC4
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:CD8
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:DC8
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:DC8
Input value do not met the req :Duplicate data for DC8.
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:DE6
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:AD5
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:CE2
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:EB3
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:AE7
Input OK
Between List of towns A-E, Enter First Route With Distance(Ex:AD9) OR enter 0 to complete the input:0
End of input entry.
################################################################### START OF EVALUATION OF 10 CONDITIONS
Is allowed visiting of Cities more than once?true
Input data[0]:AB5
Input data[1]:BC4
Input data[2]:CD8
Input data[3]:DC8
Input data[4]:DE6
Input data[5]:AD5
Input data[6]:CE2
Input data[7]:EB3
Input data[8]:AE7

======= Evaluating the distance of the route ABC ======
==========>The distance of the route ABC:9

======= Evaluating the distance of the route AD ======
==========>The distance of the route AD:5

======= Evaluating the distance of the route ADC ======
==========>The distance of the route ADC:13

======= Evaluating the distance of the route AEBCD ======
==========>The distance of the route AEBCD:22

======= Evaluating the distance of the route AED ======
==========>The distance of the route AED: NO SUCH ROUTE

======= Evaluating the number of trips starting at C and ending at C with a maximum of 3 stops ======
======= Evaluating the number of trips starting at C and ending at C ======
The number of trips starting at C and ending at C:3
Trip starting at C and ending at C:CDC
Trip starting at C and ending at C:CEBC
Trip starting at C and ending at C:CDEBC
Considering route to repeated cities
==========>The number of trips starting at C and ending at C with a maximum of 3 stops:2
==========>Trip starting at C and ending at C with a maximum of 3 stops:CDC
==========>Trip starting at C and ending at C with a maximum of 3 stops:CEBC

======= Evaluating the number of trips starting at A and ending at C with exactly 4 stops ======
======= Evaluating the number of trips starting at A and ending at C ======
The number of trips starting at A and ending at C:4
Trip starting at A and ending at C:ABC
Trip starting at A and ending at C:ADC
Trip starting at A and ending at C:AEBC
Trip starting at A and ending at C:ADEBC
======= Evaluating the number of trips starting at C and ending at C ======
The number of trips starting at C and ending at C:3
Trip starting at C and ending at C:CDC
Trip starting at C and ending at C:CEBC
Trip starting at C and ending at C:CDEBC
Considering route to repeated cities
==========>The number of trips starting at A and ending at C with exactly 4 stops:3
==========>Trip starting at A and ending at C with exactly 4 stops:ADEBC
==========>Trip starting at A and ending at C with exactly 4 stops:ABCDC
==========>Trip starting at A and ending at C with exactly 4 stops:ADCDC

======= Evaluating the length of the shortest route (in terms of distance to travel) from A to C ======
======= Evaluating the number of trips starting at A and ending at C ======
The number of trips starting at A and ending at C:4
Trip starting at A and ending at C:ABC
Trip starting at A and ending at C:ADC
Trip starting at A and ending at C:AEBC
Trip starting at A and ending at C:ADEBC
======= Evaluating the distance of the route ABC ======
==========>The distance of the route ABC:9
ABC==9
======= Evaluating the distance of the route ADC ======
==========>The distance of the route ADC:13
ADC==13
======= Evaluating the distance of the route AEBC ======
==========>The distance of the route AEBC:14
AEBC==14
======= Evaluating the distance of the route ADEBC ======
==========>The distance of the route ADEBC:18
ADEBC==18
==========>The length of the shortest route (in terms of distance to travel) from A to C:9

======= Evaluating the length of the shortest route (in terms of distance to travel) from B to B ======
======= Evaluating the number of trips starting at B and ending at B ======
The number of trips starting at B and ending at B:3
Trip starting at B and ending at B:BCDCEB
Trip starting at B and ending at B:BCEB
Trip starting at B and ending at B:BCDEB
======= Evaluating the distance of the route BCDCEB ======
==========>The distance of the route BCDCEB:25
BCDCEB==25
======= Evaluating the distance of the route BCEB ======
==========>The distance of the route BCEB:9
BCEB==9
======= Evaluating the distance of the route BCDEB ======
==========>The distance of the route BCDEB:21
BCDEB==21
==========>The length of the shortest route (in terms of distance to travel) from B to B:9

======= Evaluating the number of different routes from C to C with a distance of less than 30 ======
======= Evaluating the number of trips starting at C and ending at C ======
The number of trips starting at C and ending at C:3
Trip starting at C and ending at C:CDC
Trip starting at C and ending at C:CEBC
Trip starting at C and ending at C:CDEBC
======= Evaluating the number of trips starting at C and ending at C ======
The number of trips starting at C and ending at C:3
Trip starting at C and ending at C:CDC
Trip starting at C and ending at C:CEBC
Trip starting at C and ending at C:CDEBC
======= Evaluating the distance of the route CDC ======
==========>The distance of the route CDC:16
CDC==16
======= Evaluating the distance of the route CEBC ======
==========>The distance of the route CEBC:9
CEBC==9
======= Evaluating the distance of the route CDEBC ======
==========>The distance of the route CDEBC:21
CDEBC==21
Considering route to repeated cities
======= Evaluating the distance of the route CDCDC ======
==========>The distance of the route CDCDC:32
======= Evaluating the distance of the route CDCEBC ======
==========>The distance of the route CDCEBC:25
CDCEBC==25
======= Evaluating the distance of the route CDCDEBC ======
==========>The distance of the route CDCDEBC:37
======= Evaluating the distance of the route CEBCDC ======
==========>The distance of the route CEBCDC:25
CEBCDC==25
======= Evaluating the distance of the route CEBCEBC ======
==========>The distance of the route CEBCEBC:18
CEBCEBC==18
======= Evaluating the distance of the route CEBCDEBC ======
==========>The distance of the route CEBCDEBC:30
======= Evaluating the distance of the route CDEBCDC ======
==========>The distance of the route CDEBCDC:37
======= Evaluating the distance of the route CDEBCEBC ======
==========>The distance of the route CDEBCEBC:30
======= Evaluating the distance of the route CDEBCDEBC ======
==========>The distance of the route CDEBCDEBC:42
======= Evaluating the distance of the route CDCEBCDC ======
==========>The distance of the route CDCEBCDC:41
======= Evaluating the distance of the route CDCEBCEBC ======
==========>The distance of the route CDCEBCEBC:34
======= Evaluating the distance of the route CDCEBCDEBC ======
==========>The distance of the route CDCEBCDEBC:46
======= Evaluating the distance of the route CEBCDCDC ======
==========>The distance of the route CEBCDCDC:41
======= Evaluating the distance of the route CEBCDCEBC ======
==========>The distance of the route CEBCDCEBC:34
======= Evaluating the distance of the route CEBCDCDEBC ======
==========>The distance of the route CEBCDCDEBC:46
======= Evaluating the distance of the route CEBCEBCDC ======
==========>The distance of the route CEBCEBCDC:34
======= Evaluating the distance of the route CEBCEBCEBC ======
==========>The distance of the route CEBCEBCEBC:27
CEBCEBCEBC==27
======= Evaluating the distance of the route CEBCEBCDEBC ======
==========>The distance of the route CEBCEBCDEBC:39
======= Evaluating the distance of the route CEBCEBCEBCDC ======
==========>The distance of the route CEBCEBCEBCDC:43
======= Evaluating the distance of the route CEBCEBCEBCEBC ======
==========>The distance of the route CEBCEBCEBCEBC:36
======= Evaluating the distance of the route CEBCEBCEBCDEBC ======
==========>The distance of the route CEBCEBCEBCDEBC:48
==========>The number of different routes from C to C with a distance of less than 30:7
################################################################### END OF EVALUATION OF 10 CONDITIONS
EXEC TIME:116 mseconds