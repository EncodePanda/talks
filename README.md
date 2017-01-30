# My talks

This a collection of my talks.

## JVM

### “Demystifying folklore beliefs with JVM bytecode for Scala developers.” 

_Status_: :ballot_box_with_check:

TL;DR: There’s a lot of folklore beliefs & ignorance in our industry. Let’s learn some JVM bytecode in order to demystify some of the common ones in the Scala world!

Martin Thomson, in one of him famous talks, said “There is a lot of folklore, a lot of people believe strange things in our industry. I define it as ‘The fanboi problem’. People jump on ideas, google for things and they believe it blindly”. This happens in Scala world as well. You’ve probably heard at least one of them before: “Encapsulation keeps your internal safe”, “Only concatenate Strings using StringBuilder or String interpolation”, “Use shorts instead of ints whenever it is possible”, “Scala has tail recursion optimization”, “Lambdas are light”.

Also did you ever wonder how lambdas are implemented in Scala? How by-name lazy evaluation was achieved? How traits look internally? 
 
In this talk we will learn all the necessary basics of the JVM bytecode and then apply that knowledge, to answer all the questions above. 


## Functional Programming

### “Fun never stops. Introduction to Haskell Programming language”

_Status_: :ballot_box_with_check:

What is functional programming? No assignment statements, no variables,
once given a value never change, no side-effects at all. “The functional programmer sounds rather like a mediæval monk, denying himself the pleasures of life in the hope that it will make him virtuous.”.

But there must be something to it, as there are languages which allow only this kind of approach to software design. Can something useful can really be done in this paradigm?

I will show you a language develop in the late 80s called Haskell. We will explore its syntax as well as philosophy behind its creation. Why would you want to learn Haskell? Some say it will make you a better developer, triggering ability to look at software problems with different approach. Is it true? You have to see it for yourself.


### “Having a cake and eating it too. Introduction to Typeclasses in Scala”

_Status_: :ballot_box_with_check:

Being in a Scala community, you've probably heard about type classes. Very basic concept that both commonly used among many Scala libraries and at the same time very fundamental to understand any theoretical concepts behind Functional Programming. This short talk is all about explaining what Type classes are, how to use them and how to create them, with strong emphasis on answering the question "why should I even care?". We will focus on both on prons and cons, however speaker will probably be a bit biased towards the former.
We will follow story of couple of developers, struggling with conceptual design problem. As many before them, they will eventually reinvent the wheel. The solution they will end up with, is what we call a Type class.
This is a "from zero to hero" talk. Preferable audience are people who want to:
1. understand any shapeless/scalaz/cats presentation out there (this presentation will give you ability to survive first 10 minutes of mentioned talks)
2. be enlightened that "monads are just type classes with some laws" (this is not a monad tutorial though)
3. get the "aha!" moment, realising that they've been using Type classes from time to time, without knowing it


### Make your programs Free. Eye-opener to the very essence of Functional Programming

_Status_: :ballot_box_with_check:

For me, functional programming was never about switching paradigms just to switch. It was always about sanity. Yes, sanity. The ability to finally do real engineering (to some extent). A safe space where you can reason about your code in isolation. Where modularity actually makes sense. Because software engineering is hard - whatever paradigm or approach you are going to choose for your next project, the complexity will not magically disappear. FP allows you to tackle the complexity in a divide-and-conquer manner. I believe that we live in era of "software alchemy" [(c) Martin Thomson], and functional programming is the first real step to bring science and true engineering to our industry.

Free monad is a concept that forges that idea into practical solution. It allows you to reason about your concerns in isolation and combine them together on a higher level. Programs written with Free are very comprehensible and maintainable (once you know how Free works).



### “Going bananas with recursion schemes for fixed point data types”

_Status_: :ballot_box_with_check:

In 1991 Erik Meijer, Maarten Fokkinga, and Ross Paterson published "Functional Programming with Bananas, Lenses, Envelopes and Barbed Wire." This paper is a classic one, widely recognizable in the FP community. Constructs described - known as recursion schemas - have real world applications. Strictly speaking, explicit recursion is the ‘goto’ of pure functional programming. Recursion schemas provide same level of sanity as loops did for structural programming back in the day.

