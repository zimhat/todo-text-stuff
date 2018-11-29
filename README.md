# todo-text-stuff
Stuff I've written for my todo.txt setup.

Currently contains:

ice_recur : A recurring item generator for todo.txt.  Yes, there are like 14 of these, but I couldn't find a single one that could do "every 2 weeks", so I wrote my own.   REQUIREMENTS: Ruby ; gems: ice_cube, trollop, todotxt-rb
templated_checklists : A file to keep available copies of one-time checklists (i.e. "stuff to take when going swimming")

Tests:

Run ice_recur tests like this if you want pretty output and failure if you miss tests: prove --exec "./ice_recur --test" ice_recur
