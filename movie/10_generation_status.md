# 10 — Generation Status

| Scene | Story | Screenplay | Shots | Keyframes | Video | Voice | Sound | Music | Edit | QC | User Approval |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 01 | Ready | Ready | Ready | Approved reference | Not rendered | Pending | Pending | Pending | Pending | Pending | Visual approved; final scene not yet locked |

## Command behavior
`Generate Scene XX` = run all available pipeline stages, perform QC, and present a review package. User approval is required before the scene becomes LOCKED.

## Revision behavior
If the user requests a change, identify affected shots/assets/context, regenerate only what is necessary, then rerun relevant QC. Never silently change locked continuity.
