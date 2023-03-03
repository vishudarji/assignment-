# assignment-
assignment 1
admin@ADMIN MINGW64 ~
$ cd documents

admin@ADMIN MINGW64 ~/documents
$ mkdir shopping

admin@ADMIN MINGW64 ~/documents
$ git init shopping
Initialized empty Git repository in C:/Users/admin/Documents/shopping/.git/

admin@ADMIN MINGW64 ~/documents
$ cd shopping

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ touch yard.txt

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ touch groceries.txt

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git add .

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git commit -m 'create yard and groceries lists'
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'admin@ADMIN.(none)')

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ ^C

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git config -- user.email "vishwadarji2412@gmail.com"

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ gti config -- user.name "vishwa"
bash: gti: command not found

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git config -- user.name "vishwa"

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git commit -m 'create yard and groceries lists'
[master (root-commit) db7d592] create yard and groceries lists
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 groceries.txt
 create mode 100644 yard.txt

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git add groceries.txt

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git commit -m 'add ingredients for tomato soup'
[master b1848dd] add ingredients for tomato soup
 1 file changed, 3 insertions(+)

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git add yard.txt

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git commit -m 'add items needed for garden box'
[master 2c56781] add items needed for garden box
 1 file changed, 2 insertions(+)

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git add .

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git commit -m 'add items needed to grow potatoes'
[master 7d25dc7] add items needed to grow potatoes
 2 files changed, 2 insertions(+), 1 deletion(-)

admin@ADMIN MINGW64 ~/documents/shopping (master)
$ git log
commit 7d25dc7163ed45a0b0191aa8246eae973c2f0989 (HEAD -> master)
Author: vishwa <vishwadarji2412@gmail.com>
Date:   Fri Mar 3 23:33:10 2023 +0530

    add items needed to grow potatoes

commit 2c56781c308b39804b55cc96a177cc40648fe220
Author: vishwa <vishwadarji2412@gmail.com>
Date:   Fri Mar 3 23:30:31 2023 +0530

    add items needed for garden box

commit b1848ddf1387c166502e4f9853f7a954a10eff67
Author: vishwa <vishwadarji2412@gmail.com>
Date:   Fri Mar 3 23:29:10 2023 +0530

    add ingredients for tomato soup

commit db7d592e073ba55ed1ee86af0379ec54fa77e664
Author: vishwa <vishwadarji2412@gmail.com>
Date:   Fri Mar 3 23:25:18 2023 +0530

    create yard and groceries lists

admin@ADMIN MINGW64 ~/documents/shopping (master)
$
