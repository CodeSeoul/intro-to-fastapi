# Intro to FastAPI

This is a tiny project demonstrating some useful and interesting features of FastAPI. This was built alongside [a presentation delivered as part of CodeSeoul's Saturday Hangouts event](https://docs.google.com/presentation/d/1b4aB3SHxpwJSmmOnesIEyRrMmkb3K5PN1GWGUgS090g/edit#slide=id.p).

We recorded it the presentation, but the audio wasn't configured properly. Instead, this repository has lots of comments. Please create an issue if anything is missing or unclear in the explanations.

## Setup
Mac/Linux:

```shell
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -e '.[dev]'
pre-commit install
```

## Running it
Mac/Linux
```shell
app
```

You can check the automagically generated documentation by visiting [http://localhost:5000/docs](http://localhost:5000/docs).
