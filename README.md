# Personal public dot files

## Vim

### I'am Using NVIM

### install
- brew install fzf
- brew install ripgrep

### Common :
- OPEN FILE => `:open <filename>`
- UNDO => `:u`
- REDO => `:redo`
- REDO => `ctrl + r`

- NO WRAP => `:set nowrap`
- WRAP => `:set wrap`

- COPY => `yyy`
- PASTE => `command + v`
- DELTE ONE LINE => `dd`
- NERDTREE => `ctrl + kk`
- FUZZYSEARCH => `ctrl + p`

- OPEN FILE IN SPLIT PANEL
    - vertical => `:vsplit`
    - horizontal => `:split`
- MOVE TO PANEL => `ctrl + j k l h`

- SPLIT TERMINAL BOTTOM => `:vsplit term://zsh`


- RUN PRETIER => `:Prettier`

- ENABLE DISABLE COC PLUGINS => `:CocList extensions`

- GOTO END OF FILE => `G`
- GOTO TOP OF FILE => `:1`
- GOTO SPESIFIC LINE => `:<line_number>`


- SEARCH IN FILE => `:Rg <text>`
- SEARCH IN MULTIPLE FILE => `:Rg <text>`
- Search file => `ctrl + f`
- SEARCH IN BUFFER => 

- REPLACE ALL => 
    - `:Rg <text>` => will open window fzf
    - select with tab and enter to open buffer
    - on buffer run => `:cfdo %s/<find>/<replace>/g`
  
  
  
### SAVE SESSION :
- `:SaveSeesion`
- Manualy restore => `:RestoreSession`
  
### WRITE QUIT :
WRITE => `:w`
WRITE THEN QUIT => `:qw`
QUIT => `:q`
FORCE QUIT `:q!`
SAVE ALL => `:wa`



### GIT :
- fix conflict
- git blame


### GOTO DEFINITION :
- php => `<leader> phpdf`
- go => `:DoDef`




## Other replace method :
- `:s#pat/tern#replace#g` - Use another character as separator to match "pat/tern"
- `:s/pat\/tern/replace/g` - Escape the / to match "pat/tern"
- next occur `n`
