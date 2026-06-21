## Saturday Day 4

- make a check in CI that functions stay vector optimized
- turn on compiler remarks to see why vectorization doesn't happen
- check the cores are not powermanaged during testing (failing powermanagement can be due to failing power management )
- look into a formatting of std::byte

## Hana's Keynote

- core, language, evolution?
- constexpr implementation in clang, values are stored as APValue and can be anything
- Pointer provenance data, pointing past the end of array and pointing
- inplace_vector initially initialized or not? find out.
- Encourage more people to help making compilers better, compilation of clang takes ~4 minutes on modern machines.
- Hash Array Mapped Trie

💡 idea lifetime extension for reference types? understand how that would (not) work. Probably because the reference outside the stack, but in that case its a different problem space. We could do this for anything stack allocated?

Reminder to self to send to Lieven de Cock: passing heap allocated values from compile time to runtime is not possible, for example std::string (but his suggested workaround at of course viable)

- most standard containers are now constexpr
- vector should be your default container unless you have a good reason to choose something else

## Jason, Safety in Numbers

- safety in numbers
- look at mp-units again
- look at ubsan minimal runtime
- std::saturating_add is called add_sat
- std::saturating_cast
- safe-comparisons break type safety

## Braden Ganetsky, Techniques of Compile-time Unit Testing in C++

- snitch, compile time testing
- k3tchup
- Braden talks us through the development process of a ingenious library that he is developing (not production ready) to allow both compile time and runtime testing
- He had to jumps to several interesting hoops to make it all happen, but it looks really interesting.
- Is makes me think that we should have compile-time facilities to store information that be used during constexpr evaluation to store and retrieve

## KEYNOTE: Taylor Cramer, Incrementally securing your C++ using Rust

- Taylor takes us through the process of making Rust <=> C++ interop possible
- -Wlifetime-safety, needs annotations? see https://clang.llvm.org/docs/LifetimeSafety.html
- note to self: make proposal to hoist more references to locals in functions outside the function to enable lifetime extension for more reference types like string_view
- child-groups, references to sub objects excluded

## Dinner at the Pullman

- with Victor Cuira, Mathieu Ropert, Celine and others.
- hardened pre /post conditions in the working draft
- check cmake for long path \\?\ and patch cmake if needed
- https://rustlings.rust-lang.org/
- Rust compiles to WASM which , wasi 3.0 API , C++ also.
- https://emscripten.org/
- Yosh Wuyts https://developer.microsoft.com/en-us/advocates/yoshua-wuyts
- https://opensource.microsoft.com/blog/2024/11/07/introducing-hyperlight-virtual-machine-based-security-for-functions-at-scale/
- https://opensource.microsoft.com/blog/2025/02/11/hyperlight-creating-a-0-0009-second-micro-vm-execution-time/
- https://cocktailsdistilled.com/recipe/beton-cocktail/

22:44 Still at The Bouverie (Tap) having a super relaxing 😎 chat with Victor Ciura
