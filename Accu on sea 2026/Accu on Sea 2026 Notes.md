
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
## KEYNOTE: Out of Our Minds: What is AI Doing To Us and For Us?

- How to organize your 💬 thoughts
- Tortoise AI scribe ?
- Should AI reduce or speed up thinking  and /or cognitive load
## Lightning talks

- francis: respect wasps, leaving their next will cause them not to come back next year.
- ubsan finds more without asan in the same build.
## Saturday Day 4

- make a check in CI that functions stay vector optimized
- turn on compiler remarks to see why vectorization doesn't happen 
- check the cores are not powermanaged during testing (failing powermanagement can be due to failing power management )
-  look into a formatting of std::byte

## Hana's Keynote
- core, language, evolution?
- constexpr implementation in clang, values are stored as APValue and can be anything 
- Pointer provenance data, pointing past the end of array and pointing 
- inplace_vector initially initializated or not? find out.
- Encourage more people to help making compilers better, compilation of clang takes ~4 minutes on modern machines.
- Hash Array Mapped Trie


💡 idea  lifetime extension for reference types? understand how that would (not) work. Probably because the reference outside the stack, but in that case its a different problem space. We could do this for anything stack allocated? 

Lieven: passing heap allocated values from compile time to runtime is not possible, for example std::string 

- most standard containers are now constexpr
- vector should be your default container unless you have a good reason to choose something else

## Jason

- safety in numbers
- look at mp-units again
-  look at ubsan minimal runtime
- std::saturating_add is called add_sat
- std::saturating_cast
- safe-comparisons break type safety

## Braden

- snitch , compile time testing
- k3tchup

## KEYNOTE: Incrementally securing your C++ using Rust

- Taylor Cramer
- -Wlifetime-safety, needs annotations?
- make proposal to hoist references to locals in functions outside the function to enable lifetime extension for more reference types like string_view
- child-groups, references to sub objects excluded

## Dinner at the Pullman

- with Victor, Mattheui 
- hardened pre /post conditions in the working draft
- - check cmake for long path \\?\ and patch cmake if needed 
- - https://rustlings.rust-lang.org/
- Rust compiles to WASM which , wasi 3.0 API , C++ also.
- https://emscripten.org/
- Yosh Wuyts https://developer.microsoft.com/en-us/advocates/yoshua-wuyts
- 



## Information

- ⚜️ Hey ! I'm Jan Wilmans, I am at ACCU on Sea 2026 this week and I am the author of this Live Blog.
- I will post updates during the week about whats happening, talks that stand out to me and a collection of more or less random things. Come back for regular updates if you are interested 😋.
