# My AI Movie

Tamil investigation-thriller feature-film project.

## Purpose
This repository is the source of truth for the movie bible, characters, locations, props, continuity, scene/shot generation workflow, and production status.

## Core workflow
`Movie Bible → Character/Location/Costume/Prop Bible → Timeline → Clue Database → Scene → Shot Division → Keyframes → Video Prompts → Voice → Sound → Music → Edit → QC → User Review → Lock`

## User command
When the user says **Generate Scene XX**, interpret it as an orchestration request to run the complete available production pipeline for that scene, then present the result/package for review. Do not mark the scene final until the user explicitly approves it.

## Approval states
- IN PROGRESS
- READY FOR REVIEW
- REVISION REQUESTED
- APPROVED / LOCKED

## Locked character names
- Nagarajan
- Meera
- Aditya Karikalan
- Arjun
- Latha
- Raghuvaran
- Ashok Kumar
- Niral
- Kamala
- Indirani
- Inspector Stephen

## Locked Scene 01 visual direction
Nagarajan Estate: grand Tamil Nadu-inspired luxury estate; bright natural morning daylight; peaceful, elegant atmosphere with subtle mystery; photorealistic cinematic Tamil-film visual language. The celebration-remnants prop is a modern drinks glass, not a tea glass.

## Reference source
The user uploaded `KNIVES_OUT.pdf` in the ChatGPT conversation as source/reference material. The source is used as inspiration/reference for adaptation planning; do not reproduce the copyrighted screenplay verbatim or recreate it scene-for-scene in expression. Derived project documents should contain original Tamil adaptation material.

## Repository structure
- `movie/` — master creative bibles and prompt system
- `screenplay/` — approved original Tamil screenplay material
- `scenes/` — scene-level production packages
- `assets/` — approved visual references and generated production assets when upload is supported
- `references/` — source/reference notes and provenance

## Status
Scene 01 visual direction: **APPROVED / LOCKED**. Actual MP4 rendering is external to the current ChatGPT toolset; the repository therefore tracks production-ready prompts/assets and review state.