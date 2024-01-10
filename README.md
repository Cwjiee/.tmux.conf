1. To setup tmux config, clone the Tmux Plugin Manager repo
  ``git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm``

2. Then, copy the following code to your .tmux.conf file
   ```
   set -g @plugin 'tmux-plugins/tpm'
   set -g @plugin 'tmux-plugins/tmus-sensible'
      
   run '~/.tmux/plugins/tpm/tpm'
   ```
   
3. Add your plugins
   ```
   set -g @plugin 'catppuccin/tmux'
   ```
4. In your tmux session, press ``prefix + I``
<br>
  You are done with setting up tmux config!
