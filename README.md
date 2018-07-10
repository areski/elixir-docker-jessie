
# Docker Elixir & Erlang Build

Dockerfile to build Elixir/Erlang on Debian 8 (Jessie)

This builds a Docker image that can be used as a base to build Elixir (and Erlang) projects.

## How to build your Docker

Elixir 1.6.6 on Jessie:

    docker build --tag=jessie_elixir16 -f docker/Dockerfile.Jessie.Elixir16 .

Erlang 21 on Jessie:

    docker build --tag=jessie_erlang21 -f docker/Dockerfile.Jessie.Erlang21 .

## See Also

- https://github.com/Financial-Times/docker-elixir-build
