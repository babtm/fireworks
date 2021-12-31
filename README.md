# fireworks [![demo badge](https://img.shields.io/badge/fireworks-demo-yellow)][live demo] [![Twitter Follow](https://img.shields.io/twitter/follow/creativemaybeno?label=Follow&style=social)](https://twitter.com/creativemaybeno)

Interactive app(s) for showing fireworks using [Flutter]'s canvas.

[<img width="1668" src="https://user-images.githubusercontent.com/19204050/147835938-4c33cf28-fe9b-43df-8e3c-40cdffe4601e.png">][live demo]

## Repo structure

To allow for both the [live demo] and counter app using the same code for rendering the actual
fireworks, the repo contains the following packages:

* [`fireworks`][fireworks], which is a basic Flutter **package** that contains a
  [render object and widget](https://youtu.be/HqXNGawzSbY) for rendering the fireworks. It also
  contains a controller class that manages the rockets, explosion particles, vsync, etc.
* [`fireworks_demo`][fireworks_demo], which is the app that is used for the [live demo].
* [`fireworks_counter`][fireworks_counter], which is a slightly modified version of the Flutter
  template app using the `fireworks` package. 

## Live demo

You can view a [live demo] of the `fireworks` package in action that allows you to both watch the
fireworks and launch your own firework rockets by hovering with the mouse :)

[![](https://user-images.githubusercontent.com/19204050/147836016-cc317dd6-e428-438f-b7d1-b9dd90253472.png)][live demo]


You can [checkout the tweet](https://twitter.com/creativemaybeno/status/1344848563264770048?s=20)
I made about it. 

## Counter app

For the Flutter counter challenge, I took the template app that is generated by `flutter create`
and modified just a few lines of code to add the fireworks to it :)

![](https://i.ibb.co/5MtbFRc/Screen-Shot-2021-01-02-at-1-43-11-AM.png)

Because I had already implemented the `fireworks` package in an abstract way before, I was able
to simply drop the widget and the controller into the counter app and transform it in a matter of
minutes.  
You can also [checkout the tweet](https://twitter.com/creativemaybeno/status/1345338801867157504?s=20) for this one.

[Flutter]: https://github.com/flutter/flutter
[live demo]: https://fireworks.creativemaybeno.dev
[fireworks]: https://github.com/creativecreatorormaybenot/fireworks/tree/main/fireworks
[fireworks_demo]: https://github.com/creativecreatorormaybenot/fireworks/tree/main/fireworks_demo
[fireworks_counter]: https://github.com/creativecreatorormaybenot/fireworks/tree/main/fireworks_counter
