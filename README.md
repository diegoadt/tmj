#### Install
## IT DOES NOT WORK WITH RVM, YOU NEED TO INSTALL RBENV
- install tmux ( $ sudo apt-get install tmux )
- copy .tmux.conf to $HOME
- edit "scriptpath"/tmj and change JERICO_ROOT_DIR and JIS_ROOT_DIR to our real path
- create symbolic link ( $ sudo ln -s "scriptpath"/tmj /bin/tmj )

#### How to use
- run ( $ tmj )
- every command init by `ctrl+a`
After this:

1..4: switch window (src, pry-...)

b: "minimize" tmj

arrows (<-; ->..): switch panel

?: show help
