# Object Oriented Programming - Lab

A practice lab where I built a small library system in Python using classes and inheritance. Everything's in `oop_lab.ipynb`.

## What's in it
- **LibraryItem**: the base class. Every item has a title, author, year, and an availability flag, plus methods to display info, check out, and return.
- **Book**: adds an ISBN and publisher.
- **Magazine**: adds an issue number and month.
- **DVD**: adds duration, director, and a set of genres, plus an `add_genre()` method. Author defaults to "N/A".

## What I practiced
Inheritance, `super()`, overriding methods, default values, and sets.

## Ideas for later
Block checkout when an item's already out, track multiple copies, and add more item types like audiobooks.