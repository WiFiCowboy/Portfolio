# Legacy submodule reference

The 2019 portfolio contained an orphan Git submodule entry:

- Path: assests/mygist
- Commit: 14869f84e5e5a1eda10376cd5848824b5bb152b2
- Mode: 160000
- Source URL: not recorded in a .gitmodules file

GitHub Pages failed during checkout because this entry had no source URL. The current site does not use this path. The orphan entry was removed from the current tree to restore publishing; the original entry remains in commit dd54ff986c4142d4035e290ae1ecc873cb6af81f and subsequent history before the repair. No submodule content was available to migrate.
