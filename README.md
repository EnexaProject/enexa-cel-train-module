* Class Expression Learning module for ENEXA
** Build
Build the [[https://github.com/EnexaProject/enexa-utils][enexa-utils]] Docker image first, then:
#+begin_src shell :results output silent
make build
#+end_src

** Test
Setup the test environment from [[https://github.com/EnexaProject/enexa-utils][enexa-utils]] first, then:
#+begin_src shell :results output silent
make test
#+end_src

** Developer information
- ~Dockerfile~ :: A Dockerfile for the Docker image of this module.
- ~module~ :: A main module script to translate the input and output parameters between ENEXA and the application.

** Links
- [[https://github.com/dice-group/dice-embeddings][DICE Embeddings]]
