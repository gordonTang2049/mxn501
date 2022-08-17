###### Question on Tutorial
--------------------------------------------------------------------



--------------------------------------------------------------------
Units
    1. Event & Probability 
    2. Independence & conditional probaility
    3. Law of Total Probability and Bayes' 
    4. Combinatorics 
    5. Random Variables and distributions
    6. Specical discrete distributions
    7. Specical continous distributions
    8. Bivariate distributions
    9. Vectors and Matrics
    10. Markov Chains
    11. Simple Random Walks
    12. Poisson Process 

PST1 - 29.8.2022

###### Notes
--------------------------------------------------------------------
(W1 u W2)(W3W4 u W5) 
    Expand
W1W3W4 u W2W5 u W2W3W4 u W1W5 



###### Rules
--------------------------------------------------------------------
Intersection Rule
    Pr( A intersect B ) = Pr(A) x Pr(B)


Union Rule
    1. Pr(AuB) = Pr(A) + Pr(B) - Pr(A intersect B) (Addition rule for non-disjoint events)
    2. Pr(AuB) = Pr(A) + Pr(B) (Addition rule for disjoint events)

Another Rule
    Pr(A intersect Complement(B)) = Pr(A) - Pr(A intersect B)

De Morgan's Law

    1. Pr(Complement(A intersect B)) = 1 - Pr(A intersect B)
        = Pr(complment(A) U complment(B))

    2. Pr(Complement(A) U Complement(B)) = 1 - Pr(A U B)
        = Pr(complment(A) intersect complment(B))

###### Event
--------------------------------------------------------------------
joint Event
    More than one event (Can happen at the same time)

Disjoint Event === mutally exclusive events
    -Can never event simultaneously -> Either Event A or B
    -are typically very dependent

###### Week 1 
----------------------------------
Disjoint Event === mutally exclusive events
    -Can never event simultaneously -> Either Event A or B
    -are typically very dependent

Lecture 1
https://qut.zoom.us/rec/play/2daXwvR5jFXu4y6ERBvw5UpK5xUlf1zndcu8UyoW3jwr9dKYCUy1B9PXkE2magYG25oooiOcJ93N2CAM.8tzROSw57HTOD9Tp?continueMode=true&_x_zm_rtaid=qDNvrIJfR22125DVEtIizw.1658871528448.d774572d05fca4cf90cfd409c82ca5fc&_x_zm_rhtaid=994

AZ?h3SqC


Tutorial 1
https://qut.zoom.us/rec/play/mKTKWBdnacjYsMSL7gSQAJJfRM4Hf7JOzEFMA4tQmzOZIylB322SBvMkc3zdq6IkxJrJ-aaeaq5qCyPp.RV-qZEjtVPk0UE96?continueMode=true&_x_zm_rtaid=qDNvrIJfR22125DVEtIizw.1658871528448.d774572d05fca4cf90cfd409c82ca5fc&_x_zm_rhtaid=994

k#2%9kIb


Event & Venn Diagrams
https://blackboard.qut.edu.au/bbcswebdav/pid-10038559-dt-content-rid-58086587_1/courses/MXN501_22se2/Spotlight%201%20Events%20and%20probability%282%29.mp4


Random Variables
https://blackboard.qut.edu.au/bbcswebdav/pid-10038559-dt-content-rid-58086588_1/courses/MXN501_22se2/Spotlight%202%20random%20variables%282%29.mp4


QUT readings
https://blackboard.qut.edu.au/webapps/blackboard/content/listContent.jsp?course_id=_165131_1&content_id=_10038506_1


###### Week 2
--------------------------------------------------------------------
Lecture 2
https://blackboard.qut.edu.au/webapps/blackboard/content/contentWrapper.jsp?content_id=_10141371_1&displayName=Linked+File&navItem=content&attachment=true&course_id=_165131_1&tab_group=courses&href=https%3A%2F%2Fqut.zoom.us%2Frec%2Fshare%2F3GwpN-LMLnErobJeURzArOo7GDn7S4AdpeLF3Elm8rrRBxOp4wAQ8sW-XdGON-nh.NRKgHLwpzykJ9cLq

