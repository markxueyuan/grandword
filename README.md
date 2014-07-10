# grandword

A Clojure written tool for building English vocabulary.

The dictionary part is a wrapper of Wordnet.

## Usage


### Make your dictionary ready

lein repl

(use 'grandword.vocabulary)


### Basic Operation

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

### For better experience

To simplify the operation, you can choose to load the dictionary first:

(load-dic)

Then you can discard the (annoying) braces in your operation:

query a new word in the dictionary:

? newword

or

newword

add a word to wordlist as a new word:

$ newword

add a word to wordlist as a familiar word:

! newword

change the mode of a word in the wordlist(from new to familiar or from familiar to new):

% newword

sift a document to get all the new words in the wordlist:

& "D:/data/article.txt"
& "http://nytimes.com"


## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
