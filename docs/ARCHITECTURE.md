# Architecture

Sound Engineer AI is planned as a standalone web service powered by the OpenAI API.

## Main Parts

```text
User
  ↓
Web App
  ↓
API Service
  ↓
Prompt Workflows
  ↓
OpenAI API
  ↓
Structured AI Response
```

## Web App

The web app will allow users to:

* ask audio engineering questions
* upload screenshots
* define their DAW
* define available plugins
* receive mix and master feedback

## API Service

The API service will:

* receive user requests
* prepare the correct prompt workflow
* call the OpenAI API
* return structured responses
* protect API keys

## Prompt Workflows

Prompt workflows will be separated by task:

* vocal processing
* mixing
* mastering
* plugin settings
* DAW troubleshooting
* screenshot analysis
* audio feedback
