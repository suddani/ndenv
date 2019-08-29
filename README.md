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

# Usage

1. List available node version for install
   ~~~ sh
   $ ndenv ls
   ~~~
2. Install one of the versions, for example 10.16.3
   ~~~ sh
   $ ndenv install 10.16.3
   ~~~
3. List currently set node version and all installed.
   ~~~ sh
   $ ndenv
   Current: none
   v10.16.3-linux-x64
   ~~~
4. Activate a installed node version
   ~~~ sh
   $ ndenv v10.16.3-linux-x64
   Changing version to: v10.16.3-linux-x64
   ~~~
