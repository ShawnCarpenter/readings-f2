# Reading 14

Project idea

I think a meal planning/recipe app would be useful.

The user story is this:

I used to do all the cooking and meal planning, but recently my time has been taken up by other things, so we have a whiteboard on the fridge that the rest of the family signs up for weekdays to make dinner and what they will be making.

It would be useful to have this system automated where people could choose a day and sign up to make a meal.

There are APIs for recipe search:
http://www.recipepuppy.com/about/api/
https://developer.edamam.com/edamam-recipe-api
https://www.themealdb.com/api.php

A user could favorite recipes, or add their own to a list.
Then the user could add recipes to a calendar for the next week or month or ?? 

Google calendar has an API, maybe connecting to that could be done? Not sure how hard that would be. Maybe a stretch goal or it might be better to start with calendar integration as a goal, it seems like it would be harder to tack on later if it wasn't baked into the design from the start.

We would need a table of users and households, users would need to see the whole household's menu to avoid conflicts in picking days, but not be able to change any claimed days or meals except for their own.

Possible stretch goal: random recipe from a favorites list? 

User 1 knows they want to cook on Wednesday and they know they like to cook three different things, they could pick wednesday, click an "I'm feeling lucky" button and have a random meal picked for them.
