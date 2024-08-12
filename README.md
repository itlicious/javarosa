# BDB Collect
## How to sync with remote?
- git fetch --all
- git checkout -b feature/v4.4.0.1  v4.4.0 (v4.4.0 is the remote tag we are starting from)
- merge from previous changes and solve conflicts
- push to the feature branch
- git tag v4.4.0.1
- git push origin --tags
- https://jitpack.io for getting a pack