# Kindness Drive

Playable build: https://joenasriani.github.io/kids-kindness-drive/

Kindness Drive is a three-lane browser game developed as part of a multi-game interactive children’s edutainment activation in the UAE. Its core rule is direct: collect named constructive habits and avoid named harmful or unsafe habits.

## Game rule

The player moves a car between three lanes while habit statements travel down the road.

- Collecting a constructive habit adds to the score.
- Missing too many constructive habits ends the run.
- Contact with a harmful or unsafe habit ends the run and displays a short explanation linked to that statement.
- Level progression changes the pace of incoming items.

Examples present in the current build include sharing toys, saying please, helping others, telling the truth, washing hands, wasting food, being rude, and talking to strangers.

## Instructional structure

**habit statement → player decision → immediate game consequence → short reinforcement or explanation**

The repository demonstrates that interaction structure. It does not contain a controlled study measuring learning, retention, behavior change, or educational effectiveness.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Repository scope

This repository contains one playable game module. It does not contain a multi-game platform, learner accounts, curriculum tracking, teacher controls, or cross-game progression.

## Implementation

The playable build is contained in `index.html` and uses React, ReactDOM, Babel and Tailwind loaded from public CDNs.

`index.html` is the game artifact. The accompanying README, crawl instructions and informational page describe the artifact without changing its rules, controls, scoring, assets or runtime behavior.