Over the years a lot of the progress have been made. Papers like "Recursion schemes from comonads" by Tarmo  Uustalu, Varmo Vene & Alberto Pardo or "Unifying Structured Recursion Schemes" by Ralf Hinze, Nicolas Wu & Jeremy Gibbons - pushed the concept forward.

This talk is about generalization of a very specific recursion schema (called catamorphism) over fixed point data type. After providing introduction the concept of catamorphism, we will jump straight to fix point data types trying to solve some real-world problems.
Code examples are in Scala. Code examples use Matryoshka - which is an open sourced project design to generalize folds, unfolds, and traversals for fixed point data structures in Scala.

## "Functional Programming? It's all been done before! - The Hitchhiker's Guide to Time Travel"

_Status_:  ▒▒▒▒▒▒▒▒▒▒ 0%

Welcome to my latest invention: time-travelling machine. Please: jump in and fasten your seatbelts, as we are going for a ride. 
Where we are going, you ask? I’m going to show you origins of this Functional Programming thingy you’ve been hearing about recently so often. What’s that? No, Functional Programming isn’t a new concept. It’s been discovered and discussed decades ago. It’s still vastly unexplored domain, if you read latest papers from academia, they will blow your mind. But things you call Functional Programming, things you discover at conferences, clearly are not new.
Where exactly are we going? Oh, don’t worry, not that far. You’re going to meet some awesome guys, among few: Alonzo Church, John Backus, John Hughes, Philip Wadler. They wrote some awesome stuff. You’re going to be amazed, you have my word. 

Fasten your seatbelts. 90s, 80s and 30s … here we go!

## "Event Sourcing & Functional Programming - a pair made in heaven"

_Status_: :ballot_box_with_check:

TL;DR: Intro to core concepts of FP. Intro to core concepts of ES. Tons of fun with Scala code, while transforming OO-style ES application, to a purely FP one.

While reading blogs or attending conferences, you might have heard about Event Sourcing. But didn't you get this feeling, that while there is a lot of theory out there, it is really hard to see a hands-on example? And even if you find one, it’s always focusing on Object Oriented approach?
Greg Young once said "When we talk about Event Sourcing, current state is a left-fold of previous behaviours. Nothing new to Functional Programmers". Thus isn’t this natural to see emerging code examples of event sources systems written written functional way.

In this talk I will try to answer what Functional Programming really means (we will have to travel back in time to early 90s, 80s or even 30s!). Then I will introduce some more advanced concepts (like State monad). Then I will quickly introduce Event Sourcing: it’s origins, strengths and weaknesses. 

Armoured with that knowledge we will try to transform sample ES application (OO-style, tightly coupled with framework) to frameworkless, FP-style solution.
Talk is targeted for beginner and intermediate audience. Examples are in Scala.

## "Monads - asking the right question"

_Status_: :ballot_box_with_check:

When entering the world of functional programming, one is quickly introduced with a concept of a Monad. Concept that is for some reason really hard to grasp and comprehend. When querying the Internet for "What is a Monad?" you will most likely learn that "you do not need to know the category theory to understand monads" and that "you are not asking the right question". The first thing that came to my mind, when I was struggling with this dilemma, was "Well, what is the right question then?".
This talk is all about looking for that right question and answering it. After this talk I hope you will find yourself knowing and understanding the concept, being able to apply it in a daily programming routine.

## Apache Spark

### “Let's talk about Spark internals!”

_Status_:  ████████▒▒ 85%

This talk introduce a bit more details about Apache Spark internals. We will cover:| a) quick intro to how RDDs are implemented b) Apache Spark memory model (the one introduced in 1.6.0) c) available shuffling algorithms We will see some slides but will also go deep down into the Apache Spark code base

### “Writing your own RDD for fun and profit”

_Status_: :ballot_box_with_check:

You all know what RDD stands for, right? You have the mental model of a distributed collection. But have you ever consider writing your own RDD? During this talk we will do just that. We will start by explaining essence of how RDDs are implemented internally, following by semi-live demo (*), where we will implement few RDDs from the scratch.
After this talk you will not only be able to write your own RDD, but you will also have a deeper understanding of how Apache Spark works under the hood. 
I guarantee fun during the talk and profit during your next job interview. 

