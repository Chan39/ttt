# Design 1
![alt text](images/design1.png)
* Pros
    1. Statistics was implemented as a parent class.
    2. Associations had labels.
    3. Implemented a Login class.
* Cons
    1. A lot of extra classes that felt unneeded.
    2. Utility class EWS listed attributes (state).
# Design 2
![alt text](images/design2.png)
* Pros
    1. Took the idea of creating a parent class Player that extends User.
    2. Had comments that provided additional information on certain class attributes.
* Cons
    1. Player class had implemented most of the required functionality. Functionality was not distributed among classes.
# Design 3
![alt text](images/design3.png) 
* Pros
    1. Had few classes, so understanding the system was easier.
    2. Had a single statistics class that encapsulated all information related to statistics.
* Cons
    1. The Player & WordScramble classes both maintained a copy of the same statistics class.
# Design 4
![alt text](images/design4.png)
* Pros
    1. Took extra time looking into how a player can be logged into the system from different devices ie Phone, Web Browser, and Tablet.
    2. Took a different approach and made the Statistics for the WordScramble as a Association.
    3. Implemented a Login class.
    4. 
    5. 
* Cons
    1. Certain methods weren't returning values needed to complete requirements
    2. Login functionality shouldn't be associated to the Player.
# Team Design
![alt text](images/TeamDesign.png)
* Commonality
    1. Using WordScrambleStatistics/PlayStatistics as seperate classes.
    2. PlayerStatistics is a one-to-one relationship with Player.
* Differences
    1. Used the login functionality that wasn't in the majority of the teams classes.
    2. Decided on using a status field in case User is logged in on different devices which wasn't in the majority of the teams designs.
    3. Along with the Login differences the Login Uses the ExternalWebService only and then is never associated to any other classes.
    3. Used WordStatistics as a assocation.
    4. Implemented use of enumerations which wasn't used in the majority of the designs.
    5. PlayerStatus is now a part of the Player Class.

# Summary