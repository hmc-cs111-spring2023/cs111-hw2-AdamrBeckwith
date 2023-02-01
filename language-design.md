_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates
are:

- Something you agreed with / resonates with your own experience
- Something you disagree with
- Something that is interesting, a new idea or perspective you'd like to remember
- Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**

-  A master plan leads to "When people lose the sense of responsibility for the environment they live in, and realize that they are merely cogs in someone else’s machine, how can they feel any sense of identification with the community, or any sense of purpose there?" [Steele, 1998]

I feel like this is a very meaningful quote. Now of course you could use it as an analysis of the human condition, but even within the context of *specifically* design it really emphasizes art and creation as community (a home). We as programmers are a community, and the langauges we design (regardless of who for) require passion and dedication that leads to purpose. If we allow the industry to be dominated by a "master plan" in this context we will lose that community and purpose. 

- Every piece of software we use was written by other people, slaving away over thousands of lines of code. Why shouldn’t those “interfaces” be as humanely designed as the ones we tap and swipe?  [Pavlus, 2012]

I like this one compares programming and software design to mobile games and more :"consumer" based products. Treating ourselves (programmers) as above consumers is foolish. While we are experts we don't need more then they do, nor should we maintain a difficulty that only we can master. Only with clear and *humane* interfaces can we code effectively. Its healthier for everyone and the product to design everything for everyone. 

- "You can't please everyone so aim to displease everyone equally." [Bloch, 2006]

I disagree >:(. I feel while pleasing everyone is impossible, it is shooting yourself in the foot to act as if you can't. **Aim to please everyone despite the fact you will displease everyone equally in the end** is a better version of this phrase. Shoot for the moon, you might reach the stars kinda thing. You will be suprised how close you get to pleasing everyone. 

---

**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**

A well designed language has 2 main boons. One: it "must be designed to help the task of growth." [Steele, 1998] Specifically allowing community and individual members to build upon the language and grow it beyond its intended use, either into new subsections of its domain, or beyond it if necessary. 

Second: It must be human designed first and formost. Allow inefficiency as a trade for readibility, understandability and documentation. As Block says: "Design is an art, not a science. Strive for beauty, and trust your gut."[Bloch, 2006]. The actual design of the language comes first. 

We can see a badly designed language has the inverse of these qualities. It focuses on a single individual (or groups) designation of whats "good" for the language, designed by committee (rather then community). In addition, they may focus on low code character count rather then readibily and writeability. Its alienating for new uses while feeding the "old guards" ego. 

---

**Question**

How might the themes of _Growing a Language_ relate to ideas from the Fowler reading?

**Response**

I think it has a lot to do with *internal languages* that Fowler mentions. Specifically about the *boundries* of DSL's. I feel like the ability to add internal DSL's is a key part of allowing growth in a language. Let people specificy and modify a language to suite their specific needs and that will benefit your language in the long run. Which is exactly what DSL's are doing. Its all about modularity and not restriciting the end user and their needs. 

---

**Question**

In what way is an API a language?

**Response**

An API is a langauge just like sign language or speaking into a microphone is a language. It is a tool to allow people to interact and communicate with a langauge. For programming, using an interface doesnt make influencing a computer any less "programming" . ""All programmers are API designers.""[Bloch, 2006] This is because the goal of programming is to create a way for someone (you or someone else) to make a computer *do* something. An API is a way of interacting with a computer to do *something*. Therefore programming language is an API. 

---

**Question**

What does the post on grayscale tell us about the process of API design?

**Response**

Its a long long process. Generally its 1 person saying something and getting feedback. Its interesting how 90% of the comments are just people giving their own suggestions from their own fields. When in reality the writer was asking for feedback on his own set of 4 options. (I personally think black is the most intuitive). API design is trial and error on a community wide scale. Everyone tries it and 1 idea sticks. Lastly this is my favourite comment: TIGT: "If we do end up with gray(), will grey() be an alias?" It shows how specific and detail focused people will be with languages. "I need this function to use my personal spelling of grey" while also pointing out how america centric some programming models can be. 

---

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of AppleScript:

> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
> [[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**

---
