# fisher install 
curl -sL https://raw.githubusercontent.com/jorgebucaran/fisher/main/functions/fisher.fish | source && fisher install jorgebucaran/fisher

# theme install
fisher install IlanCosman/tide@v5

# fzf install
fisher install PatrickF1/fzf.fish
brew install fzf fd bat 

可得到下面功能
COMMAND            |  DEFAULT KEY SEQUENCE         |  CORRESPONDING OPTION
Search Directory   |  Ctrl+Alt+F (F for file)      |  --directory
Search Git Log     |  Ctrl+Alt+L (L for log)       |  --git_log
Search Git Status  |  Ctrl+Alt+S (S for status)    |  --git_status
Search History     |  Ctrl+R     (R for reverse)   |  --history
Search Processes   |  Ctrl+Alt+P (P for process)   |  --processes
Search Variables   |  Ctrl+V     (V for variable)  |  --variables

# export 方法
set --universal --export theme_nerd_fonts yes
set --universal --export theme_color_scheme zenburn
set --universal --export PROJECT_PATHS ~/Library/PROJECT_PATH

# alias 方法
alias nvim="CC=/usr/local/bin/gcc-13 nvim"

# export alias tool
bass
https://github.com/edc/bass
