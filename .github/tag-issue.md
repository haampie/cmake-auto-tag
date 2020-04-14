---
title: cmake project version older than git tag
labels: bug
---
The cmake version should be in sync with the git version to ensure the correct file names and sonames of shared libraries:

- cmake version: {{ env.CMAKE_VERSION }}
- git tag: {{ env.GIT_VERSION }}