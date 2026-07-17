# Ari’el: An Embodied AI Guide

Ari’el is an embodied AI guide designed to help people understand complex software without leaving the application they are using.

Instead of behaving like a separate chatbot or static help panel, Ari’el moves toward the control the user selected, acknowledges the action, explains the feature in context, speaks the explanation aloud, and uses animation and spatial sound to feel present inside the interface.

## OpenAI Build Week

This repository supports the OpenAI Build Week submission:

**Ari’el: An Embodied AI Guide**

The submitted prototype demonstrates Ari’el inside a VR Quest software-training interface.

## What the prototype does

- Responds to menu and tool selections
- Moves toward the selected interface area
- Explains controls in context
- Uses speech and mouth synchronization
- Uses gesture, proximity, and movement sound
- Avoids blocking the cursor or selected controls
- Preserves alignment when the browser is resized or zoomed
- Supports a local-first interaction model

## How Codex was used

OpenAI Codex was used throughout development as an active engineering collaborator.

Codex helped:

- Refactor HTML, CSS, and JavaScript
- Repair interface alignment and zoom-related selection drift
- Improve animation timing and natural movement
- Integrate speech, mouth synchronization, and spatial audio
- Debug missing or broken character behavior
- Improve contextual responses
- Review regressions between iterations
- Package working versions for testing
- Maintain and improve the project through many rapid build-test-repair cycles

Codex was especially valuable because the prototype required coordinated changes across visual layout, interaction logic, animation, audio, and contextual behavior.

## How GPT-5.6 was used

GPT-5.6 was used for:

- Product direction and feature prioritization
- Simplifying the embodied-help concept into a clear contest entry
- Reviewing usability and interaction behavior
- Writing and refining Ari’el’s contextual responses
- Planning the submission structure
- Preparing the project description, README, and demonstration narrative
- Translating observations from testing into specific engineering changes

The model was used as both a reasoning partner and product-development collaborator, while the final implementation decisions remained under human direction.

## Architecture

The demonstration includes:

- HTML5
- CSS3
- JavaScript
- Browser speech synthesis
- Web Audio behavior
- Animated embodied interface logic
- Local interaction and contextual help content
- Optional local model integration through Ollama and Gemma 2

Ari’el is part of a broader local-first architecture called LIMINA, designed for privacy-respecting, emotionally aware, context-sensitive AI.

## Repository contents

This repository will contain:

- The final demonstration package
- Supporting assets
- Setup and testing instructions
- Documentation describing Codex and GPT-5.6 usage
- Screenshots and demonstration materials where appropriate

## Running the demonstration

Detailed run instructions will be added with the final project files.

The demonstration is intended to run locally in a modern desktop browser.

## Status

OpenAI Build Week submission in progress.

## Creator

Created by Bob Ladrach under LIMINA.
