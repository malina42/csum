P.S. DOn't use these. I have them as placeholders. I idntified last minutr 'regressions'
which are real, when dealing with small vs large files, many an few etc. findiing the right 
"scheduler" algorithm for all these cases in a 'default' runtime isn't entirely trivial 
(but has nothing to do with the hashing algorithms, themselves.

this one is a SLOW version I re-upped just due to leak. this one isn't even fast.


checksummer that goes vroom vroom.

b3,b3b,b3bp,sha256,sha512,sha3_224.

WIP so demo mode. but should be good enough for fun hashing ,)

forgot to add. csum.b3:


oops. hardcoded threads and when porting older work into this , I forgot to sort out a overlapping scheduler. 

Will re-up soon
tuned a bit , and now it's slower than bsum. sigh.

will figure out it back to normaml speed but I ned ot understand WHY it happens.. and I don't yet.
