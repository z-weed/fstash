# Stashf

## Why

Sharing a function that I wrote to automate finding a file in a git stash.

## Usage

Given you've cloned and sourced the function in the file:

```
# For a file that is present
 
$ search_stash accounts_controller_spec
Your file was found in stash number: 2
 
# For non-present files
 
$ search_stash acro
We were unable to find the specified file
 ```

