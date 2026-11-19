# Pokémon Italy

Pokémon Italy is a work-in-progress, English-language single-player ROM hack project based on the US version of Pokémon White 2 for Nintendo DS.

The planned region takes inspiration from Italy's cities and mountain landscapes. The story will explore a supernatural mystery with a darker tone, alongside a familiar journey through eight Gyms and the Pokémon League. The project aims to retain Generation V's visual style and mechanics and feature Pokémon from Generations I–V.

## Development

- `main` holds the project overview and will host stable project updates.
- `dev` is the working branch for source integration and development.

The source base is [fuddlesworth/pokebw2](https://github.com/fuddlesworth/pokebw2), a community decompilation of Pokémon Black 2 and White 2. The initial import on `dev` is a source snapshot from upstream commit [`3aec1627a9`](https://github.com/fuddlesworth/pokebw2/commit/3aec1627a9a5751a3973b44c10ea6e28ad3b5967). See the upstream GPL-3.0 license included with the imported sources.

The initial snapshot is not a standalone build. For baseline build instructions and the required inputs, see the [upstream build guide](https://github.com/fuddlesworth/pokebw2#build). The planned playable release will be a patch applied locally to the matching White 2 ROM.
