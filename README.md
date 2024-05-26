# DjangOBS

----
![python](https://img.shields.io/static/v1?label=Python&message=3.11&logo=Python&color=3776AB)
![django](https://img.shields.io/static/v1?label=Django&message=5.0&logo=Django&color=092E20)
![obs](https://img.shields.io/static/v1?label=OBS%20Webservices&message=5.0&logo=obsstudio&color=302E31)

DjangOBS is an adapter to handle OBS WebSockets with django.

## Features

WIP

## Installation

WIP

## Configuration

WIP

### Examples

WIP

## External documentation

DjangOBS creates an adapter of [`obsws-python`](https://github.com/aatikturk/obsws-python) for Django.
It achieves this by creating and abstraction layer between [`Django`](https://www.djangoproject.com/) and [OBS](https://obsproject.com/fr/)

### Developer's notes

This app is created to support handling streaming events. So it's highly driver with the needs that arose during such events.
It's maintained _(at the moment)_ mostly to support the future of [FastAndFabs](https://www.twitch.tv/fastandfabs) events.

I created this to help me clean up the dirty code I wrote for [`marathon-manager`](https://github.com/FastAndFabs/marathon-manager).