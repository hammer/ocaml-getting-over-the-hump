# IDE

* [ocaml-user-setup](https://github.com/OCamlPro/opam-user-setup)

## Emacs
### [Tuareg](https://github.com/ocaml/tuareg)
* `(setq tuareg-font-lock-symbols t)` to get `'a` to display as `α`

### [ocp-indent](https://github.com/OCamlPro/ocp-indent)

### [Merlin](https://github.com/the-lambda-church/merlin)
* `M-<tab>` for autocomplete
* `C-c C-t` for type of variable under cursor
* `C-c C-u` to refresh
* [Configuration with `.merlin`](https://github.com/the-lambda-church/merlin/wiki/project-configuration)
  * `PKG ...`

### [utop](https://github.com/diml/utop)
```
(autoload 'utop-setup-ocaml-buffer "utop" "Toplevel for OCaml" t)
(add-hook 'tuareg-mode-hook 'utop-setup-ocaml-buffer)
(add-hook 'typerex-mode-hook 'utop-setup-ocaml-buffer)
```
* http://mads-hartmann.com/ocaml/2014/01/05/using-utop-in-emacs.html