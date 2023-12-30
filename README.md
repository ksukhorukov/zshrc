# .ZSHRC

My own Z-Shell Profile Configuraion File

````
user@air zshrc$ cat README.md 
user@air zshrc$  cat ~/.zshrc
PROMPT='%n@%m %1~$ '
# Add RVM to PATH for scripting. Make sure this is the last PATH variable change.
cd /Users/user/Desktop/Data

export LDFLAGS="-L/opt/homebrew/opt/libffi/lib"
export CPPFLAGS="-I/opt/homebrew/opt/libffi/include"
export PKG_CONFIG_PATH="/opt/homebrew/opt/libffi/lib/pkgconfig"

alias varnish="echo > ~/.zsh_history && kill -9 $$"
alias updatedv="sudo /usr/libexec/locate.updatedb"
alias zz="ls -la"
alias unbr="unbroot | head -n 10 | tail -n 10 | head -n 1"
alias gpush="git push"
alias gstat="git status"
alias workspace="cd ~/workspace"
export EDITOR="subl"
export PATH="$PATH:$HOME/.rvm/bin"
export PATH="$PATH:/Applications/Sublime Text.app/Contents/SharedSupport/bin"
export PATH="$PATH:$HOME/updatedb"
export PATH="$PATH:$HOME/workspace/collage"

export RUBY_CONFIGURE_OPTS="--with-openssl-dir=$(brew --prefix openssl@3)"
export PATH="$PATH:/Users/user/workspace/sotd/"
sotd

PATH="$PATH:/Users/user/workspace/unbroot"
````

# [EOF]
