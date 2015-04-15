# Software Architecture Roadmap

## Final product

The goal is to create a multi-platform King of Tokyo clone.  There will be frontend clients for Android, iOS, and the web that are all interoperable.  The main backend will be a cloud service that permits players to asynchronously play against each other.  It will also be possible for one of the mobile apps to serve as its own backend, which would allow a group of players with the mobile app to play against each other synchronously over bluetooth.

## Milestones

These are still ill thought out, but here is the rough outline of a sketch of a plan:

  - Get just barely enough of a project up and running that multiple people can do work on it at the same time.
  - Complete a basic version of the game where essentially all of the logic is on the server.  There will be a web interface, but it will essentially be a web form that will present the current state of a game and accept moves.  There will be no asynchronous javascript communication with the server.
  - Create a web interface that can asynchronously commnicate with the server and generally act like a real web application instead of something from the late '90s.
