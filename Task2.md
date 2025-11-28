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

##Geometries and statistical elements##

##Coordinates##

##Guides and facets##


##References##
