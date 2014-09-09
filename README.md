emacs-config
============

Configuration for emacs (sligthly modified)

Called by .emacs:

```elisp
(require 'org)
(org-babel-load-file "~/Private/ORG/avs-emacs.org")
(add-to-list 'load-path "/usr/local/Cellar/mu/HEAD/share/emacs/site-lisp/mu4e/")
(org-babel-load-file "~/Private/ORG/avs-mu4e.org")
```
