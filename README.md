# memory-hacks
A repository for my study of memory

## Source
Based on the hacks found in: [Ron Hale-Evans. Mind Performance Hacks.](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewBook)


## Dominic System

_"...The Dominic System uses an easy-to-remember number-to-letter conversion and the initials of memorable people, as well as journeys that are like memory palaces..."_

The first step for this to work is to remember the the keys from 0 to 9.

The letters a to h are used to represent the numbers 1 to 8, with the exceptions that `S` represents 6, (S being the first letter if six). And, the additions of O for 0 and N for nine.

O - 0

A - 1

B - 2

C - 3

D - 4

E - 5

S - 6

G - 7

H - 8

N - 9


When creating my own mnemonic for the dominic system I largely based in on the Ron Hale-Evans' template [mnemonics_public.txt](dominic-system/mnemonics_public.txt), finding suitable replacements which focus on my interests of music and art.

My compiled list is at: [dominic-template](dominic-system/dominic_template.md)

I made a list pertinent to me including plenty of visual artists and musicians and includes famous people who I find amusing.

For a few initials I had some real difficulty finding people I knew, so I added those with memorable humorous names. For instance:  05 - [Oscar Egg](http://en.wikipedia.org/wiki?curid=10185512) an Olympic cyclist.

### Links:

An online list
[dominic-number-memory-system](http://peoplebyinitials.com/p/dominic-number-memory-system)

Information and dropdown lists
[people by initials](http://peoplebyinitials.com)

Actors initials
[initials_of_characters_and_actors](http://www.creative-remembering-techniques.com/initials_of_characters_and_actors.html)


## Scripts

The code for all the hacks can be downloaded online: [hacks](http://examples.oreilly.com/9780596101534/)

To run for example:

```
# navigate to the scripts directory
$ cd memory-hacks/scripts

# Invoke the script by running the programming language’s interpreter and feeding it the script 
$ perl scriptname.pl

# Example using the `dominate` script:
$ perl dominate dominic.dat 8071 8100
```

Testing my additional data
```
$ perl dominate dominic-f9.dat 0000 0010
$ perl dominate dominic-f9.dat 8071 8100
```



