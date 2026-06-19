
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
- [Thursday, Day 2](Thursday,%20Day%202.md)

## Friday, day 3
- 09:06 Walk to the venue, running a bit late🫩 
- Still making it in time for Imbal's talk about all the new things in C++26❤️
https://slides.com/d/3xvcfGk/live

- reflection
- define_aggragate and the lift-operator (unibrow or catsears operator)
- contracts
- not in C++26 : contracts for virtual functions 
- executions, portable, gpu executions
- std::simd
- std::linalg matrix multiplication, some already possible with std::mdspan from C++23
- placeholder _ building block for template matching
## Generating Language Bindings using C++ Reflection

- Callum Piper talks about implementing python bindings using C+26 reflection
- consteval function templates look really useful
- Bindings to javascript, python, or rust will become trivial to generate with a library 
- you dont need expansion statement (template for) inside consteval functions  because everything must happen at compile time, so normal for() works. 

Walk with Sandor DARGO during lunch into the city center.
## Software and Safety

- Anthony Williams, 
- Safety critical devices: when someone can get hurt, cars, airplane, pacemakers.
- IEC 61508 industry standard 
- ISO 26262 is based on it for automotive software
-  testing, contracts , if a contract is violated, it is a bug.
- CodeQL ?
- writing the same algorithm simpler or from a non-production library is valuable for testing
## Information

- ⚜️ Hey ! I'm Jan Wilmans, I am at ACCU on Sea 2026 this week and I am the author of this Live Blog.
- I will post updates during the week about whats happening, talks that stand out to me and a collection of more or less random things. Come back for regular updates if you are interested 😋.
