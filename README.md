# my oh-my-zsh config

1. Install oh-my-zsh:
  via curl

    `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
    
  via wget

    sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

2. Set up oh-my-zsh
    $ git clone git@github.com:qiu363/zsh.git
    $ cp zshrc ~/.zshrc

3. Install autojump
    $ git clone git://github.com/joelthelion/autojump.git 
    $ cd autojump
    $ ./install.py or ./uninstall.py

4. add incremental
    $ cd ~/.oh-my-zsh/plugins/
    $ mkdir incr
    $ cd incr
    $ wget http://mimosa-pudica.net/src/incr-0.2.zsh
    $ source incr*.zsh

