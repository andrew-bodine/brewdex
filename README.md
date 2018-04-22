![Brewdex Logo](https://docs.google.com/drawings/d/e/2PACX-1vSjF-DewE4wMoXEHVnA5Xpw-UjVgLGihSMsz-8bPnNY43XZ4Y1ssdioZLaq-HEBZhBUJ4N8ycczV8Cr/pub?w=214&h=237)

# Brewdex

Beerdex aims to bring machine learning algorithms to the hunt for epic brews
around the world. By recommending geo-based brew itineraries to users based
on their personal preferences, Beerdex answers the question of where to go
next.

## Design

### Goals

Predict which brews a user will enjoy the most, that are nearby to the user,
and recommend itineraries that suit their preferences.

Itineraries can include multiple persons, and can be weighted evenly, or more
heavily to a particular style for example.

### Microservices

| Name | Status | Link |
| --- | --- | --- |
| ui | ![TravisCI Status](#) | [GitHub repo](https://github.com/acbodine/brewdex-ui) |
| crawler | ![TravisCI Status](#) | [GitHub repo](https://github.com/acbodine/brewdex-crawler) |
| learning | ![TravisCI Status](#) | [GitHub repo](https://github.com/acbodine/brewdex-learning) |

### Architecture

![Brewdex Architecture](https://docs.google.com/drawings/d/e/2PACX-1vTUkDh3yB6CGEPbVMskom4klR2hfJekcQDycqgr5hGeTN0Z6r4JPAruMdXlsjQ8UAJ7KzEAJhw3xLEE/pub?w=903&h=419)

### Pipelines

More details on the microservice pipelines that Brewdex is built on can be found in the [Pipeline](docs/pipeline/) docs.

## Deploy

TODO

## Contributing

TODO
