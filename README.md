# Degree Planner Update Channel

This public repository hosts verified Degree Planner update artifacts only.

It intentionally contains no application source code. The private source repository remains separate.

The installed Degree Planner application reads `latest.json`, downloads the referenced HTTPS installer, verifies its SHA-256 hash, and only then launches the update installer.
