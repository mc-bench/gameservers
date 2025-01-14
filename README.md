# Gameservers

This repo exists to build and push game server docker images to the private registry.

Each game server is managed on a branch per game-version.

For example, the branch minecraft-1.21.4 contains the minecraft 1.21.4 server.

To build and push a new version, create a new branch with the name of the game-version and push it to the repo.

The build will be triggered automatically.
