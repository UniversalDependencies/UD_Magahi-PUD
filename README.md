# Summary

This is a part of the Parallel Universal Dependencies (PUD) treebanks originally created
for the [CoNLL 2017 shared task on Multilingual Parsing from Raw Text to
Universal Dependencies](http://universaldependencies.org/conll17/).


# Introduction

There are
1000 sentences in each language, always in the same order. (The sentence
alignment is 1-1 but occasionally a sentence-level segment actually consists
of two real sentences.) The sentences are taken from the news domain (sentence
id starts in ‘n’) and from Wikipedia (sentence id starts with ‘w’). There are
usually only a few sentences from each document, selected randomly, not
necessarily adjacent. The digits on the second and third position in the
sentence ids encode the original language of the sentence. The first 750
sentences are originally English (01). The remaining 250 sentences are
originally German (02), French (03), Italian (04) or Spanish (05) and they
were translated to other languages via English.

Magahi was not included in the original PUD collection for CoNLL 2017.
It was added in 2021.

The entire treebank is labeled as test set (and was used for testing in the
shared task). If it is used for training in future research, the users should
employ ten-fold cross-validation.


# Acknowledgments

...

## References

* (citation)


# Changelog

* 2021-11-15 v2.9
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.9
License: CC BY-SA 4.0
Includes text: yes
Genre: news wiki
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Alok, Deepak; Ojha, Atul Kr.
Contributing: here
Contact: panlingua@outlook.com, shashwatup9k@gmail.com
===============================================================================
</pre>
