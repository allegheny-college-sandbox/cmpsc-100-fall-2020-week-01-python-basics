# CMPSC 100: Fall 2020, Week 01

* Distributed: 5 September, 2020
* Due: 17 September, 2020

## Point values

---

|Type         |Point value |
|-------------|------------|
|Worksheets   |10 pts.     |
|Lab          |20 pts.     |
|Participation|15 pts.     |
|             |            |
|Total        |45 pts.     |
|             |4.5% of course |

## Table of contents

For those who just want to get to work, consult the `Instructional Materials` section. Else, for additional summary or context, read the additional sections included.

* [Accepting the assignment](#Accepting-the-assignment)
* [Overview](#Overview)
  * [Evaluation](#Evaluation)
* [Instructional materials](#Instructional-materials)
  * [Media](#Media)
  * [Worksheets and activities](#Worksheets-and-activities)
  * [Lab](#Lab)
* [Python basics](#Python-basics)
  * [What is programming?](#What-is-programming?)
  * [What is a programming language?](#What-is-a-programming-language?)
  * [Why Python?](#Why-Python?)
* [Syntax](#Syntax)
* [Data types](#Data-types)
* [Lab activity: G. Wiz and the lousy lottery](#Lab)
* [Wrap-up](#Wrap-up)
  * [GatorGrader](#GatorGrader)
  * [Submitting your work](#Submitting-your-work)
  
## Accepting the assignment

---

- [ ] Log into the `#labs` channel in our class [Slack](https://cmpsc-100-02-sp-2020.slack.com)
- [ ] Click the link provided for the lab assignment and accept it in GitHub classroom
- [ ] Once the assignment finishes building, click the link to go to your personal repository assignment

## "Cloning" a repository

### Using the correct download link

- [ ] On this repository's page, click the `Clone or download` button in the upper right hand corner
* You may need to scroll up to see it
- [ ] In the upper right corner of the box that appears, click `Use SSH`
- [ ] Copy the link that appears in the textbox below the phrase "Use a password with a protected key."

#### Cloning

* [ ] Type `ls` in your terminal window
* You should be in your `CMPSC100` directory
- [ ] Change directories (`cd`) to your `Labs` folder
- [ ] Once in the labs folder, "clone" the repository using the link copied above
* If I (the instructor) were to clone my own repository, I'd enter (your link will look different):

```
git clone git@github.com:allegheny-college-cmpsc-100-spring-2020/cmpsc-100-spring-2020-lab-04-dluman
```

## Overview

## Evaluation

### Worksheets

* Responses to all questions or blank cells

### Lab 

* See individual [lab guidelines](lab/Week%2001%20-%20Lab%20-%20The%20Lousy%20Lottery.ipynb#Requirements)

# Instructional materials

## Worksheets and activities

* [Week 01, Worksheet 0: Python syntax (expressions)](worksheets/Week%2001%20-%20Worksheet%200%20-%20Syntax%20-%20Expressions.ipynb)
* [Week 01, Worksheet 1: Python syntax (assignments)](worksheets/Week%2001%20-%20Worksheet%201%20-%20Syntax%20-%20Assignments.ipynb)

## Lab

# Python basics

## What is programming?

The job of a programming language is to solve problems. You can think of it like this:

![Yep, definitely nothing here.](https://cs.allegheny.edu/sites/dluman/cmpsc100/cmpsc-100-black-box.png)

A programmer, then, has the task of writing the thing in the box -- the program that takes the `inputs` and turns them into understandable, desirable, or interesting `outputs`. That, in itself, constitutes a kind of magic; skilled magicians can look into the box and understand the "code" of the trick, but mostly folks who use programs expect them to do whatever it is they do, and don't generally are too much about how the trick is done.

In this class, we're interested in how the tricks are done.

## What is a programming language?

A programming language is the tool that programmers use to solve those above-referenced problems. There are many, and each have their own distinct advantages and drawbacks in addition to working in vastly different ways. Some languages are better for embedding directly on microchips; others are best used for making applications that live on the Internet.

While most contemporary computer languages are referred to as "Turing Complete" (meaning that a programmer should be able to do everything in language "B" that they could do with language "A"), professional programmers constantly contend with using the language that's "right" for a given job. Many programmers are hired because of skill in one particular language that they use throughout their career. Others like to learn as many as they can and dabble in pushing languages to their limits.

Yet, still, programmers are susceptible to comfort and personal bias. Typically, programmers play favorites with languages and many have strong opinions about the set of languages they use. 

There is no "universal" programming language, and many projects rely on a combination of them to work. 

## Why Python?

Simply put, Python follows Bushnell's Law of being "[easy to learn and difficult to master](https://en.wikipedia.org/wiki/Bushnell%27s_Law)." Mostly, you can start to do cool stuff fast.

More importantly, Python offers a great introduction to what programming languages _should be able to do_. I cannot (and would not) promise that you'll leave this class as a master of the Python language. Mastery shouldn't be the end goal. In fact, [Python has changed quite a bit](https://www.python.org/dev/peps/) since its introduction in 1991, so it's hard for anyone to truly master something that keeps moving.

Python is also an _interpreted_ language -- which means there's no compiler. This means that you run code directly from the text that creates it without any intermediate steps.

As we learn Python in this course, it's best to keep on eye on _what_ it's doing and _how_ it's doing it. This is the "trick" that we're interested in.

## "Syntax"

> Colorless green ideas sleep furiously.
>
> Noam Chomsky

Makes sense, right? Well, not really. But here's the thing: it is a 100% "correct" English-language sentence. We know this because languages (including Python) have a specific way of being arranged called "syntax." Let's break the above down to demonstrate

| Word      | Function  |
|-----------|-----------|
| Colorless | adjective |
| green     | adjective |
| ideas     | noun      |
| sleep     | verb      |
| furiously | adverb    |


So yeah -- colorless green ideas do, indeed, sleep furiously.

<div class="alert alert-block alert-info">
    <b>PROTIP:</b> Like for colorless green ideas, sleep is important.
</div>

Python also has a "syntax" or "way of speaking." Though there is more to it than we'll talk about here, the common features in how the language organizes itself are:

* statements, which are:
  * expressions
  * assignments
  * function calls
* comments

### Statements

Complete syntactic units in Python are referred to as "statements." A statement represents a complete thought or small operation. Each complete statement takes up one (1) physical written line. The line count of a Python program can range from one (1) to several thousand.

Statements are _functional_ which means that they _do something_:

* a calculation
* create text
* store values
* modify values

In the following set of worksheets, we explore statements and the various ways that Python constructs its syntax.

* [Week 01, Worksheet 0: Python syntax (expressions)](worksheets/Week%2001%20-%20Worksheet%200%20-%20Syntax%20-%20Expressions.ipynb)
* [Week 01, Worksheet 1: Python syntax (assignments)](worksheets/Week%2001%20-%20Worksheet%201%20-%20Syntax%20-%20Assignments.ipynb)

## Data types

* [Week 01, Worksheet 2: Data types]()

# Lab activity: G. Wiz and the lousy lottery

* [G. Wiz and the lousy lottery](lab/Week%2001%20-%20Lab%20-%20The%20Lousy%20Lottery.ipynb)

# Wrap-up

## GatorGrader

## Submitting your work