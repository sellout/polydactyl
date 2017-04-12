# Polydactyl

A reimplementation of [Cats](https://github.com/typelevel/cats) taking advantage of `-Ykind-polymorphism`.

This currently requires dependent projects to be compiled with [Typelevel Scala](https://github.com/typelevel/scala) 2.12.1, since that is the first version of Scala that supports kind polymorphism and this exposes kind-polymorphic types.

The idea is that actual Cats could be entirely(?) implemented by specializing the kind-polymorphic types defined here.
