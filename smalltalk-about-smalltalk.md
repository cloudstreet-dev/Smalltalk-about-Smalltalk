# Smalltalk About Smalltalk
## A Tour Through the Living Dialects of a Revolutionary Language

---

## Table of Contents

1. [Introduction: The Language That Refuses to Die](#introduction)
2. [Squeak: The Mouse That Roared](#squeak)
3. [Pharo: The Industrial Revolutionary](#pharo)
4. [Glamorous Toolkit: The Moldable Maverick](#glamorous-toolkit)
5. [GNU Smalltalk: The Command-Line Contrarian](#gnu-smalltalk)
6. [Amber: The Browser's Best Friend](#amber)
7. [The Others: Brief Encounters](#others)
8. [Influences and Legacy: How Smalltalk Infected Everything](#influences)
9. [Conclusion: Why We Can't Quit Smalltalk](#conclusion)

---

## Introduction: The Language That Refuses to Die {#introduction}

In 2025, declaring yourself a Smalltalk developer is a bit like admitting you collect vinyl records or practice calligraphy. People nod respectfully, secretly wondering if you also churn your own butter. Yet here we are, half a century after Alan Kay's team at Xerox PARC birthed this peculiar language, and Smalltalk not only survives—it thrives in pockets of innovation that would make its ancestors proud.

The joke in programming circles is that Smalltalk has been "dying" for thirty years, which makes it the healthiest corpse in computer science. While languages born decades later have already fossilized in version control graveyards, Smalltalk continues to evolve through its various implementations, each one a unique snowflake in the blizzard of object-oriented programming.

This book isn't about teaching you Smalltalk syntax—if you need that, you're probably already lost in a sea of square brackets wondering why `3 + 4 * 5` equals 35 instead of 23. (Spoiler: left-to-right evaluation, no operator precedence. You're welcome.) Instead, we're here to explore the delightful chaos of modern Smalltalk implementations, each one solving different problems for different tribes of developers who all agree on one thing: messages are better than methods, and everything really should be an object.

### The Family Reunion Nobody Asked For

Imagine a family reunion where everyone shares the same DNA but has evolved in wildly different directions. Squeak shows up wearing tie-dye and talking about educational revolution. Pharo arrives in a business suit, PowerPoint at the ready. Glamorous Toolkit floats in on a cloud of moldability manifestos. GNU Smalltalk lurks in the corner with a terminal window, muttering about POSIX compliance. And Amber? Amber's livestreaming the whole thing to the browser.

Each implementation represents a different philosophy about what Smalltalk should be in the 21st century. They share the same fundamental beliefs—everything is an object, computation happens through message passing, and the environment should be live and introspective—but their expressions of these beliefs vary wildly.

### Why This Book, Why Now?

The Smalltalk landscape in 2025 is more vibrant than it has been in years. The rise of microservices made people appreciate message-passing architectures. The JavaScript ecosystem's complexity has developers yearning for Smalltalk's elegant simplicity. Machine learning researchers have discovered that Smalltalk's live environments are perfect for exploratory data analysis. And a new generation of developers, raised on REPLs and hot-reloading, find Smalltalk's "always running" philosophy surprisingly modern.

But navigating this landscape is treacherous. Choose the wrong Smalltalk for your project, and you'll spend more time fighting the implementation than solving your problem. This book is your guide through the wilderness, helping you understand not just what each Smalltalk can do, but what it wants to do, what it dreams of doing, and what it absolutely refuses to do no matter how nicely you ask.

---

## Squeak: The Mouse That Roared {#squeak}

If Smalltalk implementations were bands, Squeak would be the one that never sold out. Born in 1996 from the original Smalltalk-80 code (literally—Apple released it and Dan Ingalls said "hold my beer"), Squeak has remained true to the original vision while somehow also being the most experimental of all Smalltalks.

### The Eternal Playground

Squeak's motto might as well be "What if we never stopped playing?" It's the implementation that asks, "Why shouldn't children program multimedia applications?" and "What if the development environment was also a game engine?" These aren't rhetorical questions—Squeak actually built Etoys and Scratch on these premises, teaching millions of kids to code while the "serious" programming world wasn't looking.

The Squeak community has a peculiar habit of solving problems nobody knew existed. Need a programming environment that runs identically on everything from a Raspberry Pi to a supercomputer? Squeak's got you. Want to simulate biological systems while composing music? There's a package for that. Looking for a Smalltalk that can modify its own virtual machine while running? Welcome home, you beautiful weirdo.

### The Technical Peculiarities

Squeak's virtual machine, now evolved into the Cog VM, is a testament to what happens when computer scientists have too much fun. It features:

- **Just-in-time compilation** that would make Java jealous
- **Become:** the infamous method that can transform any object into any other object (yes, you can turn the number 3 into a HTTPServer if you really want to)
- **Morphic:** a UI framework so flexible it's basically Play-Doh for pixels
- **The ability to save your entire world** (image) and resume it decades later, like a computational time capsule

In Squeak, you don't just write programs—you grow them like digital gardens. The image-based development means your code, data, and running processes all live together in harmony, or occasionally, in spectacular chaos.

### Who Uses Squeak in 2025?

- **Educators** who believe programming should be taught like art, not engineering
- **Researchers** exploring everything from music composition to cellular automata
- **Digital artists** who treat code as a medium, not just a tool
- **That one person in every organization** who insists on using it for production systems and somehow makes it work

### The Squeak Paradox

Squeak's greatest strength and weakness is the same: it refuses to compromise. While other Smalltalks have adapted to the "file-based development with version control" world, Squeak doubles down on the image-based approach. Git integration? "Why would you version files when you can version objects?" they ask, while the rest of us weep into our merge conflicts.

---

## Pharo: The Industrial Revolutionary {#pharo}

If Squeak is the artist, Pharo is the engineer who looked at Smalltalk and said, "This is beautiful, but can it deploy to Kubernetes?" Forked from Squeak in 2008, Pharo set out to be the Smalltalk that could actually get you a job in 2025.

### The Great Cleanup

Pharo's origin story reads like a programmer's Marie Kondo episode. The team took Squeak, removed everything that didn't "spark joy" (or serve industrial purposes), and rebuilt it with a focus on:

- **Modularity:** Everything is a loadable package
- **Modern tooling:** Git integration that actually works (mostly)
- **Professional appearance:** A UI that won't frighten your manager
- **Speed:** Performance optimizations that make real applications feasible

The result? A Smalltalk that startups actually use, that consultants can sell, and that doesn't require a PhD in computer science history to understand.

### The Ecosystem That Could

Pharo's package manager, Metacello, along with its integration with GitHub/GitLab, created something the Smalltalk world hadn't seen before: a thriving, modern ecosystem. In 2025, you can:

- Deploy web applications with **Seaside** or **Teapot**
- Build microservices that actually micro and actually service
- Create native mobile apps (yes, really)
- Analyze data with libraries that rival Python's scientific stack
- Build enterprise applications without irony

### The Pharo Philosophy

Where other Smalltalks ask "What would Alan Kay do?", Pharo asks "What would a pragmatic developer need?" This leads to fascinating tensions:

- **Live programming** meets **continuous integration**
- **Image-based development** meets **source code management**
- **Object thinking** meets **microservice architecture**
- **Simplicity** meets **real-world complexity**

Pharo threads these needles with varying degrees of success, but the attempt itself has pushed Smalltalk forward more than any other implementation.

### Who's Using Pharo?

- **Financial institutions** for rapid prototyping and risk analysis
- **Consultancies** building custom business applications
- **Researchers** who need more than a toy but less than enterprise Java
- **Web developers** who miss the simplicity of early Rails but want modern features
- **IoT developers** targeting ARM devices with serious applications

### The Success Nobody Talks About

Here's the dirty secret: Pharo is probably the most successful Smalltalk you've never heard of. While the programming world argues about JavaScript frameworks, Pharo quietly powers trading systems, insurance platforms, and manufacturing processes. It's the implementation that proved Smalltalk could grow up without growing old.

---

## Glamorous Toolkit: The Moldable Maverick {#glamorous-toolkit}

Just when you thought Smalltalk couldn't get more opinionated, along comes Glamorous Toolkit (GT) with a radical proposition: what if your development environment was as malleable as your code?

### The Moldability Manifesto

GT doesn't just want you to write programs; it wants you to sculpt custom tools for understanding them. Every object in GT can have custom visualizations, custom inspectors, custom everything. It's like giving every developer their own personal Tony Stark workshop, except instead of building Iron Man suits, you're building bespoke lenses for viewing your code.

The GT team observed that developers spend 50% of their time reading code and another 40% trying to understand it, leaving only 10% for actual writing. Their response? Make the 90% as powerful as possible. In GT, you don't just read code—you experience it through custom-built archaeological tools that you create on the fly.

### Examples, Examples Everywhere

GT's most controversial feature might be its approach to documentation: examples aren't just documentation, they're executable specifications that also serve as tests, tutorials, and regression detectors. Every method can have examples that:

- Show how to use it
- Verify it still works
- Serve as living documentation
- Enable example-driven development

It's documentation that can't lie because it runs every time you save.

### The Lepiter Revolution

GT includes Lepiter, a "knowledge management system" that makes other note-taking tools look like cave paintings. Imagine if Jupyter Notebooks and Notion had a baby, and that baby was raised by Smalltalk. You can:

- Mix prose, code, and visualizations in living documents
- Execute code snippets in place
- Link knowledge to actual running systems
- Build computational narratives that explain themselves

### Who's Embracing the Moldability?

- **Software archaeologists** exploring legacy codebases
- **Data scientists** who want more than static visualizations
- **Consultants** building custom analysis tools for each client
- **Researchers** who need to explain complex systems
- **Teams** practicing example-driven development

### The Beautiful Madness

GT is what happens when you take Smalltalk's "everything is an object" philosophy to its logical extreme and then keep going. It's simultaneously the most powerful and most overwhelming Smalltalk experience available. You either get it immediately and can't imagine working any other way, or you run screaming back to your IDE where buttons stay in one place and inspectors don't have existential crises.

---

## GNU Smalltalk: The Command-Line Contrarian {#gnu-smalltalk}

In a world where every Smalltalk wants to be your entire universe, GNU Smalltalk (GST) politely declines. It's the Smalltalk that plays well with others, admits that files exist, and doesn't require you to abandon your entire toolchain.

### The UNIX Philosophy Meets Object Orientation

GST is what happens when Smalltalk goes to therapy and admits it might have some control issues. Instead of demanding you live inside its image, GST says, "Hey, want to just write some scripts?" Instead of custom tools for everything, it says, "Vim is fine, actually." It's Smalltalk for people who like Smalltalk but love their terminal more.

### Features That Make Other Smalltalks Nervous

- **File-based development:** Your code lives in actual files that git understands
- **Scripting support:** Shebang lines! Command-line arguments! Exit codes!
- **POSIX compliance:** It actually respects your operating system
- **Package management:** That works like every other language's package management
- **The ability to leave:** You can use GST for one part of your system without marrying it

### The Zen of GST

While other Smalltalks are building cathedrals, GST is building Unix tools. It's perfect for:

- Quick scripts that need more power than bash but less ceremony than Python
- Adding Smalltalk components to existing systems
- Teaching Smalltalk without the cognitive overhead of image-based development
- System administration tasks where Ruby feels too mainstream
- Proving that Smalltalk can be humble

### Who Uses GNU Smalltalk?

- **System administrators** who discovered it's better than Perl for everything
- **Polyglot programmers** who want Smalltalk in their toolkit, not their lifestyle
- **Educators** teaching OOP concepts without environmental complexity
- **Integration specialists** connecting Smalltalk ideas to Unix pipelines
- **Contrarians** who insist on using the "wrong" tool perfectly

### The Quiet Revolutionary

GST might be the most subversive Smalltalk of all. While others are trying to replace your entire development environment, GST is content to be just another language in your polyglot toolbox. It's Smalltalk without the evangelism, object-orientation without the orthodoxy. And sometimes, that's exactly what you need.

---

## Amber: The Browser's Best Friend {#amber}

If you told Alan Kay in 1972 that Smalltalk would one day run in a web browser, he'd probably say, "What's a web browser?" If you explained it, he'd say, "Oh, so like Dynabook but worse?" And yet, here's Amber, making Smalltalk dance in the most hostile environment ever created for programming languages: the JavaScript runtime.

### The Transpilation Tango

Amber doesn't just compile to JavaScript; it embraces it, extends it, and occasionally apologizes for it. It's Smalltalk that admits JavaScript won the browser war but refuses to accept that victory means good taste. Amber lets you:

- Write Smalltalk that becomes JavaScript that browsers actually run
- Call JavaScript libraries from Smalltalk (jQuery from Smalltalk is a trip)
- Use Smalltalk's live development in the browser's developer tools
- Debug Smalltalk code while it's running as JavaScript
- Experience existential confusion about what language you're actually using

### The Integration Immigration

Amber's superpower is its seamless JavaScript integration. You can:

```smalltalk
'#my-div' asJQuery html: 'Hello from Smalltalk!'
```

This isn't just foreign function interface; it's dual citizenship. Amber objects are JavaScript objects are Amber objects. It's the programming equivalent of being bilingual and forgetting which language you're thinking in.

### The Development Experience

Amber brings something beautiful to web development: live programming that makes hot-reloading look like stone-age tooling. Change a method? It updates immediately in your running application. Want to inspect that DOM element? Here's a Smalltalk inspector that understands JavaScript objects. Need to debug? Set breakpoints in Smalltalk code that's running as JavaScript.

The Helios IDE runs entirely in your browser, giving you a full Smalltalk development environment without installing anything. It's cloud development before cloud development was cool, except it all runs locally. Your browser becomes a Smalltalk machine that happens to speak JavaScript.

### Who's Betting on Amber?

- **Web developers** who think JavaScript needs more square brackets
- **Smalltalk developers** forced to do web development
- **Educational platforms** teaching programming in browsers
- **Prototype builders** who need rapid web development with live programming
- **People who like explaining why their web app is "actually Smalltalk"**

### The Philosophical Pretzel

Amber raises fascinating questions: If Smalltalk compiles to JavaScript, is it still Smalltalk? If JavaScript objects can receive Smalltalk messages, are they Smalltalk objects? If you debug Smalltalk code that's running as JavaScript in a browser that's probably implemented in C++, what language are you actually debugging?

The answer, of course, is yes.

---

## The Others: Brief Encounters {#others}

Not every Smalltalk gets a whole chapter, but they all deserve recognition. Here are the supporting cast members in our Smalltalk drama:

### Dolphin Smalltalk: The Windows Whisperer

Still alive in 2025, Dolphin Smalltalk remains the best way to build native Windows applications that nobody knows are Smalltalk. It's like a secret agent that infiltrated Microsoft's ecosystem and decided to stay. Beautiful native Windows apps, COM integration, and a development environment that makes Visual Studio look bloated. The catch? It's Windows-only, which in 2025 is like being fluent in Latin—impressive but limited in application.

### Cuis Smalltalk: The Minimalist's Dream

Juan Vuletich looked at Smalltalk and decided it had gotten too complicated. Cuis is his answer: Smalltalk reduced to its essence, like a bonsai tree or a haiku. It's beautiful, elegant, and purposefully limited. The entire system fits in your head, which is either its greatest strength or why nobody uses it for production, depending on who you ask.

### Smalltalk/X: The Speed Demon

What if Smalltalk was as fast as C? Smalltalk/X answers with a emphatic "it can be!" It compiles to machine code, integrates with C seamlessly, and runs at speeds that make other Smalltalks look like they're running in molasses. The price? Complexity that makes you wonder if you should just use C++. But when you need Smalltalk that can compete with systems languages, Smalltalk/X is your formula one race car.

### VisualWorks: The Enterprise Elder

Once the commercial king of Smalltalk, VisualWorks in 2025 is like finding a mainframe in a startup—it still works, it's still powerful, but everyone's slightly surprised it's still there. The companies using it have applications older than some programming languages, and they're not changing anytime soon. It's Smalltalk's COBOL moment, and that's not entirely an insult.

---

## Influences and Legacy: How Smalltalk Infected Everything {#influences}

The joke is that Smalltalk failed to take over the world. The punchline is that it succeeded—it just wore disguises.

### The Obvious Children

**Objective-C** was literally Smalltalk syntax grafted onto C, like a computational centaur. Brad Cox looked at C and Smalltalk and said, "Why choose?" Apple agreed, and thus iOS apps are basically Smalltalk programs that don't know it.

**Ruby** is what happens when Smalltalk has a fling with Perl at a scripting language convention. Yukihiro Matsumoto admitted he wanted "a language more powerful than Perl and more object-oriented than Python," but what he really meant was "Smalltalk that uses files." Ruby on Rails conquered web development using patterns that Smalltalk invented in the '80s.

**Java** took Smalltalk's virtual machine and object model, removed the fun parts, added static typing, and sold it to enterprise. It's like Smalltalk went to business school and came back wearing a suit. The JVM is basically a Smalltalk VM that forgot how to do "become:" and gained the ability to please managers.

### The Secret Influences

Every IDE with code completion? Smalltalk had it in 1980. Refactoring tools? Smalltalk invented the term. Test-driven development? Smalltalk was doing it before it had a acronym. Live programming? Smalltalk's been living it since birth.

The Agile movement? Kent Beck and Ward Cunningham developed it while working in Smalltalk. Extreme Programming? Born in a Smalltalk project. Design patterns? The Gang of Four book used Smalltalk for half its examples. MVC? Invented for Smalltalk-80.

### The Modern Reverberations

In 2025, when you:
- Hot-reload your React application
- Use Swift's message passing
- Debug with Chrome DevTools
- Write everything as microservices passing messages
- Use Electron for desktop apps (browser as universal VM)
- Practice "everything is a component" in modern frameworks

You're using ideas Smalltalk pioneered when the internet was still ARPANET.

### The Ultimate Irony

Smalltalk's greatest contribution might be proving that being right doesn't mean winning. It showed that elegance, consistency, and power aren't enough if you can't play well with others. Every successful language since has been less pure, less elegant, and less consistent than Smalltalk—and more successful because of it.

But here's the thing: Smalltalk doesn't care. It's still here, still pure, still showing us what programming could be if we weren't so worried about what programming should be.

---

## Conclusion: Why We Can't Quit Smalltalk {#conclusion}

Here we are in 2025, and Smalltalk is still the language that makes programmers feel feelings. It's the ex that got away, the road not taken, the alternative timeline where programming stayed fun. Every developer who seriously learns Smalltalk has the same experience: enlightenment followed by frustration that the rest of the world doesn't get it.

### The Eternal Appeal

Smalltalk offers something no modern language can: coherence. In a world where JavaScript developers need seventeen tools to build "Hello World," where Python can't decide if it's version 2 or 3, where every language is actually three languages (the language, the build system, and the package manager), Smalltalk remains beautifully, stubbornly whole.

It's not just a language; it's a philosophy rendered in code. The idea that programming should be conversational, that development should be live, that systems should be understandable—these aren't features, they're beliefs. And beliefs, unlike syntax, don't deprecate.

### The Communities That Won't Die

Each Smalltalk implementation has cultivated a community that's part user group, part philosophy club, part support group. They're the people who see `3 + 4 * 5` equaling 35 and think, "Yes, that makes sense." They're the developers who believe that if you can't inspect it, you don't really own it. They're the programmers who think version control should version objects, not text.

These communities are small but mighty, like specialized evolutionary niches that produce remarkable adaptations. They build things that shouldn't be possible, solve problems in ways that shouldn't work, and smile knowingly when the mainstream discovers "new" ideas that Smalltalk had forty years ago.

### The Future That's Always Coming

Every year, someone predicts this will be Smalltalk's year. It never is, and that's okay. Smalltalk doesn't need to win; it needs to exist. It's the control group in the great programming language experiment, the reminder of what we gave up for adoption, the road map to where we could have gone.

In 2025, Smalltalk is exactly where it should be: alive in its various forms, each one pushing boundaries in its own direction. Squeak keeps playing, Pharo keeps building, Glamorous Toolkit keeps molding, GNU Smalltalk keeps scripting, and Amber keeps transpiling. Together, they form a constellation of what programming could be if we optimized for thinking instead of typing.

### The Last Message

If Smalltalk has taught us anything, it's that in programming, as in life, the journey matters more than the destination. Every Smalltalk implementation is on its own journey, taking its own path through the landscape of computational possibility. They may never converge, may never dominate, may never "win" in any conventional sense.

But they persist. And in persisting, they remind us that programming is more than producing executables. It's about having conversations with computers, growing gardens of objects, and occasionally, just occasionally, catching a glimpse of what Alan Kay saw all those years ago: a medium for human thought that happens to run on machines.

So here's to Smalltalk in all its forms—may it forever remain the language we measure all others against, the standard we fail to meet, and the reminder that in programming, being right is more important than being popular.

After all, in a world where everything is an object, shouldn't programming languages be interesting?

---

*End of "Smalltalk About Smalltalk"*

---

## Appendix: Getting Started with Each Smalltalk

For the brave souls ready to dive in, here's where to find each implementation in 2025:

- **Squeak**: https://squeak.org - Download the all-in-one package and prepare for wonder
- **Pharo**: https://pharo.org - Get the launcher and join the professionals
- **Glamorous Toolkit**: https://gtoolkit.com - Download and prepare to have your mind reshaped
- **GNU Smalltalk**: Package manager of your choice, or build from source like it's 1999
- **Amber**: https://amber-lang.net - npm install -g amber-cli, and welcome to the contradiction
- **Cuis**: https://cuis-smalltalk.org - For when you need Smalltalk therapy
- **Dolphin**: https://github.com/dolphinsmalltalk - Windows native development awaits

Remember: choosing a Smalltalk is like choosing a philosophy. Choose wisely, but don't choose too seriously—it's supposed to be fun.

---

*"In Smalltalk, everything happens somewhere else." - Adele Goldberg*

*And that, perhaps, is the most honest thing ever said about programming.*