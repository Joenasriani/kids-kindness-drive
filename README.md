# Kindness Drive

Playable build: https://joenasriani.github.io/kids-kindness-drive/

Kindness Drive is a lane-based browser game created for a children's event and intended as one game module within a broader educational game direction for kids.

## What the player does

The player moves a car between three lanes. Short habit statements approach from the top of the road.

- Collect statements representing constructive habits.
- Avoid statements representing harmful or unsafe habits.
- Collecting a constructive habit increases the score.
- Missing too many constructive habits ends the run.
- Hitting a harmful habit ends the run and shows a short explanation tied to that habit.
- The pace changes as levels advance.

The current game uses examples such as sharing toys, saying please, helping others, telling the truth, washing hands, wasting food, being rude, and talking to strangers.

## Educational structure

The learning mechanism is embedded directly in the game rule:

**habit statement → player decision → immediate game consequence → short reinforcement or explanation**

The repository does not contain a formal learning-outcome study, so no claim is made here that the game has measured educational effectiveness.

## Event and product context

This build was made for use at a children's event. The event was a deployment context for the game, not the limit of the underlying educational-game concept.

The present repository contains this single playable module. It should not be read as evidence that a complete multi-game platform is implemented in this repository.

## Implementation

The current build is contained in a single `index.html` file and runs in the browser using React, ReactDOM, Babel and Tailwind loaded from public CDNs.

## Preservation note

The game file is kept as the playable artifact. Documentation and discovery files are maintained separately so the game rules, controls, scoring, assets and runtime behavior are not altered by repository-description work.
