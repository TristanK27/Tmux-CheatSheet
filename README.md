# Tmux-CheatSheet

A black and white, printer friendly, Tmux CheatSheet.

## Special notes
To enable vi mode-keys, do one of the following:
- <C-b>: setw -g mode-keys vi
- Append this to your tmux command `\; setw -g mode-keys vi`
  
  i.e. `tmux new-session -s tmux-cheatsheet \; setw -g mode-keys vi`
- Add `setw -g mode-keys vi` to your `.tmux.conf`

