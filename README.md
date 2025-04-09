# Tmux Config

An easy tmux config for use on servers
rebinds ctrl + b -> ctrl + a and more

1. Clone the repo

```bash
   git clone https://github.com/Peteskiis/tmux-config
```

2. Rename Folder and make sure it's in $HOME ~/.tmux

```bash
mv tmux-config ~/.tmux
```

3. Move the config out

```bash
cd ~/.tmux

mv .tmux.conf ../
```

4. Clone TPM

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

5. Start Tmux and source the new config file

```bash
tmux

tmux source ~/.tmux.conf
```

6. Install TPM and the plugins

```bash
crtl + a + I
```

Done! Enjoy
