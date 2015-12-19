# Vim as IDE Replacement

This repository is going to serve as a checklist of the features I expect to add to Vim through plugins to provide an IDE like experience in order for me to be able to be comfortable developing in vim alone.

- [ ] Load plugins for specific languages lazily

##PHP Development

I use PHPStorm as my primary IDE for PHP development.  The following PHPStorm features are what I would consider essential for my current PHP development and what I want to emulate in vim.

Features
- [x] Access PHP documentation
  - Install [pman](http://php.net/download-docs.php) with pear
    - Setup in vim to use "K" binding to find
- [x] Jumping from files
  - [ctrlp.vim](https://github.com/kien/ctrlp.vim)
- [ ] Creating code snippets with placeholders
- [ ] Multiple tabs for files
- [x] Multiple windows for files
  - Vim's native windows
- [x] Jumping to any method / property in a given class
  - [x] Ctags
  - [ ] Automatically update tag file
- [ ] Limited global search
- [x] Linting
  - [Syntastic](https://github.com/scrooloose/syntastic) with `php`
    - Problem - Linting does not check if class names are correct.
      - [ ] Resolved?
- [ ] Autocompletion
- [ ] Creating files
- [ ] Renaming files
- [ ] Search for all occurrences of a symbol
- [ ] Search for all TODO comments
- [ ] Running tests (Currently done from the command line but make it so it does not interrupt the vim workflow)
  - [ ] Tmux

##C/C++ Development

To be added.

##Javascript Development
- [x] Linting with JSLint by [Syntastic](https://github.com/scrooloose/syntastic)
To be added.

##Java Development

To be added.

##Python Development
- [x] Linting
  - [Syntastic](https://github.com/scrooloose/syntastic) with "enter linter name"
- [ ] Smart autocompletion
To be added.

##iOS Development (Obj-c and Swift)

See if this is realistic.
