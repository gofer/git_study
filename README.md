# Git Study
This is only my cheatsheet.

## Git push
    $ git add .
    $ git commit -m '[commit_message]'
    $ git push
<!-- -->

or

    $ git commit -a -m '[commit message]'
	$ git push
<!-- -->
(This commands are NOT available when added new files.)

## Git add/remove
    $ git add [file_name]
    $ git rm  [file_name]
<!-- -->

## Git pull
    $ git pull
<!-- -->

## Git clone
    $ git clone [repository_address]
<!-- -->

## Git create branch
    $ git branch [branch_name]
    $ git checkout [branch_name]
      :
      :
    $ git push -u origin [branch_name]
<!-- -->

## Git select working branch
    $ git checkout [branch_name]
<!-- -->

## Git merge branch
    $ git chekout [parent_branch]
    $ git merge [child_branch]
<!-- -->

## Git delete (local) branch
    $ git branch -d [branch_name]
<!-- -->

## Git delete (remote) branch
    $ git push origin :[branch_name]
<!-- -->
