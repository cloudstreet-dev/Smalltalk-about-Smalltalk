# Chapter 7: The Others - Brief Encounters

[← Previous: Amber](06-amber.md) | [Next: Chapter 8 - Influences and Legacy →](08-influences.md)

---

Not every Smalltalk gets a whole chapter, but they all deserve recognition. Here are the supporting cast members in our Smalltalk drama:

## Dolphin Smalltalk: The Windows Whisperer

Still alive in 2025, Dolphin Smalltalk remains the best way to build native Windows applications that nobody knows are Smalltalk. It's like a secret agent that infiltrated Microsoft's ecosystem and decided to stay. Beautiful native Windows apps, COM integration, and a development environment that makes Visual Studio look bloated. The catch? It's Windows-only, which in 2025 is like being fluent in Latin—impressive but limited in application.

Dolphin is now open source and free, a move that came too late to save it from obscurity but just in time to preserve it for posterity. It's the Smalltalk that proves you can build "real" Windows applications without C++ or C#. The MVP (Model-View-Presenter) framework is so clean it makes other GUI frameworks look like they're trying too hard.

## Cuis Smalltalk: The Minimalist's Dream

Juan Vuletich looked at Smalltalk and decided it had gotten too complicated. Cuis is his answer: Smalltalk reduced to its essence, like a bonsai tree or a haiku. It's beautiful, elegant, and purposefully limited. The entire system fits in your head, which is either its greatest strength or why nobody uses it for production, depending on who you ask.

Cuis takes pride in what it doesn't have:
- No backward compatibility baggage
- No thousands of obscure classes
- No features added "just because"
- No complexity without purpose

It's Smalltalk that went on a diet and discovered minimalism. The entire core system is about 600 classes—compare that to Pharo's 8,000+ and you understand the philosophy. Cuis proves that you can build a complete, modern Smalltalk system that a single person can fully understand. Whether you'd want to use it for your next project is another question entirely.

## Smalltalk/X: The Speed Demon

What if Smalltalk was as fast as C? Smalltalk/X answers with a emphatic "it can be!" It compiles to machine code, integrates with C seamlessly, and runs at speeds that make other Smalltalks look like they're running in molasses. The price? Complexity that makes you wonder if you should just use C++. But when you need Smalltalk that can compete with systems languages, Smalltalk/X is your formula one race car.

Smalltalk/X can:
- Compile to standalone executables (real ones, not bundled VMs)
- Inline C code directly in Smalltalk methods
- Call C functions with zero overhead
- Generate code that runs at near-C speeds

It's the Smalltalk for people who love Smalltalk but also love performance benchmarks. The IDE looks like it escaped from the 1990s, but when your Smalltalk code is outperforming Java, you stop caring about aesthetics.

## VisualWorks: The Enterprise Elder

Once the commercial king of Smalltalk, VisualWorks in 2025 is like finding a mainframe in a startup—it still works, it's still powerful, but everyone's slightly surprised it's still there. The companies using it have applications older than some programming languages, and they're not changing anytime soon. It's Smalltalk's COBOL moment, and that's not entirely an insult.

VisualWorks powers:
- Trading systems that move billions daily
- Insurance platforms that have processed claims since the 1990s
- Manufacturing systems that refuse to die
- Government systems that will outlive us all

It's the Smalltalk that proved you could build enterprise systems that last decades. The licensing costs could fund a small startup, but when your system has been running flawlessly for 25 years, ROI calculations become academic.

## GemStone/S: The Persistent Perfectionist

GemStone/S isn't just a Smalltalk—it's a Smalltalk with a built-in object database. Imagine if your objects never died, if persistence was automatic, if ACID transactions were as natural as message passing. That's GemStone/S: the Smalltalk that solved the object-relational impedance mismatch by eliminating the relational part entirely.

In GemStone/S:
- Objects live forever (or until you tell them not to)
- Multiple VMs can share the same object space
- Transactions are first-class citizens
- You can have objects larger than RAM

It's enterprise Smalltalk for people who think enterprise Java isn't enterprise enough. The learning curve is vertical, the licensing costs are astronomical, but when you need objects that absolutely, positively must survive the heat death of the universe, GemStone/S is there.

## Newspeak: The Modular Maverick

Gilad Bracha looked at Smalltalk and said, "What if we took late binding to its logical extreme?" Newspeak is the answer: a Smalltalk where everything is late-bound, even classes. It's modularity taken to an almost absurd degree, where dependencies are capabilities and isolation is mandatory.

Newspeak features:
- No global namespace (even classes are local)
- True capability-based security
- Modules that actually module
- Mirror-based reflection that makes your head hurt

It's the Smalltalk for programming language researchers and people who think dependency injection doesn't go far enough. Production use? That would require explaining to your team why classes don't exist until runtime, and good luck with that.

## The Lesson of the Others

Each of these "other" Smalltalks teaches us something:

- **Dolphin** shows that Smalltalk can be a first-class citizen on any platform
- **Cuis** proves that simplicity is a feature, not a limitation
- **Smalltalk/X** demonstrates that dynamic doesn't mean slow
- **VisualWorks** confirms that good architecture survives decades
- **GemStone/S** solves persistence properly, expensively
- **Newspeak** explores what Smalltalk could become if we're brave enough

They're the experimental branches of Smalltalk evolution, each exploring a different "what if." Most will never be mainstream, but their ideas leak into other implementations, other languages, and occasionally, into the future.

---

[← Previous: Amber](06-amber.md) | [Next: Chapter 8 - Influences and Legacy →](08-influences.md)