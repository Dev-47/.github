# Branch naming conventions

Branches should not contain more than the scope of what you're currently trying to modify. It should be of descriptive types;
Recommended Branch types;

- release - for new releases
- feature - for new features
- hotfix/update - used when a feature is not working properly
- bugfix - used when there is a bug report

Give the shortest description of what the branch does after specifying the branch type.
e.g `feat/add-auth-middleware`

Issues should be added to the end of the branch name too if available.
e.g `feat/add-auth-middleware__#1`

`feat/add-auth-middleware__#1`

Breakdown of this would be

- branch type -> `feat`
- description -> `add-auth-middleware`
- issue(if exists) -> `#1`
