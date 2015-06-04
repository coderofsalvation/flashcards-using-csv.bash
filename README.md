flashcards-using-csv.bash
=========================

all the (basic) good stuff of ANKI in few lines of bash

## Why

I had a tiny embedded linux device which i wanted to use for learning a language.

## How to use 

dump some flashcard csv-files in flashcards/ and run:

    $ ./flashcard flashcards/*.csv

> NOTE: see flashcards/example.csv or use CSV exporters for ANKI flashcards

## In action

When running you will be presented a question

      i am a boy


Imagine you need to translate this in another language.
Think of the answer and press enter.
Now you'll see:

      i am a boy
      
      
      ik ben een jongen
      
      
      p) too easy     

Pressing enter will repeat the question at a later time, and p will ignore it in the future.
