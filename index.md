# First: Simple Prompt


<img src="https://i.ibb.co/CB6M30g/This-is-A-Screenshot-D-2022-01-09-kl-16-13-11.png" alt="First" border="0">

Code: (put in .zshrc)

```zsh
autoload -U colors && colors
NEWLINE=$'\n'
PROMPT="%F{blue}%n%f  %F{red}(%~)  %f%F{green}(%T)%f${NEWLINE}%F{red}-->%f "
