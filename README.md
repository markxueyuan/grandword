# grandword

A Clojure written tool for building English vocabulary.

The dictionary part is a wrapper of Wordnet.

## Usage

query a new word in the dictionary:

(? newword)

add a word to wordlist as a new word:

($ newword)

add a word to wordlist as a familiar word:

(! newword)

change the mode of a word in the wordlist(from new to familiar or from familiar to new):

(% newword)

sift a document to get all the new words in the wordlist:

(& "D:/data/article.txt")
(& "http://nytimes.com")


## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
