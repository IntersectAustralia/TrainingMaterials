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

### Regexes are… 

+++
#### …Everywhere!

- Most good text editors, TextWrangler, Notepad++, Jedit, Vim…
- Google Spreadsheets
- Microsoft Word (a reduced set anyway)
- Open Refine
- Command Line programs, sed, grep…
- Programming languages, Perl, Python, Ruby, R…
- Online sandpits

+++

#### …Very old

- Developed in 1950s
- Based on characters in basic set 
- Many extensions since then
- Some variation in syntax between implementations

+++

#### …Frustrating

- Syntax is easily forgotten
- Some matches might not be possible

+++

#### …Not machine learning

- Regular expressions are not an example of machine learning
- You need to specify the pattern – the rule – that matches what you want, and _only_ what you want
- This is sometimes challenging, and occasionally impossible

+++

#### …Powerful!

- Once you learn them, you will see applications everywhere

---

### So!

Let's get started!

+++

#### Exercise 1: Avian Internet

- RegExr
   - http://www.regexr.com
- RFC2549
   - http://bit.ly/1MLmg7C

+++

#### Exercise 2: To die upon a kiss

- RegExr
   - http://www.regexr.com
- Full text of Othello
   - http://bit.ly/1tKfAMW

+++

#### Exercise 3: Substituting names

- RegExr
   - http://www.regexr.com
- Random name generator
   - http://bit.ly/1MLmknO

+++

#### Exercise 5: Reformatting dates

- RegExr
   - http://www.regexr.com
- Dates in American History
   - https://goo.gl/35lQXi

---

## Summing up

+++

### We have seen that…

- Regular expressions are a powerful means of matching patterns in text
- This is very useful for analysing and modifying unstructured text
- This is also useful in working with structured text, html, xml, csv…

+++

### Next steps

- Find out how to use regular expressions with your data
- Look out for regular expression options in your text editor's search and replace function
- Search the internet for "regular expressions cheat sheet" and grab a copy of one that you like

---

### Thank you for attending!

- Please complete our course survey: http://svy.mk/18c8dHa
- Get in contact with us if you have questions: [training@intersect.org.au](mailto:training@intersect.org.au)
- Join Intersect's Training mailing list for info on upcoming courses:
   - Send an email to [learn+subscribe@intersect.org.au](mailto:learn+subscribe@intersect.org.au)
