rawlindarby
===========

I've been wanting to create my own programming language since forever. Some years ago, some of the concepts started to gel and the name "rawlindarby" was born, I can't even remember the why of the name. It just is.

My goals with this language are unclear, but here is where my notes and thoughts of it will germinate it's eventual being.These notes are a dump of many thoughs over the years and may seem like a chaotic mess, but that is ok because I'm in no rush and they will slowly converge into a small, simple, cohisive thing.

## Goals & Motivations
### Syntax & Semantics
- I want it all, but have to make some choices. I'm in no rush, so this is ok.
- I like loose & dynamic but also value a strong type system.
- I hate rules but value their guidance.
- I want exceptions to the rules but don't want a bloated beast
- I value orthoginality, simplicity, & consistancy
- core syntax should strive to reduce ambigutiy; there shouldn't be similar looking constructs that do different things
- Easy things should be easy and difficult things doable, hopefully easily doable.
- Readability is king
- I want the extensibility of lisp/scheme style macros, but don't want another lisp syntax
- erlang (ML?) style pattern matching is cool
- OO when (and only when) it makes sense
- easy scripting, as in "why on earth would I write bash code if I can do the same in rawlindarby"
- memory managemnt is automatic unless you really really really want otherwise
- embrace c-family syntax where it makes sense, but be free to diverge
- be able to be easily used by a novice, but geared at the experienced programmer
- erlang style "processes" are awesome
- promote usage of immutable state, but allow mutation
- the goals of scala were noble, but the end result is too bloated
- should be flexible but also encourage a "right way"
- javascript, but just the good parts


### Build, Compile, Runtime, & Hardware
- interpret-able AND compile-able in a clean and cohesive manner would be holy-grail
- the JRE is a tempting target platform, but...
- I've been playing with arduino and other low-level stuff. This language should be usable on arduino
- the erlang runtime is freakin awesome
- core runtime should be modular so that compiled binaries only include what they require

