# goland-helpers

> this repertory lists the uses of goland so as not to forget 

## display and shortcut problems 


1. to solve the problem of replacing variables in fmt.Printf (%s, %v etc.) (example : `fmt.Sprintf("hello #{name}")` instead of `fmt.Sprintf("hello %s", name)` ([link reddit](https://www.reddit.com/r/golang/comments/elk9pp/goland_201931_formatting_changes_which_setting_to/))
    * `File` > `Settings` >  `Editor` > `General` > `Code Folding`
    * disable `format strings`  in Go parts
2. to solve the character replacement in shortcuts: ≠ instead of != 
    * `File` > `Settings` >  `Editor` > `Reader Mode`
    * disable `font ligatures`
