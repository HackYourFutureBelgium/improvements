a new plan for the modules based on what the students should be able to do, instead of the technologies they will learn

This plan only adds two weeks at the beginning for module 0, everything after that is the same length as it is now.

---




## Module 0: working with code (2 weeks)


Summary
* _pains you’ll relieve_: disorganized file systems, how/where to edit files, sharing files, making public sites
* _what you can build_: a live github pages portfolio, with markdown
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: your portfolio is very limited being written in markdown, it's easy to get lost in the process of building even a small project

Learning Objectives
* push, pull, fork, pr, branch with plain markdown files
* set up github pages
* work locally using VSC & GitKraken (or another client)
* learn how to turn in homework and integrate feedback using issues


## Module 1: incremental devlopment (3 weeks)


Summary
* _pains you’ll relieve_: make the portfolio you imagine with HTML/CSS, incremental development helps organize your work over time
* _what you can build_: responsive & static web pages, built in steps
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: HTML/CSS alone don't allow for much interaction, saving your steps in different folders is cumbersome

Learning Objectives:
* create simple & responsive HTML/CSS sites deployed to gh-pages
* use the devtools to inspect pages, modify live pages, and (loosely) replicate the styling of other web pages
* incremental, story/feature based development using one folder per step

## Module 2: separation of concerns (3 weeks)

Summary
* _pains you’ll relieve_: using Git branches makes incremental development much nicer, javascript puts some interactivity behind your sites.
* _what you can build_: simple web pages, built in steps, with the ability to display processed user input
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: the user interface is very static and limited, pages that don't remember data are very limited

Learning Objectives
* use JS to make stateless web pages (pure functions connected to inputs/outputs in the dom)
* isolating logic from view and testing it
* branches and commits to organize incremental development
* JS/debugger/testing foundations

## Module 3: stateful programming (3 weeks)

Summary
* _pains you’ll relieve_: storing data in a ```state``` object makes much more interesting sites, dom components make for a more interesting user experience
* _what you can build_: simple web pages that take user input, process it with page state, and more complex user output with vanilla components
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: your JS is scattered and doesn't feel "whole", having a static page structure is limiting

Learning Objectives
* forms for inputting more interesting data
* pure, vanilla dom components for rendering data structures
* a state object (with no methods)
* more challenging pure functions that operate on user inputs and the state object
* dividing and collaborating on shared code base


## Module 4: oop (3 weeks)

Summary
* _pains you’ll relieve_: organizing code into objects makes for a nicer experience, fully rendered pages are more interactive
* _what you can build_: a fully interactive (but simple) web page with vanilla JS that is organized into an object
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: dealing with a lot of vanilla dom is annoying, limiting your page data stored in source code is limiting

Learning Objectives
* simple oop apps with handlers for inputs and renders for outputs
* fully-rendered ui's (ie. start with only a root)
* behavioral testing / tdd
* running & testing js in the terminal

## module 5: using apis (3 weeks)

Summary
* _pains you’ll relieve_: accessing api's (external data or logic) makes your pages actually meaningful
* _what you can build_: interactive web pages that allow users to interact with third-party data or logic via api calls
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: your web page never remembers what people do between visits

Learning Objectives
* async calls to apis from frontend, render to dom
* basics of apis with postman and something like this: https://github.com/typicode/json-server
* reading and writing to .json files with fs

## module 6: persistence (3 weeks)

Summary
* _pains you’ll relieve_: learn how to organize and save application data between visits
* _what you can build_: very basic restful api that connects to a cloud-hosted sql database, and a super minimal ui for this api. not hosted at the same endpoint, so the api can stay clearly an api
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: the frontend is very limited, and it's a bit strange having to go to two different ports

Learning Objectives
* basic fs read/write for persisting state as json
* basic restful backends reading & writing to cloud-hosted postgres (tested with postman)
* most basic/transparent crud frontend to call backend (basically a ui for the api, this can even be provided)


## module 7: fullstacking (3 weeks)

Summary
* _pains you’ll relieve_: putting everything behind one endpoint finally feels like a real web app!
* _what you can build_: very simple fullstack webapp with vanilla frontend & minimal express backend
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: it's still a pain to build vanilla frontends

Learning Objectives
* super basic vanilla fullstack with 2 data types (ie. front & back behind a single endpoint, "/" is frontend, "/api" is the api)
* minimal deployment with now, or something like it

## module 8: frontend frameworks (3 weeks)

Summary
* _pains you’ll relieve_: using frameworks and buildscripts allows much smoother frontend development
* _what you can build_: simple fullstack web apps, but with frameworked frontends
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: growing code bases are difficult to manage, and sharing work is challenging

Learning Objectives
* frontend build scripts
* intro to frontend frameworks (hyperapp with built-in logging?)

## module 9: projecting (5 weeks)

Summary
* _pains you’ll relieve_: learn strategies for understanding and organizing growing code bases, how to plan projects ahead of time, and how to collaborate on larger projects
* _things you’ll build_: a fullstack app with good architecture, developed over 5 weeks in teams, with multiple data types, using a light project management methodology
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: your projects are still definitely learning projects, what's the real world like?

Learning Objectives
* dividing and organizing code for collaborating on growing code bases
* testing & documenting larger projects
* react intro

## bootcamp (4 weeks, full time, open to all alumni)

Summary
* _pains you’ll relieve_: experience the full professional experience
* _what you can build_: an open-source prototype/mvp for a social-good project
* _skills you’ll encounter_: (see learning objectives)
* _pains you’ll feel_: you'll be painfully ready for a real job

Learning Objectives
* more into react and frontend state management
* project management methodologies
* authentication
* ... deeper into whatever the students want to specialize in
