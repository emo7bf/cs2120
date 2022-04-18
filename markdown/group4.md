---
title: Group Activity 4 | Counting Dishes
...

Put your answers for each problem of this activity in this [worksheet](/files/group4.pdf).

# Directions

This activity is designed to be done in a group, whether that's in class, at home with family, or with suite-mates, or friends. 

- **If you're working on this in class**, please first form a group of approximately 3 people (+/- 1 person). 

- **If you're working on this elsewhere**, find at least 1 other person (but ideally 2) to participate in this activity with you. Your partner(s) definitely don't need to have any math/cs background, but be prepared to teach some discrete math to someone! When completing your activity you may print our the worksheet above, or roughly reproduce it on your own paper. To submit, email the completed work to your instructor AND turn in the paper in class.

For this activity you will be solving a series of Potluck-themed counting problems.


# Introduce Your Team/Family!

Enter all the names and computing IDs of all members of your group. 

# Introduce Your Potluck Meal!

A Potluck meal usually involves each person bringing one (or more) of their favorite dishes to share. You generally never know what you're going to get - there may be 5 salads and 10 desserts and no main dishes. But usually it's enough to make a meal out of and a great way to sample new and delicious foods from other cultures.
Have each person in your group share their two favorite food items that they might bring to a Potluck meal. Write down the set of all dishes you've named (**Problem 1**). We'll refer to this set as $D$ in a future problem


# Counting Meals

We'll define a "helping" to be any non-empty subset of dishes from the set $D$. How many different helpings are there for you set $D$? (**Problem 2**)


# More Counting Problems

**If you're in class**: Do each of the following problems together

**If you're at home**: You're welcome to work on these problems with your team/family, but you're also welcome to work on them alone.

For the remaining problems we'll be analyzing how many different Potluck feasts Briana and Elizbeth could have.

Briana and Elizabeth will have the following at their Potluck meal dinner:

- Turkey
- Mashed Potatoes
- Ham
- Green Beans
- Corn
- Potato Salad
- Baked Beans
- Chicken Tenders
- Macaroni and Cheese
- Flourless Chocolate Cake

The following items are gluten-free:

- Turkey
- Mashed Potatoes
- Ham
- Corn
- Green Beans
- Potato Salad
- Flourless Chocolate Cake

The following items are vegan:

- Green Beans
- Baked Beans
- Corn


## How Many Plates?

At a Potluck, you walk down the line of dishes and scoop a helping onto your plate. We want to look at all the different ways a plate can "look" (or the different combinations we can make on a plate). We'll define a "plate" to be any non-empty subset of the items listed above. For example, one plate might be {Turkey, Mashed Potatoes, Corn, Baked Beans}, and a different helping might be {Corn, Baked Beans}. 

**Problem 3**: How many different possible plates are there for the Professors' Potluck?

**Problem 4**: How many different possible plates are there for Elizabeth, where Elizabeth can only eat gluten-free items?

**Problem 5**: How many different possible plates are there for someone who can only eat items that are gluten-free and vegan?

**Problem 6**: How many different possible plates are there if no plate may have both Mashed Potatoes and Potato Salad?

## Spice It Up!

In addition to all of the tasty items above, the Professors' Potluck will feature a spicy gluten-free hot sauce (think Frank's RedHot). Hot sauce tastes good on most items available for this meal, but not all of them. In particular, it would be unpleasant if you put hot sauce on any of these:

- Green Beans
- Potato Salad
- Flourless Chocolate Cake

All remaining items would taste good with hot sauce on top, and so we call those "sauce-able".

We'll consider a "hot sauce plate" to be a plate where sauce-able items may or may not be paired with hot sauce (also, a hot sauce plate may not have both an item with hot sauce and also that same item without hot sauce). For example, some different valid hot sauce plates might be:

- {(Turkey, Hot Sauce), (Mashed Potatoes, Hot Sauce), Baked Beans}
- {Turkey, (Mashed Potatoes, Hot Sauce), Corn}
- {Green Beans}

**Problem 7** How many different hot sauce plates are there?


## Leftovers

On the day after the PotLuck meal, Briana's husband likes to make a sandwich with the leftover items. Importantly, unlike for a plate, the order that items are placed on a sandwich is very important. Every valid sandwich must start and end with bread, and any different sequence of ingredients in the middle would make a different sandwich. For example, all of the following would be different valid sandwiches:

- (bread, Corn, Turkey, Mashed Potatoes, bread)
- (bread, Turkey, Corn, Mashed Potatoes, bread)
- (bread, Turkey, Turkey, bread)
- (bread, Turkey, Turkey, Turkey, bread)

For now (we'll change this in the next section) sandwiches may not have hot sauce.

**Problem 8** How many different sandwiches are there?

**Problem 9** A sandwich is really only going to be edible if you can fit it into your mouth, so maybe it's unwise to have sandwiches that have 5 or more ingredients (not counting the bread). How many edible sandwiches are there?

**Problem 10** How many sandwiches would there be if we wanted them to have exactly 5 distinct ingredients (including the bread as one ingredient)?


## Spicy Sandwiches

A sandwich is considered "sauce-able" if all of its ingredients are sauce-able. Any sauce-able sandwich may additionally have hot sauce added (just once and it can be placed anywhere between the two pieces of bread). If we may add hot sauce to sandwiches, these would be different valid sandwiches with hot sauce:

- (bread, Hot Sauce, Turkey, Turkey, bread)
- (bread, Turkey, hot sauce, Turkey, bread)
- (bread, Turkey, hot sauce, Mashed Potatoes, bread)

**Problem 11** How many possible sauce-able sandwiches are there if we must have exactly 5 distinct ingredients, where one of them must be hot sauce (including the bread as an ingredient)?
