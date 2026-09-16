# AI Workflow Finder

A lightweight prototype for identifying repetitive workplace tasks that may be good candidates for AI assistance.

## What it does

Users describe a recurring task, enter how often it happens and how long it takes, and the prototype returns:

- an opportunity score
- estimated monthly time impact
- a potential time-reduction estimate
- a suggested AI approach
- a practical first step for testing the idea

## Prototype approach

This version intentionally uses simple client-side logic rather than an external AI API. That keeps the prototype easy to run, inexpensive, and safe to demo without exposing API keys.

A production version could add an LLM through a secure backend, connect to company systems with permission, and learn from user feedback. The key assumption to test is whether starting with employees' descriptions of their actual work makes AI adoption easier and more practical.

## Run locally

Open `index.html` in a browser, or serve the folder with any simple static web server.
