---
layout: post
title:  Beginning Elm
---

I recently stumbled upon [Elm](http://elm-lang.org/), a functional reactive programming. I literally spent evenings and nights for
the next 2 weeks pouring over tutorials and videos learning Elm.

I found these resources really helpful:
   * [Building Web Apps with Elm](https://pragmaticstudio.com/elm)
   * [The Elm Architecture (aka TEA)](https://guide.elm-lang.org/architecture/)
   * [Elm Seeds](https://elmseeds.thaterikperson.com/)
 
I ported over a search widget to Elm (from KnockoutJS) and that helped cement much of what I learned. The backend is written in [Mojolicious](http://mojolicious.org/).
I even published my first CPAN module , [Mojolicious::Plugin::AssetPack::Pipe::ElmLang](http://search.cpan.org/~csandeep/Mojolicious-Plugin-AssetPack-Pipe-ElmLang-0.4/lib/Mojolicious/Plugin/AssetPack/Pipe/ElmLang.pm) -
a pipeline to compile Elm source files into Javascript!

The journey so far has been smooth sailing and Im really enjoying learning
