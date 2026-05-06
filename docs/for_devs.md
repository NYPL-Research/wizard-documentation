---
layout: default
title: For Devs
parent: Home
nav_order: 9
---

# For Devs
`Hello World!` Welcome to the **Wizard** ecosystem.

If you are here, you are probably wanting to understand how Wizard functions. In this subcategory, you will find support for each Action script, as well as for the app as a whole.

## Key Architectural Terms

**Action Scripts**
: files that act as "grunt" workers that run a specific action for DIS workflow, these are all CLI compatible

**Orchestrator**
: a file (orchestratory.py) that acts as the "manager" of all of the "grunt" action scripts

**Components**
: a file (components.py) that acts as the "executive", in other words the front-facing User Interface

**Handlers**
: a file (handlers.py) that contains all handlers for running Action Scripts through Orchestrator via the Components UI