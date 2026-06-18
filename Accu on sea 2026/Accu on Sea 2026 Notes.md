
# ACCU on Sea 2026 Live Blog

Join the discord server, link below 👇 

- https://accuonsea.uk/2026/schedule/index.html
- https://accuonsea.uk/discord/

[More links](../More%20links.md)
# News

- https://herbsutter.com/2026/06/13/brno-trip-report/
- [Conference stats](../Overview.md)

Blogging pages

- [Arrived! on Tuesday](Arrived!%20on%20Tuesday.md)
- [Schedule Wednesday](../Schedule%20Wednesday.md)
- [Wednesday Day 1](Wednesday.md)

Thursday, day 2



## Start of day 1

- Breakfast with Justin Link (nice to meet you Justin!)
- 8:50 off to the welcome speech 💬 
- Guy wakes us all up and entertains as he does 😋
## Andrei Alexandrescu's Keynote

- 9:30 Andrei Alexandrescu talks about **Abstraction** as the ultimate software engineering tool. Also a look at predictions from the past and a lookout into the next 20 years/months/weeks/days!? How is AI going to change the way we develop software? Are we now in a reverse centaur stance ? 

A model can teach you how to use *it*. This has no precedent in human history. 

Contracts are a specification language on top of C++, which will be good for creating and checking AI generated code.

Andrei talked about how AI might become the ultimate code optimizer once compilers get better interfaces to let agents talk to them. As an example he mentioned the overwhelming amount of information a compiler can emit using full warning and remarks flags.

## The Async graveyard, Robert Leahy

- 11:30 Robert talks about C functions in C++ wrappers leading into sleeping threads that block on synchronous operations.
- C-ARES async library introduced, explanation of separation of responsibilities of caller and continuation
- A exploration or async executions using various means follows, std::async, coroutines and senders
- I lost track of the story somewhere, because of the sheet volume of information 😂
- Take away: senders/receivers are basic building blocks for all asynchronous invocation, and if you known eventual time bounds up front , you can use them without any dynamic allocation 

## Nevin "";)" Liber

16 years doing C++ Standardization Work
A Personal Retrospective

- Nevin tells a story about the start of his career at Bell labs.
- He continues to tell the story about C++ and his contribution/involvement to the standards commissie
- It was a great story about how anyone can become involved and contribute to the standardization process

## Klaus Iglberger

Design Patterns, The Most Common Misconceptions ( 3 of N)

Klaus we know as the Design-Patterns-Guy and the creator of the now famous Klaus-initialization rule.

- Klaus talks again on Design Patterns like we are now used to from him.
- #1 Adaptor, 
- std::stack and std::queue are adaptors!
- I have to try std::pmr::vector and implement my own allocator
- Expect adaptors in any form classes, templates or free functions
#2 Decorators 
- std::pmr::vector<std::pmr::string> demo

#3 Expression Templates
- DynamicVector, demonstrate lazy operator[] functions
#4 demo of lazy ranges views
Range Adaptors might be a misnomer, they are decorators (mostly)

Lightning talks
-  Will Bucanan: We abstracted away thinking, is this ok? 
- Dietmar : deducing this
- Will sings bill rutherford: a song on stage 😂💬
- Sandor Dargo: never call now() mock it using std::function?
- Lieven de Cock verify your headers , look into BASEDIR in cmake
- Pete goodliffe: computer puzzles 
- Florian: author of the Berlin code of conduct, helps to align values also between organisers
- Dom Davis: Life, talk about Stuff , ACCU needs help.
- Keith Stock performance reviews at Microsoft, STL made std::excepted nodiscard in MSVC 
-  Cassio Neri: Dragon Lord 🔥 Floating point number do not exist 😂 Math fun.
- Chris Oldwood: coding phuns

## Dinner at the Rosemond

- The rib eye was great still 😋
- Nice dinner with Anders, Robert and more friends (I'm so bad with names I will have to add them in later)

## Back to the venue

Back at the venue to do a hallway track, Talked to Tim van Deurzen and software signal analyzer.








## Information

- ⚜️ Hey ! I'm Jan Wilmans, I am at ACCU on Sea 2026 this week and I am the author of this Live Blog.
- I will post updates during the week about whats happening, talks that stand out to me and a collection of more or less random things. Come back for regular updates if you are interested 😋.
