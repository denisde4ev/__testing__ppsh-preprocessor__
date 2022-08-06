# simple PreProcessor written in shell script
simple preprocessor written in shell script (test)

just tetsting some ideas (it might work tho..)


# Example usage:

``` sh
$ cd test
$ bat a.sh
     File: a.sh
   1 
   2 # init:
   3 #dumpvar a
   4 
   5 #define a
   6 # after def:
   7 #dumpvar a
   8 
   9 #undef a
  10 # after undef:
  11 #dumpvar a
$ ppsh a.sh | bat
     STDIN
   1 
   2 # init:
   3 a=0
   4 
   5 # after def:
   6 a=1
   7 
   8 # after undef:
   9 a=0
```
