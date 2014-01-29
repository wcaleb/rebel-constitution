rebel-constitution
==================

This repo was inspired by a [conversation on Twitter][] between
[YAppelbaum][], [JasonKuznicki][], [JKP_Discovery][], and [myself][]
about the best way to visualize changes made by the Confederate
Constitution to the United States Constitution.

You can get right to the point by looking at the [diffs page][] showing
the revisions made by the Confederates in their rebel Constitution.

My Method
---------

The source text for the two Constitution files comes from the [Avalon
Project edition of the U.S. Constitution][] and the [Avalon Project
edition of the Confederate Constitution][], with one exception. The
Confederate presidental oath is for some reason missing in the Avalon
edition, so I took that one section from the [WikiSource edition][].

First, I used [pandoc][] and (in the case of the U.S. Constitution) my
own [pandocket][] tool to grab the text from Avalon and convert the HTML
to markdown.

Next, I removed some of the extraneous cruft (menu sections, signatures
to the Confederate Constitution, and descriptive substitles given next
to the section numbers for the U.S. Constitution) so as to make the
similarities and dissimilarities in content more clearly stand out.

For the same reason, I also did some light editing of punctuation,
capitalization, and numbering and section-heading style to make them
more standard between the two documents. A few archaic spellings in the
U.S. Constitution (like "labour" and "judgement") were also modernized.

I was not scrupulously consistent in determining which source file to
tweak in order to eliminate these slight differences between the two
texts. I am also aware that differences that may seem insignificant to
me will seem significant to others (for example, the Avalon edition of
the Confederate Constitution sometimes capitalizes "States" and "State"
in places where its edition of the U.S. Constitution does not).

My decisions make this project an intepretive act. You are welcome to
inspect the changes more closely by looking at the commit histories for
the individual Constitution files, which show the initial text as I got
it from Avalon as well as the changes that I made.

Further Reading
---------------

This project can be seen, in some respects, as a more open (and perhaps
more geeky!) version of a similar [interactive feature][] created by the
*New York Times* as part of historian Stephanie McCurry's "Disunion"
post, "[The Rebel Constitution][]," published March 10, 2011.

I recommend that you read that post, drawn from McCurry's book
*Confederate Reckoning*, for a good discussion of the major changes and
their significance. But my other goal here is to let you explore the
differences yourself, without annotations or extensive interpretive
notes.

  [conversation on Twitter]: https://twitter.com/YAppelbaum/status/414582442167521280
  [YAppelbaum]: http://twitter.com/YAppelbaum
  [JasonKuznicki]: http://twitter.com/JasonKuznicki
  [JKP_Discovery]: http://twitter.com/JKP_Discovery
  [myself]: http://twitter.com/wcaleb
  [diffs page]: https://github.com/wcaleb/rebel-constitution/commit/03637b4a1b56185c185c87ddd98c59e5e183e72c#diff-1906bc26b552b77d6df2daa6cd3fa67eR548
  [Avalon Project edition of the U.S. Constitution]: http://avalon.law.yale.edu/18th_century/usconst.asp
  [Avalon Project edition of the Confederate Constitution]: http://avalon.law.yale.edu/19th_century/csa_csa.asp
  [WikiSource edition]: https://en.wikisource.org/wiki/Constitution_of_the_Confederate_States_of_America
  [pandoc]: http://johnmacfarlane.net/pandoc/index.html
  [pandocket]: https://github.com/wcaleb/pandocket
  [interactive feature]: http://www.nytimes.com/interactive/2011/03/11/opinion/20110311_Disunion_Confederate_Contitution.html
  [The Rebel Constitution]: http://opinionator.blogs.nytimes.com/2011/03/10/the-rebel-constitution/
