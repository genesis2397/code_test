# code_test

Hello Good Day! First of all sorry I beat overtimed of 1 hr. Some personal errands did happened

First of all my initial impression of the code was quite similar to the methods that i'm using but what is makes apart from mine is the using of variables. The original
codebase makes a variable for every $request->all() whereas if you've noticed i do usually inject it right through the parameters of a called function, classes and repository.

Secondly was the index function at the BookingController. I noticed that it called a two function in the Booking Repo. So what my take about this is you can make it simplier
by making another function at BookingRepository and you put the conditional part of what what be the returned outcome. So it gives more cleaner look to the Controller.

Third was the series of conditioning of just only two results at distanceFeed function at Booking Controller. For me it is more efficient to use a ternary operator to
shorten things up and consume alot of lines.

Fourth was the proper indention, for me I do practice it especially on an elloquent expression and with an array of many elements. Because it gives an ease for your co-developer
to see the part on which is needed to be done.



CONS



Using ternary operator is not suitable on an expression that has many option results, it will just cause a confusion. So the best use case is to only make it if the condition has only
two outcome.

About my practice of redirecting the Model's variable, sometimes it is not accepted by many. Yes it will shorten the code but the catch is sometimes your co-devs preffered
to make a variable for it before injecting it as a parameters.

Needed to improve

I think the BookingRepository has a lot of potential to be refactored but since I don't understand most of it because it's not a live program I can't provide a concrete
solution. But what I saw was a bit of redundant functionalities I all I can was it can be reused.



Overall, I do believe that I have the skillset needed to be the part of the team and I will prove that you needed someone like me. 
