### Github Markdown Relative Links Cheat Sheet
you can use it in any *.md file within Github

it's **RELATIVE** links so it'll be valid in all forks of your project



#### the project's [root](/../../)

`[root](/../../)` *(default branch)*
 
#### the [current](./) folder

`[current](./)` *(exept root folder)*

#### a file in the current folder [current/readme.md](./readme.md)

`[current/readme.md](./readme.md)`

#### another brunch [test](/../../tree/test)

`[test](/../../tree/test)`

#### open in editor [doc/readme.md](/../../edit/master/doc/readme.md)

`[doc/readme.md](/../../edit/master/doc/readme.md)`

#### view history of [doc/readme.md](/../../commits/master/doc/readme.md) 

`[doc/readme.md](/../../commits/master/doc/readme.md)`

#### delete(!) [doc/readme.md](/../../delete/master/doc/readme.md)

`[doc/readme.md](/../../delete/master/doc/readme.md)` *(it will offer to create a commit to delete file)*

#### blame mode [doc/readme.md](/../../blame/master/doc/readme.md)

`[doc/readme.md](/../../blame/master/doc/readme.md)`

#### raw file [doc/readme.md](/../../raw/master/doc/readme.md) 

`[doc/readme.md](/../../raw/master/doc/readme.md) ` *(you'll be redirected to raw.githubusercontent.com/...)*

#### new file in [doc/](/../../new/master/doc/) 

`[doc/](/../../new/master/doc/) `

#### new file in [doc/newSubFolder](/../../new/master/doc/newSubFolder) 

`[doc/newSubFolder](/../../new/master/doc/newSubFolder) `

#### ask to upload to [doc/](/../../upload/master/doc/) 

`[doc/](/../../upload/master/doc/)`

#### find file in specific brunch [find](/../../find/test)

`[find](/../../find/test)`

>instead of `master` you can specify another branch name `/../../upload/new_brunch/doc/`, but be carefull - it's not relative!



>in issues you may use this links such way: `(../upload/master/doc/)`

