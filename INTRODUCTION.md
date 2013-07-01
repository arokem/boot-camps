# Introduction

### The goal of this workshop: 

Computers are increasingly making their way into non-computer sciences.

- People are really good at some things. Computers are very good at other things.
- Don't let your computer do what you could do better.
- But don't bother doing all the things your computer should be doing!

In other words, scientists in all fields need to learn how to use
computers. However, the academic institutions are slow to adapt and many
departments still do not offer formal instruction addressing the computational
needs of scientists in these departments. The goal of this workshop is to familiarize you with tools that will help you be a better scientist. These tools focus on capitalizing on the relative advantages of computers over humans. We will teach you a core of tools and hopefully give you an incentive to seek out more information yourself. 

### The instructors and helpers: 

**Instructors**
- [Shreyas Cholia](http://www.nersc.gov/about/nersc-staff/outreach-software-and-programming-group/shreyas-cholia/)
- [Ariel Rokem](http://arokem.org)

**Helpers**
- ??
- ?? 

What are helpers for? Well, they're here to *help*! If you are stuck with something, but you don't think that it's a question for the entire class(something about your setup), please attach a sticky note to your laptop. helper will come and help you out.

## [The schedule](http://arokem.github.io/boot-camps/2013-07-01-christchurch/#schedule)


# Day 1 - the basics

- The unix shell : the unix shell is a powerful tool for interacting with the contents of your computer. In the shell, atomic operations are strung together to automate routine operations

*"This is the Unix philosophy: Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface."* -- Doug Mcllroy (via [Wikipedia](http://en.wikipedia.org/wiki/Unix_philosophy))

- Git : Version control, or time travel made easy.

# Day 2 - programming 

- Introduction to python : Python is a programming language that is rapidly becoming the *lingua franca* for many scientific fields. It is relatively easy to learn. Makes difficult tasks easy and impossible tasks possible. Many libraries help to do the tasks that we want to do as scientists. 

- Scientific computing in python : We will introduce the numpy library for array computations and the scipy library for performing scientific computations. Matplotlib will be introduced as a way of visualizing data. 

# Day 3 - Building robust reliable really reliable science 

- Software validation and testing : Now that you know how to program, make sure that your software works. We will use automated testing using the nose library. Test-driven development will be introduced as a way of thinking about writing code. 

- Reproducible work-flow: with all the tools at our disposal, we will now demonstrate how you would build a reproducible work-flow for your computational analysis. 

### Etherpad: 
Find the instructors and helpers during the breaks and ask us questions! But - in particular, please use [this etherpad](https://etherpad.mozilla.org/swc-christchurch-072013) to make comments and ask questions as we go along.

The etherpad has both a central text field, that we will fill with comments, tips, etc. and a chat-box on the right-hand side. Use that to ask questions. 

At the end of every session, we will ask you to give feedback through the etherpad

## Questions?

## Before we move on

Does everyone have everything they need installed?

- Let's open a terminal
- Navigate to an easy to find location on your hard-drive. For example:
    $cd ~/Documents

- And get this repository, by running this command (we will explain this command later this afternoon):
	git clone -b 2013-07-christchurch https://github.com/arokem/boot-camps.git

- Now change your working directory to the `SWC` directory. The files that we will be using in the workshop (+much more!) should now be in there.
