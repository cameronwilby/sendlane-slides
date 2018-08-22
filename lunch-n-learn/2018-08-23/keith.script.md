# tba

In Vue, the data binding seems like magic because of how the directives on our element tags take care of the vanilla leg work by including event listeners, (as you saw when a predetermined event happens in response to our interaction), and updates the element based on what we've specified.

In this example we are using v-model on an input tag to update our data, which in turn updates the 'message' we are referring to within the paragraph tag. This is where the newly typed message will be displayed.

Like magic, it just works without having to set up any event listeners or targeting elements, or even specifying what element we'd like to gather information from.

This is the beauty of Vue as opposed to React or other front end frameworks you may have heard about.
It just works with the minimal amount of set up required to get an app up and running, and uses far fewer lines of code to accomplish this.
