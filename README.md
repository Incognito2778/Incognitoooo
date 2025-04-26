# Game2Bed Releases

This repository contains the release binaries for Game2Bed. Each release is tagged with the corresponding version number.

## How to Update

1. Create an empty commit:
```bash
git commit --allow-empty -m "Release vX.X.X"
```

2. Create a tag:
```bash
git tag -a vX.X.X -m "Release vX.X.X"
```

3. Push the commit and tag:
```bash
git push origin main
git push origin vX.X.X
```

4. Create a new release on GitHub with the tag
5. Upload the release binaries (Windows .exe and Mac .dmg) 