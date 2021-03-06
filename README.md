# Tails coding test

## About this task

Think of this as an open source project. How would this have to look, in order for you to be impressed with it if you were to find it on Github? Now go do that.

Try to limit the amount of time you spend on this to 90-120 minutes. However, feel free to spend more - just make sure you're happy with your submission!

_Hint_: we're looking for a high-quality submission with great application architecture, not a "just get it done"-like approach. Stay away from frameworks/boilerplates that handle everything for you - or use them only as a thin layer - so we can see how you structure applications yourself.  Remember that this test is your opportuniity to show us how you think, so be clear about how you're thinking in your code - whether that's with comments, tests, how you name things etc.

## What to do

### First

* Create a new Python-based application (any framework is fine, we prefer Flask)
* Build an API that returns stores from the `stores.json` file, based on a given search string in a performant way and unit test it, i.e. return "Newhaven" when searching for "hav" - make sure the search allows to use both city name and postcode
* Order the results by matching postcode first and then matching city names, i.e. "br" would have "Orpington" as the 1st result (as its postcoxde is "BR5 3RP"), "Bracknell" as the 2nd


### If you're applying for a backend role

* Use postcodes.io to get the latitude and longitude for each postcode and return them in an appropriate way as part of the API response
* Build the functionality that allows you to return a list of stores in any given radius of any given postcode in the UK ordered from north to south and unit test it

### If you're applying for a full stack role

* Using your favourite front-end framework (we'd prefer Vue, React or Ember though) on the user-facing side
* Build a frontend that renders a text field for the query and the list of stores that match it, following the layout in the included wireframe (we still need to add one to the repo!)
* Add suggestions to the query field as you type, with a debounce effect of 100ms and a minimum of 2 characters
* Limit the results to 3 and lazy load the rest

### Finally

* Zip your code up and upload it into Greenhouse (our recruitment system) using the link provided at the bottom of the email you received
* Tell us which test you completed (backend or full-stack)
* Tell us what you would have done differently if you'd have had more time?
* What bits did you find the toughest? What bit are you most proud of? In both cases, why?
* What's one thing we could do to improve this test?
