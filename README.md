Working directory for practicing Russian language & Cyrillic typing with quail keyboard.

Note to self:

C-\ --> enable/disable use of selected input method (toggle-input-method)

C-h C-\ _method_ RET --> describe input method _method_ (descibe-input-method)

You can use the command M-x quail-show-key to show what key (or key sequence) to type in order to input the character following point, using the selected keyboard layout. The command C-u C-x = also shows that information, in addition to other information about the character.


Oh yeah! Also, I almost forgot that I specified keyboard commands in .emacs.d/lisp/init-fonts.el ...

(global-set-key (kbd "C-c d") 'default-input-font)
(global-set-key (kbd "C-c r") 'russian-input-font)
