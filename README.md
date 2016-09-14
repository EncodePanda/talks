# My talks

This a collection of my talks.

## Functional Programming

### Make your programs Free. Eye-opener to the very essence of Functional Programming

_Status_: :ballot_box_with_check:

For me, functional programming was never about switching paradigms just to switch. It was always about sanity. Yes, sanity. The ability to finally do real engineering (to some extent). A safe space where you can reason about your code in isolation. Where modularity actually makes sense. Because software engineering is hard - whatever paradigm or approach you are going to choose for your next project, the complexity will not magically disappear. FP allows you to tackle the complexity in a divide-and-conquer manner. I believe that we live in era of "software alchemy" [(c) Martin Thomson], and functional programming is the first real step to bring science and true engineering to our industry.

Free monad is a concept that forges that idea into practical solution. It allows you to reason about your concerns in isolation and combine them together on a higher level. Programs written with Free are very comprehensible and maintainable (once you know how Free works).



### “Going bananas with recursion schemas for fixed point data types”

_Status_: :white_medium_square: █▒▒▒▒▒▒▒▒▒

In 1991 Erik Meijer, Maarten Fokkinga, and Ross Paterson published "Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire." This paper is a classic one, widely recognizable in the FP community. Constructs described - known as recursion schemas - have real world applications. Strictly speaking, explicit recursion is the ‘goto’ of pure functional programming. Recursion schemas provide same level of sanity as loops did for structural programming back in the day.

Over the years a lot of the progress have been made. Papers like "Recursion schemes from comonads" by Tarmo  Uustalu, Varmo Vene & Alberto Pardo or "Unifying Structured Recursion Schemes" by Ralf Hinze, Nicolas Wu & Jeremy Gibbons - pushed the concept forward.

This talk is about generalization of a very specific recursion schema (called catamorphism) over fixed point data type. After providing introduction the concept of catamorphism, we will jump straight to fix point data types trying to solve some real-world problems.
Code examples are in Scala. Code examples use Matryoshka - which is an open sourced project design to generalize folds, unfolds, and traversals for fixed point data structures in Scala.

## Apache Spark

### “Let's talk about Spark internals!”

_Status_: :white_medium_square: ████████▒▒

This talk introduce a bit more details about Apache Spark internals. We will cover:| a) quick intro to how RDDs are implemented b) Apache Spark memory model (the one introduced in 1.6.0) c) available shuffling algorithms We will see some slides but will also go deep down into the Apache Spark code base

### “Writing your own RDD for fun and profit”

_Status_: :ballot_box_with_check: ██████████

You all know what RDD stands for, right? You have the mental model of a distributed collection. But have you ever consider writing your own RDD? During this talk we will do just that. We will start by explaining essence of how RDDs are implemented internally, following by semi-live demo (*), where we will implement few RDDs from the scratch.
After this talk you will not only be able to write your own RDD, but you will also have a deeper understanding of how Apache Spark works under the hood. 
I guarantee fun during the talk and profit during your next job interview. 

(*) by 'semi-live' author means not really code live because that almost never works, but slowly pulling small commits from the repo :)

