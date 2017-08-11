## Powerful text searching and matching with Regular Expressions

---

### General Introduction

- Intersect (http://intersect.org.au)
   - Who are we?
   - Your trainers
- Your University IT Contacts
- General Housekeeping
   - Toilets
   - Coffee and water facilities
   - Emergency exits

---

![Logo](https://imgs.xkcd.com/comics/regular_expressions.png)

https://xkcd.com/208/

---

### Find and Replace

- Most people will be aware of the *find* and *replace* options of programs such as *Word*.
- Often we use find to locate the occurrence of a particular word, phrase or number.
  - E.g., _realize_, _cookie_, _3.1415927_

+++

#### Sometimes the objective is…

to find out how many matches there are
    _101 occurrences of "realize"_
to locate each match and review it in context 
    _"Cookie" occurs before "monster"_
to replace or substitute that match for something else 
    _"replace 3.1415927 with π"_

---

### Regular Expressions

can be used to make *more sophisticated* matches and *more complex* substitutions.

+++

#### You might want to find…

- all the phone numbers or email addresses in a document
- all the hashtags in a collection of tweets
- all the words that start with "e" and end in "ed", irrespective of length
- all words at the end of a line of text
- "honest" words, like "honor", "honour", "honorable", "honesty", etc.

+++

#### Conceptual leap

Note this leap from looking for a literal match ("#auspol") to matching a pattern

All things that look like a hashtag; a # character followed by alphanumeric characters



---

## Regexes are: 

### Everywhere!

You can use regular expressions (regexes) in:
- Most good text editors:
   - TextWrangler, Notepad++, Jedit, Vim, Sublime Text…
- Google Spreadsheets
- Microsoft Word (a reduced set anyway)
- Open Refine
- Command Line programs
   - sed, grep…
- Programming languages
   - Perl, Python, Ruby, R…
- Online sandpits

+++

## Regexes are: 
### Very old

- Developed in 1950s
- Based on characters in basic set 
    -what's available on a keyboard
- Many extensions since then
- Some variation in syntax between implementations

+++

## Regexes are: 
### Frustrating

- Syntax is easily forgotten
- Some matches might not be possible

+++

## Regexes are: 
### Not machine learning

- Regular expressions are not an example of machine learning
- You need to specify the pattern – the rule – that matches what you want, and _only_ what you want
- This is sometimes challenging, and occasionally impossible
