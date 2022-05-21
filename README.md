# SPGHTT
A SPWN package manager written in SPWN.

# Usage
First, add C:\Program Files (x86)\spghtt to your PATH in enviroment variables, then run this in CMD:
```
spghtt
```
Then when prompted to, run "install", then run "hello_world".
Now, create a file named example.spwn, and put this code in:
```
let hworld = import hello_world
hworld()
```
Now run "spwn build example.spwn -l", and it should say "Hello World!"

# Library Usage
#### note: the library was meant for use in [Ash](https://github.com/arc-spwn/ash)
```js
let SPGHTT = import spghtt
SPGHTT.action("install", "package_here")
// or
SPGHTT.action("publish", "package_dir_here", "package_name_here")
