# gig

gig is help you create `.gitignore` files for your git repository.

## contrib
* [Git bash extension - git ignore](https://github.com/hackrslab/gig/tree/master/contrib/git-bash-ext)

## install

```
$ npm install -g gig
```

## update

```
$ npm update -g gig
```

## uasge

### generate .gitignore file

generate `.gitignore` file for your git repository

```
// If aleady `.gitignore` file exists, append  conditions to `.gitignore` file.
$ gig gen java intellij sublimetext  

// If do you want to overrride `.gitignore` file, usable to options : --override (shortcut : -o) 
$ gig gen -o java intellij sublimetest 

```

### packaging template

pkg command is usable to create custom template. 

```
// If aleady 'mypakage' file exists, append conditions to 'mypakage' file.
$ gig pkg -name 'mypakage' java intellij sublimetext  

// if do you want to override `mypakage` file,usable to options : --override (shortcut : -o) 
$ gig pkg -name 'mypakage' -o java intellij sublimetext  

$ gig show mypakage
*.class

# Package Files #
*.jar
*.war
*.ear

intellij :
*.iml
*.ipr
*.iws
.idea/

sublimetext :
# SublimeText project files
*.sublime-workspace
```

### Display ignore conditions.

```
$ gig show java intellij sublimetext  
```

### More Infomations

```
$ gig --help
```

# gitignore template files source by 

[GitHub gitignore repository](https://github.com/github/gitignore)

# ChangeLog

[See the ChangeLog](https://github.com/hackrslab/gig/tree/master/ChangeLog)

# LICENCE

## MIT LICENSE

The MIT License

Copyright (c) 2013 The gig Authors

See the [LICENSE](https://github.com/hackrslab/gig/tree/master/LICENSE) file for details. 

