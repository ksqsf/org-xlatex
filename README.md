# org-xlatex

This package provides instant latex preview for org buffers using xwidget and mathjax.

## Screencast

https://github.com/ksqsf/org-xlatex/assets/23358293/6518d97c-ecd7-40ed-9f5a-10093343a508

## Configuration

```elisp
(use-package org-xlatex
  :after (org)
  :hook (org-mode . org-xlatex-mode))
```
