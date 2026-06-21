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
- placeholder \_ building block for template matching

## Generating Language Bindings using C++ Reflection

- Callum Piper talks about implementing python bindings using C+26 reflection
- consteval function templates look really useful
- Bindings to javascript, python, or rust will become trivial to generate with a library
- you dont need expansion statement (template for) inside consteval functions because everything must happen at compile time, so normal for() works.

Walk with Sandor DARGO during lunch into the city center.

## Software and Safety

- Anthony Williams,
- Safety critical devices: when someone can get hurt, cars, airplane, pacemakers.
- IEC 61508 industry standard
- ISO 26262 is based on it for automotive software
- testing, contracts , if a contract is violated, it is a bug.
- CodeQL ?
- writing the same algorithm simpler or from a non-production library is valuable for testing

## KEYNOTE: Out of Our Minds: What is AI Doing To Us and For Us?

- How to organize your 💬 thoughts
- Tortoise AI scribe ?
- Should AI reduce or speed up thinking and /or cognitive load

## Lightning talks

- francis: respect wasps, leaving their next will cause them not to come back next year.
- ubsan finds more without asan in the same build.
