# Luca's Toy

## Introduction

My son's name is Luca. My wife and I are all software engineers. Luca is interested in computer and any other electronic devices very much. When we're at home, working with vi and ssh on the black terminal, little Luca can't help interrupting us from time to time.

It's time for Luca to start his K2 in 2019 Sep. He learned 26 letters and a few words when he was in K1. I think maybe we can teach him how to type or code. Luca likes computer and recognizes letters.

How to inspire him? It's boring for kids to just type letters. [Turtle graphics](https://en.wikipedia.org/wiki/Turtle_graphics) is a popular way to introduce young learners to programing. It was part of the original Logo programming language, which, according to Wikipedia, is an educational programming language Seymour Papert and others designed in 1967. Actually, I first encountered Logo when I was grade 4 in primary school. It's very cool to draw those fancy diagrams.

I hope Luca will like it. :)

## Example 1: Draw a line

One of the simplest things we can do using the turtle module is to draw a line.

### Code

```python
# Step 1: Make all the "turtle" commands available to us.
import turtle

# Step 2: Create a new turtle. We'll call it "luca"
luca = turtle.Turtle()

# Step 3: Move in the direction Luca's facing for 50 pixels
luca.forward(50)

# Step 4: We're done!
turtle.done()
```

## Example 2: Draw a square

Lines are boring. We can rotate the turtle in order to draw more interesting figures.

### Code

```python
import turtle

luca = turtle.Turtle()

luca.forward(50)
luca.right(90)

luca.forward(50)
luca.right(90)

luca.forward(50)
luca.right(90)

luca.forward(50)
luca.right(90)

turtle.done()
```
