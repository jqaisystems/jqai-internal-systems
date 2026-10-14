# Etsy to Pinterest Pipeline

[Website case study](https://www.ai.joaoqueiros.com/systems/etsy-to-pinterest) · [Guided demo](https://www.ai.joaoqueiros.com/demo/etsy-to-pinterest.html) · [System film](https://www.ai.joaoqueiros.com/media/systems/films/etsy-to-pinterest.mp4)

Status: internal system, described using public workflow evidence. Updated 14 October 2026.

## Problem

Listing promotion involves repeated asset selection, SEO fields, board choices and scheduling. Image pins and video pins also need different delivery paths.

## Workflow

1. Import listings through Etsy or a CSV, preserving image and video context separately.
2. Exclude unusable images and prepare Pinterest-sized assets, checking duplicates.
3. Draft listing-specific titles, descriptions, keywords, boards and alt text.
4. Review the drafts and use explicit batch controls.
5. Re-host approved images before scheduling image pins through the posting path.
6. Prepare video assets and metadata in a separate manual upload queue.
7. Export the video queue and track which items have been posted.

The public walkthrough demonstrates CSV import, stop and rollback controls, image scheduling and the manual video queue. Video files do not enter the image-posting webhook.

## What changes

The operator can review repeatable preparation steps in one workspace. Separate media paths make the handoff clear: approved images can be scheduled, while video pins remain under manual upload control.

## Adaptable patterns

Marketplace-to-social preparation, batch metadata, duplicate checks, review queues and separate delivery paths by media type.

## Evidence and boundaries

The linked website case study and guided demo are the public evidence. This breakdown makes no guaranteed time-saving claim. Production data, shop exports, prompts, credentials and implementation source stay private.
