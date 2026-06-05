# Example User Workflow

## 1. User selects DAW

Example:

```text
Logic Pro

2. User adds available plugins

Example:
FabFilter Pro-Q 3
Waves Tune Real-Time
Ozone 12
RX 10
Valhalla VintageVerb
3. User asks a question

Example:

My vocal sounds muddy and not bright enough. What should I change?
4. Assistant gives plugin-aware advice

The assistant should only recommend plugins that the user actually owns.

5. User uploads screenshot or audio file

The assistant analyzes the chain and gives practical feedback.


---

## 6. Создай Issues

Зайди во вкладку **Issues → New issue**. GitHub официально использует Issues для планирования, обсуждения и трекинга задач в проекте. :contentReference[oaicite:3]{index=3}

Создай 7 задач.

### Issue 1

**Title:**

```text
Build basic web app structure

Description:

Create the initial frontend structure for the Sound Engineer AI web app.

Tasks:

- choose frontend stack
- create basic layout
- add chat interface placeholder
- add user plugin profile section
- add screenshot upload placeholder
Issue 2

Title:

Create backend API service skeleton

Description:

Create the initial backend API structure.

Tasks:

- define API routes
- add OpenAI API client plan
- add environment variable setup
- add request validation
- add basic error handling
Issue 3

Title:

Add OpenAI API integration

Description:

Add OpenAI API integration for the assistant.

Tasks:

- create secure API key handling
- add first chat completion workflow
- add prompt routing
- return structured assistant responses
Issue 4

Title:

Create user plugin profile system

Description:

Create a system that allows users to define their DAW and available plugins.

The assistant should use this profile to avoid recommending plugins that the user does not own.
Issue 5

Title:

Add screenshot analysis workflow

Description:

Create a workflow for analyzing screenshots from DAWs and plugin chains.

The assistant should explain:

- what the settings mean
- what may be wrong
- what to change
- how to improve the chain
Issue 6

Title:

Add audio feedback workflow

Description:

Create a workflow for giving structured feedback on uploaded audio files.

Planned feedback areas:

- vocal clarity
- muddiness
- harshness
- low-end balance
- stereo width
- loudness
- master readiness
Issue 7

Title:

Add DAW-specific documentation

Description:

Add documentation and assistant behavior for specific DAWs.

Initial DAWs:

- Logic Pro
- Ableton Live
- FL Studio
