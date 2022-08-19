# Upload instructions

```
git fetch upstream --tags
git checkout vX.Y.Z
git cherry-pick vA.B.C-pypi --edit
git tag vX.Y.Z-pypi
git push origin vX.Y.Z-pypi
```
