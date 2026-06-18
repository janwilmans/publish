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
- 