## Tmuxinator configs (Ubuntu/macOS)

To install:
```bash
$ cd ~/Projects
$ git clone https://github.com/Marian-13/tmaxinator_configs.git
$ cd tmaxinator_configs
$ git config user.name "Marian-13"
$ git config user.email "Marian144519@gmail.com"
$ mkdir ~/.config
$ mkdir ~/.config/tmuxinator
$ cp bitrep.yml ~/.config/tmuxinator/bitrep.yml
```

To pull (update local version):
```
$ cd ~/Projects/tmaxinator_configs
$ git pull
$ cp ~/.config/tmuxinator/bitrep.yml bitrep.yml
```

To push (update remote version):
```
$ cd ~/Projects/tmaxinator_configs
$ cp ~/.config/tmuxinator/bitrep.yml bitrep.yml
$ git add .
$ git push origin master
```
