# Tmux Config

An easy tmux config for use on servers
rebinds ctrl + b -> ctrl + a and more

1. Clone the repo
   git clone https://github.com/Peteskiis/tmux-config

2. Rename Folder

```bash
mv tmux-config ~/.tmux
```

3. Move the config out

```bash
cd ~/.tmux

mv .tmux.conf ../
```

4. Start Tmux and source the new config file

```bash
tmux

tmux source ~/.tmux.conf
```

5. Install TPM and the plugins

```bash
crtl + a + I
```

6. Done! Enjoy
