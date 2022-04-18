---
title: Group Activity 4 | Counting Cranberries (yep)
...

Put your answers for each problem of this activity in this [worksheet](/group4.pdf).

# Directions

This activity is designed to be done in a group, whether that's in class, at home with family, or with suite-mates, friends, or people you meet on the bus or in an airport. 

- **If you're working on this in class**, please first form a group of approximately 3 people (+/- 1 person). 

- **If you're working on this elsewhere**, find at least 1 other person (but ideally 2) to participate in this activity with you. Your partner(s) definitely don't need to have any math/cs background, but be prepared to teach some discrete math to someone! When completing your activity you may print our the worksheet above, or roughly reproduce it on your own paper. To submit, email the completed work to your instructor AND turn in the paper in class.

For this activity you will be solving a series of Thanksgiving-themed counting problems.


# Introduce Your Team/Family!

Enter all the names and computing IDs of all members of your group. 

# Introduce Your (Thanksgiving) Dinner!

Have each person in your group share their two favorite items to have at Thanksgiving dinner. If you do not celebrate Thanksgiving, then just name at least one food that you enjoy to eat with your family. Write down the set of all dishes you've named (**Problem 2**). We'll refer to this set as $D$ in a future problem


# Counting Meals

We'll define a "helping" to be any non-empty subset of dishes from the set $D$. How many different helpings are there for you set $D$? (**Problem 3**)


# More Counting Problems

**If you're in class**: Do each of the following problems together

**If you're at home**: You're welcome to work on these problems with your team/family, but if they're tired and grumpy from all the feasting, you're welcome to work on them alone.

For the remaining problems we'll be analyzing how many different Thanksgiving feasts Nate and Elizbeth could have.

Nate and Elizabeth will have the following at their Thanksgiving dinner:

- Turkey
- Mashed Potatoes
- Dressing
- Green Beans
- Corn
- Cranberry Sauce
- Sweet potato casserole
- Cornbread
- Macaroni and Cheese

The following items are gluten-free:

- Turkey
- Mashed Potatoes
- Corn
- Cranberry Sauce
- Cornbread

The following items are vegan:

- Green Beans
- Cranberry Sauce
- Sweet Potato casserole


## How Many Helpings?

Again, we'll define a "helping" to be any non-empty subset of the items listed above. For example, one helping might be {Turkey, Mashed potatoes, Corn, Cornbread}, and a different helping might be {Corn, Cornbread}. 

**Problem 4**: How many different possible helpings are there for the Professors' Thanksgiving?

**Problem 5**: How many different possible helpings are there for Elizabeth, where Elizabeth can only eat gluten-free items?

**Problem 6**: How many different possible helpings are there for someone who can only eat items that are gluten-free and vegan?

**Problem 7**: How many different possible helpings are there if no helping may have both corn and cornbread?

## Gravy Boat

In addition to all of the tasty items above, the Professors' Thanksgiving will feature a delicious gluten-free gravy (a savory sauce, thickened with flour or other starch). Gravy tastes good on most items available for this meal, but not all of them. In particular, it would be unpleasant if you covered any of these with gravy:

- Cranberry Sauce
- Sweet Potato Casserole
- Macaroni and Cheese

All remaining items would taste good with gravy on top, and so we call those "graviable".

We'll consider a "gravy-helping" to be a helping where graviable items may or may not be paired with gravy (also, a gravy-helping may not have both an item with gravy and also that same item without gravy). For example, some different valid gravy-helpings might be:

- {(Turkey, Gravy), (Mashed Potatoes, Gravy), Cranberry Sauce}
- {Turkey, (Mashed Potatoes, Gravy), Cranberry Sauce}
- {Cranberry Sauce}

**Problem 8** How many different gravy-helpings are there?


## Leftovers

On the day after Thanksgiving, Nate likes to make a sandwich with the leftover items. Importantly, unlike for a helping, the order that items are placed on a sandwich is very important. Every valid sandwich must start and end with bread, and any different sequence of ingredients in the middle would make a different sandwich. For example, all of the following would be different valid sandwiches:

- (bread, corn, turkey, mashed potatoes, bread)
- (bread, turkey, corn, mashed potatoes, bread)
- (bread, turkey, turkey, bread)
- (bread, turkey, turkey, turkey, bread)

For now (we'll change this in the next section) sandwiches may not have gravy.

**Problem 9** How many different sandwiches are there?

**Problem 10** A sandwich is really only going to be edible if you can fit it into your mouth, so maybe it's unwise to have sandwiches that have 5 or more ingredients (not counting the bread). How many edible sandwiches are there?

**Problem 11** How many sandwiches would there be if we wanted them to have exactly 5 distinct ingredients?


## Gravy on Sandwiches

A sandwich is considered "graviable" if all of its ingredients are graviable. Any graviable sandwich may additionally have gravy added (just once and it can be placed anywhere between the two pieces of bread). If we may add gravy to sandwiches, these would be different valid sandwiches with gravy:

- (bread, gravy, turkey, turkey, bread)
- (bread, turkey, gravy, turkey, bread)
- (bread, turkey, gravy, mashed potatoes, bread)

**Problem 12** How many possible graviable sandwiches are there if we must have exactly 5 distinct ingredients, where one of them must be gravy?
