# US Telecom Routing Data: Static Architecture

This repository contains the logic and documentation for a high-performance static site generator built in Python.

## Project Scope
The goal is to map localized telecom payment gateways and support structures for hundreds of US cities without the overhead of a dynamic database. By utilizing Python and Jinja2, the pipeline converts raw CSV datasets into a zero-latency HTML directory.

### Core Tech Stack
* **Language:** Python 3.12
* **Templating:** Jinja2
* **Infrastructure:** Bare-metal VPS / Static HTML

## Live Production Deployment
A live instance of the generated environment, currently hosting 170+ localized routing nodes, is available for testing here:

