# Project Commands

## Primary command
**Generate Scene XX**

Runs the complete available pipeline for that scene using the repository as the source of truth:
1. Load all bibles/context.
2. Check previous/next continuity.
3. Generate/update scene design.
4. Generate original Tamil screenplay.
5. Divide into shots.
6. Generate keyframe/reference prompts and images when image generation is available.
7. Generate video prompts for the selected video-rendering system.
8. Generate Tamil voice/dialogue prompts.
9. Generate sound design.
10. Generate music cues.
11. Generate editing instructions.
12. Run continuity/QC.
13. Present a review package.
14. Wait for user approval.

The scene is not final until the user says **Approve Scene XX**.

## Revision commands
- `Regenerate Scene XX Shot YY`
- `Change [specific element] in Scene XX`
- `Apply suggestions and regenerate Scene XX`
- `QC Scene XX`
- `Approve Scene XX`
- `Continue`

## Continuity rule
Approved/locked scene data becomes input to subsequent scenes.

## Rendering limitation
The ChatGPT toolset currently available to this project can generate images and production specifications but does not provide a built-in MP4 video renderer. Video prompts are therefore renderer-ready specifications for the chosen external video-generation system. Do not claim an MP4 exists unless an actual video file has been rendered and attached.
