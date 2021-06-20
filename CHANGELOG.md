# Changelog
All notable changes to this project will be documented in this file.

## [0.1.0-rc.6] - 2021-06-20

### Miscellaneous Tasks

- Set the release body on linux

## [0.1.0-rc.5] - 2021-06-19

### Bug Fixes

- Update config to skip release commits

## [0.1.0-rc.4] - 2021-06-19

### Revert

- Chore(config): update template to include commit ids

## [0.1.0-rc.3] - 2021-06-19

### Bug Fixes

- Strip the unreleased title from tag message
- Update commit parsers to match the commit type

### Miscellaneous Tasks

- Fix setting the release body
- Update the skip_tags regex
- Update template to include commit ids

## [0.1.0-rc.2] - 2021-06-19

### Bug Fixes

- Use default tag_pattern for tests

### Features

- Add `--output` argument

### Miscellaneous Tasks

- Add release title to the tag message
- Set the release name explicitly
- Remove user directive from Dockerfile
- Set the changelog as release body

### Refactor

- Make tag_pattern optional

## [0.1.0-rc.1] - 2021-06-16

### Documentation

- Update the doc comment for completions script
- Add usage section

### Features

- Add `--workdir` argument
- Show the processsed commit message

### Miscellaneous Tasks

- Add release script
- Update the release script about arguments
- Strip the markdown format from tag message

### Refactor

- Update the value name for `--strip`
- Improve logging
- Update value names and description

## [0.1.0-beta.4] - 2021-06-14

### Bug Fixes

- Use bash while setting the release version

### Miscellaneous Tasks

- Add docker releases

## [0.1.0-beta.3] - 2021-06-14

### Bug Fixes

- Include configuration file in the binary releases
- Specify the bash as shell

### Miscellaneous Tasks

- Set the release body text

## [0.1.0-beta.2] - 2021-06-14

### Bug Fixes

- Install musl-tools for musl builds

### Miscellaneous Tasks

- Update config

<!-- generated by git-cliff -->