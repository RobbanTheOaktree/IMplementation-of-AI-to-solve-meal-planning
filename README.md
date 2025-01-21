# IMplementation-of-AI-to-solve-meal-planning
This is a description of a plan of mine to make an AI that can utilize deep learning and machine learning to learn about peoples ingredients at home to notify them when they most likely need to buy more and also to recommend certain recipes based on the ingredients at home.


<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

Implementation of AI to solve meal planning

Final project for the Building AI course

## Summary

With this I would want to make meal planning easier for people and provide an idea of what they already have at home. This would be great to reduce waste and also to make it easier for people to plan meals. You could also build another LLM specifically trained on food recipes to provide good food recommendations based on the users taste. This would be done using deep learning and machine learning to find patterns in food consumption.


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.

The problems this solves:
* It would make it easier for people to not waste food by giving a reminder once a certain ingredient is likely to go bad. It could also make it easier to remember what to buy at the store since machine learning and deep learning could provide an idea of what the user already has at home food-wise.
* The application could include tools to plan meals. For example, if you include a LLM (you acn actually use GPT-4 for this) you could then provide inspiration to different recipes for the user to explore making cooking a fun and tasteful experience for everyone tailored to their needs.
* 

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

The user would get text messages from the app installed that would notify him/her that he/she is most likely goin to run out of a certain key ingredient soon, like bread. The app would also get data from the store that the user purchases their food from to restock the virtual pantry. This data could then be used to provide certain recommendations of new and interesting recipes that could make it more fun and fulfilling for the user to cook. These could be based on user preferences to make sure that someone who likes italian food can be recommended that and so on. To then remove ingredients the user could for example follow a recipe in the app and click a box to confirm that she used the set amount of ingredients listed in the app and not more. The user could also scan the bar-code on a package to remove the item from the virtual pantry. This information could also be used to enhancee the machine learning algorith. Meaning that we would then have even better information on how much and how often the user throws away food to make sure that we get it right when we recommend recipes based on what the user has at home. This information could of course be used for other users as well. 

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
