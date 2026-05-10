# Etsy To Pinterest Pipeline

Case study only. No source code, credentials, prompts, databases, logs, or API keys are included.

Public page: [Etsy to Pinterest Pipeline](https://www.ai.joaoqueiros.com/systems/etsy-to-pinterest)  
Public demo: [guided walkthrough](https://www.ai.joaoqueiros.com/demo/etsy-to-pinterest.html)

## Problem

Each new Etsy listing needs a Pinterest-ready image, title, description, alt text, board choice, and posting time. The work is small but constant, and skipping it weakens product discovery.

## System Pattern

The system imports listings, prepares images, detects the product niche, drafts Pinterest SEO metadata, deduplicates repeated assets, and sends approved pins into a review and scheduling flow.

## Stack

Python, FastAPI, Claude API, Etsy data, Pinterest API or Make.com webhook, SQLite-style workflow storage, image processing, human approval queue.

## Outcome

The workflow changes daily manual cross-posting into a short review step. It keeps Pinterest output consistent while preserving human approval before anything is posted.
