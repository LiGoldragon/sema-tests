# Fixture provenance

The earlier fixture-selection packet was unavailable to this setup flow. This minimal selection was made from the current remote `main` of each public source repository. Each fixture is restored exactly with `git show <revision>:<path>`, and `SOURCES.tsv` records its source repository, full revision, path, Git blob identity, and SHA-256.
