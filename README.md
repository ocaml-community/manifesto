*Note that this README (the manifesto) is a work in progress and is meant to be
collaboratively improved. Please contribute!*

## What is OCaml-community?

OCaml-community is a GitHub organization dedicated to the
collaborative and community-driven long-term maintenance of OCaml
packages.

In other words, the organization provides a place to host open source
OCaml packages that benefit from collective maintanance.

Unmaintained packages that are of significant interest can be adopted
by ocaml-community. Maintenance then performed collaboratively by the
community. An official maintainer will be assigned to individual
packages to make decisions about pull requests where possible.

At minimum, maintenance consists of updating software to keep it
working over time, as well as maintaining the corresponding OPAM
package. It also includes adding needed features, refactoring code,
adding and improving documentation, improving the style of the code,
adding tests, _etc_.

Changes made during maintenance should take into account the needs of
the existing user community, including the need for backward compatibility.

## Who runs this github organization?

This organization is run by
[volunteers](https://github.com/orgs/ocaml-community/people) from the OCaml
community. Everyone is welcome (you don't need to be a very
experienced OCaml programmer to participate).

## FAQ

- **Why the name ocaml-community?**

  The ocaml-community organization takes its inspiration from the similar-named
  [elm-community](https://github.com/elm-community) and
  [coq-community](https://github.com/coq-community) projects.

- **What is the difference between this and the ocaml organization's repositories?**

  The official ocaml organization is for maintaining the OCaml
  compiler itself, OPAM, odoc, and other key infrastructural
  software. The ocaml-community GitHub organization is for adopting
  and maintaining packages that are of widespread use but might lack
  active maintainers.

- **How can I propose adopting a package?**

  Open an issue on the "manifesto" repository explaining what the
  project is, where it is currently hosted (if anywhere), and what
  efforts you have made to contact the existing maintainers to make
  sure they do not intend to continue maintenance.

- **Can I propose a project I wrote?**

  Yes, you can propose a project you wrote, as a way of
  preparing to pass on the maintenance to other community members.

- **How can I propose changes to a package, or to community documentation like this very file?**

  Simply make a pull request. You can also open an issue requesting
  commit access.

- **Will all projects in ocaml-community have some Continuous Integration (CI) setup?**

  CI and automated testing is important for keeping code well
  maintained. Our goal is to eventually have an CI system, but we
  don't have one yet. You can volunteer to help with that!
