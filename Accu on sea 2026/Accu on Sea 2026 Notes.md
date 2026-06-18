
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

## Thursday, day 2

- 7:05 update blog , planned time: 10 minutes, actually it took almost 40 minutes, since my editing skills on android are sub-par 😋
- 07:59 off to breakfast 🥞 ❤️

## Keynote: Walter Brown

- 09:19 Walter Brown talks about the history of programming, mentioning the Lego Turing Machine
- Whimsical animations of LISP using a Star Wars like introduction
- 09:25 Demo of programming in th 50's?
- Emphasis we should repopularize Thusly instead 'like this'.  
- An explanation of how LISP syntax works follows. 'car' means content of address register, while ''cdr' means content of data register.
- Side note: sed if from the early 70's, vi is from the late 70's.
- Walter explains the many modern constructs like lambdas, recursion and concatenation have their origin in LISP.

## Break
- Hallway track with Andrei about AI 

## Peter Muldoon: Modernizing Legacy Codebases without Stopping the World

- Talk about how to more to modern C++
- xunused
- PMD CPD
- replace array with std::array
- clang-tidy run in single step

## Lunch

Amir, Open Content: Coding with AI, let's get aligned

- Where to use AI and the current state of workflows
- model, harness, system prompt, conversation history, tool call results, previously inferred content.
- The middle of the context window is lost if the context is overloaded
- more concrete restraints work better (instead of 'Wtite clean core' ) say: write functions with maximum of 40 lines. Etc.
- ... as appropriate is interesting in prompts (as Andrei mentioned )

## What static, inline, const, constexpr Mean and When to Use Them

- Andreas Fertig talks about keywords that have different meaning in different context.
- static variabeles in inline functions are guaranteed to appears only once
- inline static variables in C++17
- in class implemented member functions are implicitly inline (so can be included/cost size in multiple translation units, the linker may deduplicate them or not.
- constexpr functions are implicitly inline.
- constexpr variables must be marked static unless you want it to be unique on the stack when recursively. If not marked static it will be initializes again for every call.
- use 'if constexpr' instead of template specialization always when you know all the cases. (so unless you want the user to be able to add specializations)
- if not consteval  {} 😋❤️
- constinit to avoid order of initialization problems? 
- what does static mean in a constexpr function??
- constexpr constructors mean the type is initialized at compile time if it can?
-  constexpr construction is required for constinit

## Laurie Kirk, runtime reflection 

- Laurie explains reflection syntax step by step
- RTTI disabling for.smaller binaries?
- Very nice talk  but I had to pay real good attention, so I could not live-blog at the same time 😂
## Lightning talks

- Arrow IPC , Arrow flight ✈️ 
- https://omniverse.ru/talks/accuonsea-2026-table/
- Kevlin Henney on time
- Hylo
- Testudo codeberg.org/chussong/testudo
- Try boost continuations, for low latency asynchronous programming, like coroutines, but stack full, lightweight and does not litter all your code with coroutine knowledge.

## Movie Night: Walter Brown

- Hand selected series of entertaining movie clips, computer programming themed. 
- Food: most people decided to enjoy the think-cell kabab 😋 Thanks Think-cell !




## Information

- ⚜️ Hey ! I'm Jan Wilmans, I am at ACCU on Sea 2026 this week and I am the author of this Live Blog.
- I will post updates during the week about whats happening, talks that stand out to me and a collection of more or less random things. Come back for regular updates if you are interested 😋.
