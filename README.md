# Networking deepdive—From net.Dial to gRPC

Event: FOSDEM 2018 [Go devroom](https://fosdem.org/2018/schedule/event/networking/).

Many of my [code examples](code/) are based on [Network Programming with Go by Jan Newmarch](http://tumregels.github.io/Network-Programming-with-Go/) and you can also check out the [commands](commands.md) I use.

## Basics

We start off with a review of the stdlib net package and its sub-packages, walk through common use cases, patterns and challenges:

- Discussion of net and sub-packages (main types, interfaces, understanding what is available)
- Socket-level programming
- Timeouts, retries
- Security
- DNS

## Best practices

In the second part we focus on best practices using the stdlib and community-provided frameworks for networking:

- Best practices writing networked applications
- Review of non-stdlib packages useful for networking: golang.org/x/net/websocket, gorilla/websocket, gRPC
