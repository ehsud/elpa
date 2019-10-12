Emacs common function library

## How can I configure to use it?

1. The base configuration looks like this

    (require 'common)

2. Then just bind them to the key button you like

    (global-set-key (kbd "C-j") 'copy-current-line)
    (global-set-key (kbd "M-p") 'move-line-up)
    (global-set-key (kbd "M-n") 'move-line-down)

3. Start having fun ...