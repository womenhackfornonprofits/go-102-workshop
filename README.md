# Go Workshop

## Overview

The principle goal of this workshop it to get you excited about Go! We’ll be
focussing on two key areas: object oriented development in Go, and the powerful
primitives which make concurrent programming in Go a breeze.

* [Introduction](topics/the-basics): built-in types, variable declaration,
  function and custom types.
* [Object oriented development](topics/object-orientation):
  [methods](topics/object-orientation/methods.md),
  [interfaces](topics/object-orientation/interfaces.md),
  [embedding](topics/object-orientation/embedding.md) and
  [composition](topics/object-orientation/composition.md).
* [Concurrency](topics/concurrency):
  [goroutines](topics/concurrency/goroutines.md) and
  [channels](topics/concurrency/channels.md).

In each section we'll walk through a number of examples and code samples, and
will work through some coding exercises in pairs, either using a local Go
installation or the Go Playground.

## Pre-Requisites

This workshop is designed for folks who have some basic knowledge of Go, but
not necessarily any practical experience with it.  Attendees are also expected
to have practical experience with the principles behind Object Oriented
software development (in any language).

I will recap some basics at the beginning of the workshop, but you'll get more
out of it if you already have knowledge of variable declaration, functions, and
struct types. I suggest you watch the first half of my recent [introductory
talk on Go](https://vimeo.com/140410716) (the "Data & Types" section), or a
least look through the [slide
deck](https://speakerdeck.com/timblair/introduction-to-go).

## What You'll Need to Bring

As long as you have a working laptop (or a friend with one, as we'll be pairing
for the exercises), then you’re good to go.  You don’t even need Go installed
on your machine, because you can use the online [Go
Playground](http://play.golang.org/) instead for the exercises.

## Exercises

There are templates available for each of the exercises.  If you've cloned this
repo under your `$GOPATH` then you can just edit and run the template file in
place.  Alternatively, follow the link to the template already set up in the Go
Playground, and work from there instead.

* The Basics: [source](topics/the-basics/exercises/basics/template/basics.go) /
  [playground](http://play.golang.org/p/ta6oFzjgwn)
* Object Orientation
  * Methods: [source](topics/object-orientation/exercises/methods/template/methods.go) /
    [playground](http://play.golang.org/p/jnBw-jtE3n)
  * Interfaces: [source](topics/object-orientation/exercises/methods/template/methods.go) /
    [playground](http://play.golang.org/p/rL5tT2VTJH)
  * Embedding: [source](topics/object-orientation/exercises/embedding/template/embedding.go) /
    [playground](http://play.golang.org/p/5qrrcfHdiZ)
* Concurrency
  * Goroutines: [source](topics/concurrency/exercises/goroutines/template/goroutines.go) /
    [playground](http://play.golang.org/p/EH_16WR5ND)
  * Channels: [source](topics/concurrency/exercises/channels/template/channels.go) /
    [playground](http://play.golang.org/p/H4F9aLKQVA)

Example solutions are also available, but don't look at those until you've had
a go yourself!

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

Except where otherwise noted, the content of this repository is licensed under
a <a rel="license"
href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons
Attribution-ShareAlike 4.0 International License</a>.