7dg7!jP9


Tutorial 2 
https://blackboard.qut.edu.au/webapps/blackboard/content/contentWrapper.jsp?content_id=_10141862_1&displayName=Linked+File&navItem=content&attachment=true&course_id=_165131_1&tab_group=courses&href=https%3A%2F%2Fqut.zoom.us%2Frec%2Fshare%2F_gejpHFYcecDMhRnX3Met29FfnoCmR8BLwPzYcN3y5-mu8za89LA-50Pi3fvuCaf.2GAWKoNfcdkipFgS

17!8o#2j

Condiitonal Probabability
https://blackboard.qut.edu.au/bbcswebdav/pid-10038575-dt-content-rid-58086580_1/courses/MXN501_22se2/sd1%20_3_.mp4

Independent Event
https://blackboard.qut.edu.au/bbcswebdav/pid-10038575-dt-content-rid-58086583_1/courses/MXN501_22se2/sd1%20_4_.mp4

Disjoint Event
https://blackboard.qut.edu.au/bbcswebdav/pid-10038575-dt-content-rid-58086584_1/courses/MXN501_22se2/sd1%20_5_.mp4


independent event 
    -The occurences of one event *does not* affect the offer.
    ->Two events are considered independent 
        if one event occurring doesn't affect the probability of other event occurring.

    Pr(A|B) = Pr(A)
    Pr(B|A) = Pr(B)

    Note: you must assume events are dependent, unless it has been stated as an independent event

Disjoint Event === mutally exclusive events
    -Can never event simultaneously -> Either Event A or B
    -are typically very dependent

    Pr(A|B) = 0

    -intersection
    Pr(A N B) = 0

    

pairwise independece


mutual independence



Sneak Peak - Law of Total Probability

    P(A) = Sum of Pr(A|B i)Pr(Bi)
    


###### Week 3
--------------------------------------------------------------------

Law of Total Probability Derivation

    P(E) = P(E intersect (A u B u C))
    P(E) = P(EA u EB u EC)
    P(E) = P(EA) + P(EB) + P(EC)


Lecture
https://qut.zoom.us/rec/share/DV-wvKGF6vcZ33zc6NWhwDmgLmsBQJ6tJJhU_2TUM5-ucuV5epRViviRalKFHQef.L5CkzrgLD3GexH-z

5.H..dq4

tutorial
https://qut.zoom.us/rec/share/S0dKh_2QJgkKPIduAplhcOfJ4zG2NYatruMsTW7l0XwCmMDEHx1P9YQDg8Zi6Wk.I6JpnVgSgRjG5uc_

G21Y+gsJ

Law of Total Probability
https://blackboard.qut.edu.au/bbcswebdav/pid-10038581-dt-content-rid-58086585_1/courses/MXN501_22se2/sd1%20_8_.mp4


bayes Rule
https://blackboard.qut.edu.au/bbcswebdav/pid-10038581-dt-content-rid-58086586_1/courses/MXN501_22se2/sd1%20_9_.mp4


###### Week 4
----------------------------------------------------------------------------------------------------------------------------------------
Lecture 4
https://qut.zoom.us/rec/share/X2IBEpWVVPCqUyH7p9L9wg9FyZc6w0oe_a7T7KKv3WYlAtBGhauHA45dWBgkqjoe.LT4VFaf_9m3xwklg

N9b7?kG2


Tutorial 4
https://qut.zoom.us/rec/share/L3bV1kSBRba8cTqSCVE9DbO2siV7u1dUj6Z5REMkDD0bsQWAWqizxfvWyKzvO4t1.wsPv73bCFYn631XG

3?nr@0mT


Unordered Sampling with replacement
https://www.probabilitycourse.com/videos/chapter2/video2_4.php


Counting with order
https://blackboard.qut.edu.au/bbcswebdav/pid-10038567-dt-content-rid-58086567_1/courses/MXN501_22se2/sd1%20_1_.mp4


Counting without order
https://blackboard.qut.edu.au/bbcswebdav/pid-10038567-dt-content-rid-58086575_1/courses/MXN501_22se2/sd1%20_2_.mp4
