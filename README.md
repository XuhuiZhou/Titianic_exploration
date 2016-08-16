# Titanic visualization
##Summary
On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 people.This sensational tragedy shocked the world.My visualization will show you the comparison in different Pclass between life and death.Let us use data to revisit that catastrophe again.
##Design
###Initial idea
Comparison between the survivors and the dead is the core idea of this visualization.Since the Pclass is a very important thing to affect surviving or not,I use barplot to count the number of survivors and the dead in different Pclass.The column charts I used there is appropriate because they are good for comparison.I use blue and red to represent survive and death because I think these two colors can show the conflict and can be well perceived. I preprocessed the data and divided them into  four categories :children(0-17) ,male ,female,the aged(>60).And then I use them as optional buttons for my visitors to explore.I hope they could find the difference among the groups which I found it myself when I explored the data.
###Changes after the feedback
* Change the color represent death from green to red.
* Add introduction video to the page.
* Use dimplish way to create svg and solve the problems about tooltips.
* Correct grammar mistake.
* Change absolute value in scale to percentage in y scale.
* Use text to clarify something.

##Feedback
* I firstly showed this graph to my mother,since she do not know the tragedy much,she suggested me to add some background imformation.
* Forum Mentor mentioned that the tooltips are off the screen.
* A friend of mine point out that the if color represent death is changed to green would be better.
* Forum members pick up some grammar mistakes in my visualization and code.
* Reviewer suggest that change absolute value in scale to percentage in y scale.
* Reviewer suggest some clarification would be better.

##Resource
http://dimplejs.org/examples_viewer.html?id=bars_vertical_grouped_stacked
http://www.nytimes.com/interactive/2012/05/17/business/dealbook/how-the-facebook-offering-compares.html
https://discussions.udacity.com/t/what-to-do-with-websites-on-github/183390/7
http://annapawlicka.com/pretty-charts-with-dimple-js/
https://discussions.udacity.com/t/how-to-realize-count-in-dimple/183525
