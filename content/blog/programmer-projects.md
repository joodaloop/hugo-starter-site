---
title: How programmers start projects
description: excerpts borrowed from [Ben Kuhn's](https://www.benkuhn.net/caw-start/) post.
---

> But I’ve started with the hard bits or the parts I was unsure of, and tried to implement those parts first. I try not to put off anything hard or surprising to the end; I enjoy doing the hard things first. —Brad Fitzpatrick

> Most of the time, [the project] sits in the back of my mind—nothing on paper—for a period of time and I’ll concentrate on the hard parts. —Ken Thompson

> Problem solving was the same years ago. It was, identify the difficult bits, write the small prototypes, identify the areas of uncertainty, writing very small bits of code. —Joe Armstrong

>  I start with interfaces between things. What are the common methods, or the common RPCs, or the common queries. —Brad Fitzpatrick

>  I think it’s really weird that we have very few programming languages that describe the interaction between things. I keep coming back to ways of gluing things together and ways of describing protocols. We don’t have ways of describing this protocol in between things: if I send you one of them then you send me one of these. We have ways of describing packets and their types but we have very restricted ways of describing the protocols. —Joe Armstrong

> My recollection was that I did that the way I actually have done most of my programming, which is to do the data structures first. When I was young enough that my intuition would point me in the right direction—I won’t say infallibly, but close enough—that was a really good approach. —L Peter Deutsch

> As I built larger and larger systems, I found that when sitting down to write any piece of code, more and more the question I would ask myself first is, “OK, what’s the interface between this and everything around it going to look like? What gets passed in? What gets passed out? How much of a task should be on which side of an interface?” —L Peter Deutsch
> I usually write down data structures before I write down code. —Ken Thompson

> I find that getting something on the screen as soon as possible really helps focus the problem for me. It helps me decide what to work on next… When I’m just writing the first version of the program, I tend to put everything in one file. And then I start seeing structure in that file. Like there’s this block of things that are pretty similar. That’s a thousand lines now, so why don’t I move that into another file. —Jamie Zawinski

> You’ve got to be able to make progress and then improve on it. That’s all you need to be able to do in life. You’ve got to have some idea and say, “Here’s the direction to go,” and then be able to say, “Now I’ve got to refine it.” —Peter Norvig

> But in what order we do this is, first I write about what I thought about the first day I had to work on this problem. And then, the next chapter would be the thing I decided to tackle next. And I start to tackle the thing that’s most worrying to me but that I’m also ready to solve at the moment. Instead of postponing something ’til an evil day, if I’m ready to do it now, I get that out of the way. But it’s a different order—it’s neither top-down nor bottom-up. It’s psychologically, “What do I find is the thing that’s going to make me most satisfied to get done next and I’m ready to do it?” It doesn’t have too many unknowns in it. So the freedom to put the program into that human-understandable order is very important to me. —Donald Knuth

