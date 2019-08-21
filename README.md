# Install

1. Clone ndenv int ```~/.ndenv```
    ~~~ sh
    $ git clone git@github.com:suddani/ndenv.git .ndenv
    ~~~

2. Add ~/.ndenv/bin to your $PATH for access to the ndenv command-line utility.

  * For bash:
    ~~~ sh
    $ echo 'export PATH="$HOME/.ndenv/bin:node_modules/.bin:$HOME/.ndenv/current_node_version/bin:$PATH"' >> ~/.bash_profile
    ~~~
  * For Ubuntu Desktop:
    ~~~ sh
    $ echo 'export PATH="$HOME/.ndenv/bin:node_modules/.bin:$HOME/.ndenv/current_node_version/bin:$PATH"' >> ~/.bashrc
    ~~~
  * For Zsh:
    ~~~ sh
    $ echo 'export PATH="$HOME/.ndenv/bin:node_modules/.bin:$HOME/.ndenv/current_node_version/bin:$PATH"' >> ~/.zshrc
    ~~~
  * For Fish shell:
    ~~~ sh
    $ set -Ux fish_user_paths $HOME/.ndenv/bin $fish_user_paths
    $ set -Ux fish_user_paths $HOME/.ndenv/current_node_version/bin $fish_user_paths
    $ set -Ux fish_user_paths node_modules/.bin $fish_user_paths
    ~~~
