# Big Walk: Feature Scope

Status: Module concept - not implemented. Checked 2026-09-05.

The items below are proposed capabilities. They are not release notes or a list of working features.

## Route bookmarks

Plan player-created landmarks and routes that can be used as an external reference during exploration.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Layered clues

Design optional hints in stages, beginning with a nudge and only revealing a fuller solution when requested.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Challenge practice

Investigate versioned practice snapshots for replaying a completed challenge with the group.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Movement experiments

Research movement-related practice settings only where a private-session prototype can preserve puzzle and world consistency.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Progress reference

Provide a manually maintained checklist for visited areas and discovered challenges.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Group profiles

Record agreed practice settings so the whole group knows how an experimental session differs from an ordinary one.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Shared application architecture

This theme is one adapter for a common application. The shared interface can manage profiles and show change previews; each game adapter must implement and validate its own behaviour. No universal memory addresses, item identifiers, save paths or hotkeys are supplied.

## Session scope

Shared-session experiments require an agreed private group. Host and guest state must be tested separately; the package does not claim an offline mode or solo support for a co-op-only game.

## First implementation target

A group is stuck at a landmark. The planned assistant first shows the group's own route notes, then offers a small clue, keeping the full solution hidden until requested.
