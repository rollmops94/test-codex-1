# Release Cut

1. Update `CHANGELOG.md` with release notes.
2. Commit changes with `chore: prepare release`.
3. Tag the commit:
   ```bash
   git tag -a vX.Y.Z -m "Release vX.Y.Z"
   git push origin vX.Y.Z
   ```
4. Create a GitHub release if applicable.
