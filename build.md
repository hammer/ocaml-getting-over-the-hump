# OCaml Build Tools

* [findlib](http://projects.camlcity.org/projects/findlib.html)

## Project structure

* [Discussion on reddit](https://www.reddit.com/r/ocaml/comments/4scvlj/starting_a_new_project_what_is_current_best/)
* [dbuenzli/carcass](https://github.com/dbuenzli/carcass)
* [dbuenzli/topkg](https://github.com/dbuenzli/topkg)

## Documentation

* [codoc](https://github.com/dsheets/codoc)

## Build

* [solvuu/solvuu-build](https://github.com/solvuu/solvuu-build)
* [AbsInt/ocaml-buildutils](https://github.com/AbsInt/ocaml-buildutils)

## From Ashish

* **ocamlscript**: Use this for single file scripts.
* [oasis](https://github.com/ocaml/oasis): Good for small projects. You provide a high level description of your project, and oasis automatically generates a build script for you. It is widely used, but starts to fail on more complex projects.
  * [ocaml.org tutorial](https://ocaml.org/learn/tutorials/setting_up_with_oasis.html)
* **OMake**: It's been around for many years and is widely used on more complex projects. It is meant to mimic the syntax of Makefile's but is actually a full fledged programming language. It is very powerful, not too hard to use once you learn it, and has a comprehensive 200 page user manual. However, the syntax is awkward and often causes frustration. I recommend OMake only if you're getting frustrated by oasis.
* [ocamlbuild](http://projects.camlcity.org/projects/findlib.html): A lower-level build system. It is very powerful but has virtually no documentation. The chapter in the user manual isn't really sufficient to let you do much more than you can with oasis.
* **ocp-build**: A new build tool by OCamlPro. It hasn't been officially announced and is not used by many people. It's unclear if OCamlPro plans to push this as a well supported tool.
* **Jenga**: A new build tool by Jane Street. It hasn't been officially announced yet, but there will be a talk on it at the next OCaml Paris Meetup. Its design appears good, but there aren't many examples or documentation yet.
* [Assemblage](https://github.com/samoht/assemblage): what we want to use when it’s ready



