quickcards
==========

What is this quickcards repository you wonder? Why did I call it quickcards, and why did I choose to create a repository that seemingly has no code?

The term quickcards actually comes from an old piece of software called [Zoomracks] (http://en.wikipedia.org/wiki/Zoomracks). Zoomracks was a database management system for the Atari ST and IBM PC that represented data in a form that was visually represented by a filing card, known as "QUICKCARD"s.

Basically, what I want to do is write software that is as minimalistic as possible. I don't just want to go for elegance and readability: I want to go for code that is the absolute minimum in needs to be to "get stuff done".

Firstly, I want to look at a few things: I want to rewrite a kind of [Hypercard] (http://en.wikipedia.org/wiki/Hypercard) system in Python; I want it to be loosely based on the simplest [flat file database] (http://en.wikipedia.org/wiki/Flat_file_database) possible, loosely based also on the simplest blog platform possible, + loosely based on the simplest wiki implementation possible. All in Python.

The paradigm is inspired largely by the work of [Paul Otlet] (http://en.wikipedia.org/wiki/Paul_Otlet), with his Mundaneum + Universal Decimal Classification + Traité de Documentation, etc., as well as the work of [Herman Hollerith] (http://en.wikipedia.org/wiki/Herman_Hollerith) (i.e. the Art of Compiling Statistics, he developed a mechanical tabulator based on punched cards to rapidly tabulate statistics from millions of pieces of data, circa 1880s). Also a huge inspiration is the work of [Gina Trapani] (https://github.com/ginatrapani) (i.e. inventor of the [todo.txt 2.0 paradigm] (http://todotxt.com/)).

Basically, I want to write the simplest Python program possible to deal with .txt files at first, until I write the functions to store the contents of the "Cards" in lists and hash tables. I am using the metaphor of the Index Card. Basically, a Card is composed of a given number of lines of text. The lines of text are about entities, objects, and are references to other entities, objects. The Cards are hyperlinked and form a network-of-cards. That's how I am seeing it for now. More to come. Still in conceptual modeling phase.

The design philosophy is simple. Software is Text. There is little difference between a Python program written in the 21st century and a clay tablet made 5000 years ago. Both are Texts. In one case, one uses a stylus to make marks on the clay tablet. In the other, one uses a keyboard to input text into a text editor, displayed on a monitor, etc. The point is that both use character sets to make lines of text. One could imagine someone using clay tablets to write software; one would just need to scan the clay tablet and use Optical Character Recognition to make the content machine-readable. So basically I am reinventing the library card catalog, version 3.0, inspired by Herman Hollerich, Paul Otlet and Gina Trapani.