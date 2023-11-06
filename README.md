# gpt4auto

gpt4auto is inspired by gpt4all, privateGPT, h2ogpt, AutoGPT and other many AI Tools in Github.

I want to create the feel free tool that simple private GPT for daily.

## Summary(Purpose)

* Auto GPT Web for Complitely Private Using via OpenAI API Supecification
* Lightweight, CPU first (GPU as just option)
* Simple Structure / Open any process and models

## Structure

* Ref ```compose.yml```

## Status

* Work in progress
  * Now I collected the needed modules
  * Each service can be started, but there are not connected yet

## Recent Milestone

* Minimum Setup and Run all services
  * ~~Find operational repositories and modules~~
  * Implements OpenAI API specification
  * Check operation from AutoGPT web
* Refactor and Optimization
  * Remove and merge duplicate sources and no required files
  * Unify Docker description and properly separate the build process

## Develop

### Initial setup

* Debian
  * ```apt update && apt upgrade -y```
  * Install docker engine
    * https://docs.docker.com/engine/install/debian/
  * ```sudo docker compose up --build```

### Reset environment

* Docker
  * ```sudo docker system prune```
