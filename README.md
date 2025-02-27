Just place .tmux.conf in ~/

Tmux should auto load the config for new sessions

- For running sessions: press Ctrl+B and then ':'
  - input: 'source-file ~/.tmux.conf'
- From a shell
  - $ tmux source-file ~/.tmux.conf

<code>cd ~ && curl -O https://raw.githubusercontent.com/frankjannis/tmux.conf/refs/heads/main/.tmux.conf && tmux source-file ~/.tmux.conf</code>
