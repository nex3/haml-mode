# Haml-mode for Emacs

Emacs got its Haml mode. 

## Installation

Download the haml-mode.el in your .emacs.d/ directory.

Add this line to your .emacs file:
    
    (require 'haml-mode)

And for an automatic new line with auto indentation, just add:

    (add-hook 'haml-mode-hook
      (lambda ()
        (setq indent-tabs-mode nil)
        (define-key haml-mode-map "\C-m" 'newline-and-indent)))
