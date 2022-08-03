Boilerplate file for `~/.zshrc`

# ----------------------
# Python Aliases
# ----------------------
alias python="python3"

# ----------------------
# Bash Aliases
# ----------------------
alias vrc="vi ~/.zshrc"
alias src="source ~/.zshrc"
alias snowsql=/Applications/SnowSQL.app/Contents/MacOS/snowsql

# ----------------------
# Database Aliases
# ----------------------
alias pg_master="psql -h host -p 5432 -d database_name -U username"

# ----------------------
# Path Aliases
# ----------------------
alias devpath="cd ~/Repos/data"
alias dbtpath="cd ~/path/to/dbt"
alias orchpath="cd ~/path/to/orchestrator"

# ----------------------
# Dagster Aliases
# ----------------------
alias dagster_scheduler="export DAGSTER_HOME=~"/dagster_home" && dagster-daemon run"
alias dg="export DAGSTER_HOME=~"/dagster_home" && dagit"

# ----------------------
# Airbyte Aliases
# ----------------------
alias airbyte="ssh -i ~/.ssh/path_to.pem -L 8000:localhost:8000 -N -f airbyte_host"

# ----------------------
# dbt Aliases
# ----------------------
alias dbt test="dbt test --store-failures"

# ----------------------
# Git Aliases
# ----------------------
alias ga='git add'
alias gaa='git add .'
alias gaaa='git add --all'
alias gau='git add --update'
alias gb='git branch'
alias gbd='git branch --delete '
alias gc='git commit'
alias gcm='git commit --message'
alias gcf='git commit --fixup'
alias gcof='git checkout --'
alias gco='git checkout'
alias gcob='git checkout -b'
alias gcom='git checkout main'
alias gcos='git checkout staging'
alias gcod='git checkout develop'
alias gd='git diff'
alias gda='git diff HEAD'
alias gi='git init'
alias glg='git log --graph --oneline --decorate --all'
alias gld='git log --pretty=format:"%h %ad %s" --date=short --all'
alias gm='git merge --no-ff'
alias gma='git merge --abort'
alias gmc='git merge --continue'
alias gmm='git merge main'
alias gp='git pull'
alias gpr='git pull --rebase'
alias gr='git rebase'
alias gs='git status'
alias gss='git status --short'
alias gst='git stash'
alias gsta='git stash apply'
alias gstd='git stash drop'
alias gstl='git stash list'
alias gstp='git stash pop'
alias gsts='git stash save'

# ----------------------
# Git Functions
# ----------------------
# Git log find by commit message
function glf() { git log --all --grep="$1"; }
