# SIA_X
## Documentations and Howtos collection



## Linux stuff


- run tmux on interactive shell 
'''
if command -v tmux &> /dev/null && [ -n "$PS1" ] && [[ ! "$TERM" =~ screen ]] && [[ ! "$TERM" =~ tmux ]] && [ -z "$TMUX" ]; then
  exec tmux
fi
'''
