# Terminal Tips


| command | description |
| ------- | ----------- |
| git diff --numstat      | get just the numbers of lines changed for each file (removed | added | filename) |
| wc      | word count (-l is line count) |
| cat     | prints the contents of a file as standard output |
| head    | read the first few lines of a file |
| tail    | read the last few lines of a file |
| grep    | searches for a pattern in a file
| sed     | finds/replaces a pattern in a file
| awk     | finds and manipulates patterns in a file
| tee     | prints input to terminal and files
| man     | shows a command's manual (e.g. `man sudo`)
| cal     | displays a calendar in terminal


## Examples
Count number of changed lines in a file
`git status | grep 'modified:' | wc -l`

### tee
command | tee file1


## Vim

| mode    |command | description |
| ------- | ------ | ----------- |
| command | $      | move cursor to end of line |
| command | ^      | move cursor to the start of line |
| command | :set number | adds line numbers |
| command | dd | deletes a line |
| command | 3dd | deletes 3 lines |
| command | u | undo |
| command | ctr+r | redo |
| command | /<search-string> | search (n to go to next match. N to go to previous) |
| command | %s/<text-to-replace>/<replacing-text>/gc | find+replace. 'g' is global change. 'c' is ask to confirm
