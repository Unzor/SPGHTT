# SPGHTT
A SPWN package manager written in SPWN.

# Usage
Run this:
```
spghtt
```
Then when prompted to, run "install", then run "hello_world".
Now, create a file named example.spwn, and put this code in:
```
let hworld = import "hello_world"
hworld()
```
Now run "spwn build example.spwn", and it should say "Hello World!"
