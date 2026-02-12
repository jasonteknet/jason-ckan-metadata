# jason-ckan-metadata

Custom CKAN metadata repository for Jason's KSP mods and forked mods.

## Structure

Store metadata as one `.ckan` file per version under a folder named for the CKAN identifier.

Example:

- `KRPC.SCANsat/KRPC.SCANsat-v0.3.1.ckan`

## Notes

- Use exact `identifier` values in file content and folder names.
- For fork overrides, keep upstream identifier and use your fork release URL in `download`.
- For brand-new mods, use a unique identifier.
