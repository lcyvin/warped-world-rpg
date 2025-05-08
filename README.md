# Warped World RPG mdbook Repo

This repo contains the mdbook source for the Warped World RPG online sourcebook.
Warped world is a standalone, scratch-built tabletop roleplaying game designed
to handle a number of different possible game types one could want to play
within the broad fiction SCP provides. For more information or to read the most
up-to-date version of the sourcebook, see
[warpedworldrpg.com](https://warpedworldrpg.com).

## Contributing

If you would like to make additions or modifications to this book, please create a fork
and open a PR with your changes after submitting an issue or RFC to allow for discussion.
Minor changes, like typos and gramatical fixes, may not need an opened issue/RFC,
depending on the scope and nature of the change.

### Editor Setup & Style Guide

Please ensure any PRs follow the following standards for content:

- Word break at or before 90 characters (see the .vimrc in this project's root)
- Chapter and Section titles should use title casing (E.G.: This is Title Cased)
- Unless specifically necessary or relevant utilize neutral, inclusive language
  ("they" instead of "he or she", for instance)
- Any excerpts or content additions such as game starters or supplements must be original
  works or otherwise be directly attributed to their authors and be used with explicit
  permission.

### Requirements

In order to render a local version of the book, you will need to install the
mdbook rust package from cargo or your package manager. Currently, the github
actions build/deploy workflow utilizes the 0.4.45 version. Be sure to ensure
there are not breaking changes between the version you are using and the one the
runner uses if your local version does not match the workflow's.

#### Arch Linux:

mdbook can be installed from the `extra` repository:

```
sudo pacman -S mdbook
```

#### Cargo Package Manager:

Using cargo, mdbook can be installed on most operating systems:

```
cargo install --version 0.4.45 mdbook
```

*for more installation options and information, see the [mdbook repository.](https://github.com/rust-lang/mdbook)*

## Roadmap

- [ ] Port existing content from the old docs
  - [X] Introduction
  - [X] Game Setup
  - [X] Character Backgrounds
  - [ ] Gameplay Mechanics
  - [ ] Progression and Leveling
- [ ] Fix/improve mobile display
- [ ] Finish out core ruleset for playing as anomalous entities
- [ ] Write campaign starter
- [ ] Create print version
- [ ] Create character sheets
  - [ ] Print version
  - [ ] Web version
- [ ] Create pocket edition/reference version rulebook

## Suggested Contributions

The following items are open to any interested contributors as elements of the Warped
World game reference to be improved upon as content is still being ported. Of course,
contributions to other parts of this book are welcoomed as well, but these may give
interested parties a place to start.

- Improve Anartist Background: revise/update proficiency flavor text(s)
- Expand Glossary and Basic Terminology reference sections
