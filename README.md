# Target Discriminator Media Assets

This repository contains all media assets (photos and videos) used by the Target Discriminator applications.

## Structure

- `photos/threat/` - Threat identification photos
- `photos/non_threat/` - Non-threat photos
- `videos/threat/` - Threat identification videos
- `videos/non_threat/` - Non-threat videos

## Usage

This repository is included as a git submodule in:
- Android app repository
- Web app repository

## Adding New Media

1. Add files to the appropriate directory
2. Commit and push to this repository
3. Update the submodule reference in the consuming repositories
