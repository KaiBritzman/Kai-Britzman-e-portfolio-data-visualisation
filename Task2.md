---
layout: page
title: The Grammer of Graphics
permalink: /Task2/
---

##What is the Grammer of Graphics?##
The grammer of graphics is a set of rules that are followed when creating a graphic in R. When you are programming in R to make a graph, you need to declare each part of the graphc in a specific order to create the graph exactly how you want it. Its like the language strucutre of a new language. For example, in english, we follow the subject - verb - object rule. This means that we first declare a subject, then the verb and object. For example, "You eat apples". "You" is the subject, "eat" is the verb and "apples" is the object. Since we followed the subject-verb-object rule, the sentence makes sense. 
This is the same idea for the grammer of graphics. The order we go in to make a graphic is R is data, aesthetics, scales and transformations, geometries and statistical elemetns, coordinates and then guides and facets. If we did this in another order like coordinates, scales and transformations then aesthetics, it wont work because we didnt follow the rules the grammer of graphics set. 
To make a graph that follows the grammer of graphics, you need a library called ggplot. This was made to follow the grammer of graphics and allows programmers to make detailed graphics. Within ggplot, you declare functions like ```aes()``` ```data()```. Each function is a part of the grammer of graphics and they need to be delcared in the order discussed above. 
##Aesthetics##
Aesthetics are an esstential part of the grammer of graphics. They are what you are going to see on the graph. Examples are the x and y coordinates and colours you will see on the graph. When coding, aesthetics are declared using: 
```
aes()
```
The code is the written within the parenthesis.
A common misconception about aesthetics is that the code within your parenthesis draws what you want onto your graph. However, they are just instructions, they dont draw anythinhg on the graph. Other components of the grammer of graphics are used for projecting the aesthetics however you want (scales and transformations, coordinates etc). 

##Scales and transformations##
Scales and transformations are an important part of the grammer of graphics. They are how we want to position and place our aesthetics. We first declare the aesthetics in ```aes()```, then we need a way to plot them in places we want them. Without this, your IDE (integrated development environment) will decide how to plot the aesthetics for you. This is generally fine for simple graphs that aim to display uncomplex data, but as your graphcs become more detailed and you wish to tell more complex stories, you will need to be able to manipulate the aesthetics yourself so the graph can tell the story you want. 
To implement this into your graph, you need to use the function
##Geometries and statistical elements##
Geometries are how we want to present the data. This can include a point, barchart, histogram, scatter and more. Choosing the right geometric is important for the story you want to tell with your graph. Different geometrics will present the data differently, so choosing the wrong one can cause the viewer to have a view you didnt want. 
Statistical elements are components like medians, counts and means. 
##Coordinates##
Coorindates in the grammer of graphics are where we position the data. In scales and transformations, we are just manipulating the aesthetics, like colour, shapes and sizes, however with coordinates, we are pin pointing where we want our data. Coordinates allow us to present data however we want, to tell the story we want to tell. Manipulating coordinates can lead to misleading graphs, however if its used correctly and ethically, we can use it to change peoples minds, without twisting the orinigal data. 
To define coordinates, we use the function
##Guides and facets##
Guides are

Facets are multiple graphs in one. Facets are used for comparisons. For example, in the iris data set in RStudio, there are two species, Sepal and Petal. They both have a length and a width. You could use a facet to show the differences between the Sepals width and height to the petals. Facets will prevent you from having to create two seprate graphs. Instead, you can do two for only one bit of code. 
There are different types of facets. Ones called grid, and the other one is
##References##
