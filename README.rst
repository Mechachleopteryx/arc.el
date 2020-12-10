arc.el
======
An Emacs mode for the `Arc <http://www.paulgraham.com/arc.html>`_ dialect of Lisp.

The code is from the `Arc wiki <https://sites.google.com/site/arclanguagewiki/getting-started/installing-emacs>`_, with modifications to support REPL interaction.

The REPL interaction code is adapted with minor modifications from similar functionality implemented in `racket-mode <https://github.com/greghendershott/racket-mode>`_.

Installation
============
This package is not on `MELPA <https://melpa.org/>`_ at the moment, but you could install it using `straight.el <https://github.com/raxod502/straight.el>`_:

.. code-block:: elisp

   (use-package arc
     :straight
     (arc
       :type git
       :host github
       :repo "countvajhula/arc.el")
     :config
     (setq arc-source-path "/path/to/arc/arc3.2")) ; change to your arc install location
  