(*) by 'semi-live' author means not really code live because that almost never works, but slowly pulling small commits from the repo :)

### “Writing Spark connector for Quasar Analytics”

_Status_:  ▒▒▒▒▒▒▒▒▒▒ 0%

Quasar is the leading analytical interface to multi-structured data and the only general-purpose NoSQL analytics system in existence. This talk presents our 3 months struggle of implementing Apache Spark connector for Quasar. Talk is highly technical, targeting intermediate or advanced audience.

### "Apache Spark - staying sane in production environment"

_Status_: :ballot_box_with_check:

Are you familiar with this scenario: it’s a perfect morning, your new greenfield project (based on top of Apache Spark) runs just smoothly… and then something happens. It might be that your job drops suddenly on its initial performance or you are struggling with an exception that  ‘googled’ gave you just 3 results (2 of them in some foreign language). How to handle situations when things go wrong? This is hands-on talk, with many code examples & best practices.
We will describe basic concepts like: tasks, stages, DAG schedulers. We will focus on problems of partitioning, shuffling, GC. We will see how profiles, spark-ui and solid knowledge of the API can help you with your daily Spark challenges.  

### “Apache Spark 101”

_Status_: :ballot_box_with_check:

"Apache Spark™ is a fast and general engine for large-scale data processing." Above statement is taken from Apache Spark welcome page. It's one of those definitions that, while describing the product in one sentence and being 100 % true, tell still little to the wondering noob.

Why take interest in Apache Spark? Apache Spark promise being up to 100x faster than Hadoop MapReduce in certain scenarios. Being a super-set of mapreduce it provide comprehensible programming model (familiar to everyone who is used to functional programming) and vast ecosystem of tools. In my talk I will both try to reveal secrets of Apache Spark for the very beginners and at the same time introduce more advanced concepts. 

We will first quickly look at set of problems commonly known as BigData and how they were being addressed through the last ten years by Hadoop MapReduce. I will show you what were the challenges of those approaches and why the industry is now (after a decade) looking for a new solutions.

We will then move to Apache Spark. I will try to show you what was the main factor that drove its creators to introduce yet another large-scale processing engine. We will see how it works, what are its main advantages. We will also look briefly on its internals, focusing on the speed up improvements that led to Apache Spark fame. 

Presentation will be mix of slides and code examples.

## Papers We Love

### “Software Engineering - the genesis”

_Status_:  ▒▒▒▒▒▒▒▒▒▒ 0%

In 1968 there was a conference held by NATO on "Software Engineering". In fact that was the first time that term was ever used. The committee used the term to be a bit provocative, implying that industry should be more based on more traditional foundations (like those that are established in more mature branches of engineering). 

But what does this have to do with us. Is there anything we can learn from the speakers that held the conference almost half of the century ago? Can lessons be learned? You might be surprised how much. Curious? Join my session to learn more.



### “Day when bananas, lenses, envelopes and barbed wire opened my eyes”

_Status_:  ▒▒▒▒▒▒▒▒▒▒ 0%

This talk is a tribute to a "Functional Programming with Bananas, Lenses,
Envelopes and Barbed Wire" paper by Erik Meijer, Maarten Fokkinga and
Ross Paterson. This is a journey to roots and wonders of Functional Programming. A clear and pure essence of knowledge - so much needed by young FP  apprentices. The objective here is to familiarise audience with concepts described in this paper.

## Lightning talks

### "The Cats toolbox: a quick tour of some basic typeclasses"

_Status_: :ballot_box_with_check:

It’s happened to all of us: we ran away from some conversation or library because it kept on using those “weird” phrases. You know, like “type classes”, “semigroups”, “monoids”, “applicatives”. Yikes! They all seem so academic, so pointlessly detached from real-world problems. But then again, given how frequently we run into them in functional programming, are they REALLY irrelevant, or do they have real-world applications? Paweł will start helping us make sense of the gobbledygook and we can continue in a later session.



# My Bio:

Pawel Szulc is primarily a programmer. Always was and always will be. Experienced professionally in JVM ecosystem, currently having tons of fun with Scala and Haskell. Humble apprentice of Functional Programming. Runs a blog http://www.rabbitonweb.com

