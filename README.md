# PHASE live-coding session

Chat server using WebSockets and [http4s](https://http4s.org/). Similar to [http4s-chatserver][http4s-chatserver], but not as full-featured.

This repository was created to support a live-coding presentation:

* [Event Listing][meetup]
* [Session Recording][video]

## Folder Structure

/chat folder initialized via:

```bash
sbt -sbt-version 1.2.8 new http4s/http4s.g8 -b 0.20
```

/static folder copied from [https://github.com/MartinSnyder/http4s-chatserver/tree/master/static](https://github.com/MartinSnyder/http4s-chatserver/tree/master/static)

## Links

* [http4s][http4s]
* [http4s-chatserver][http4s-chatserver]

[http4s]: https://http4s.org/
[http4s-chatserver]: https://github.com/MartinSnyder/http4s-chatserver
[meetup]: https://www.meetup.com/scala-phase/events/259959798/
[video]: https://www.youtube.com/watch?v=py_V_7gD5WU
