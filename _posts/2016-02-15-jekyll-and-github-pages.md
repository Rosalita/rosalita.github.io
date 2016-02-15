---
layout: post
title: Jekyll and Github Pages
excerpt: "As you can see I set up Jekyll and Github pages."
tags: [first post]
comments: false
---

I decided I should probably set up my own Jekyll & Github page in case I need it at some point in the future.

### Go is Great

I've been learning and writing Golang since November 2015. Progress is slow but I am writing code every day. I'm hopeful that one day I will be knowledgable enough to start making some fun projects. I'm currently learning all the data structure and working through <a href="https://projecteuler.net/"> Project Euler problems</a>. One of the things I really like about Jekyll is the Rouge highligher which makes Go code look nice. This was the first problem I solved on project Euler.



{% highlight go%}
package main

import(
  "fmt"
)

func main(){
  x := 0
  total:= 0
  fmt.Println("to find sum of numbers less than x that are multiples of 3 or 5, enter x")
  fmt.Scanln(&x)
  fmt.Printf("x is %d\n", x)
  for i:= 1; i < x; i++ {
    fmt.Printf("i is %d\n", i)
       if i % 3 == 0 || i % 5 == 0 {
         fmt.Printf("%d divides by 3 or 5\n", i)
         total += i
         }
    }
    fmt.Printf("answer is: %d\n", total)
}
{% endhighlight %}





<img src="https://projecteuler.net/profile/Rosalita.png">


There are achievements for solving the problems and you even get your own url to a tiny image that display how many problems you have solved. Which is kind of neat.
