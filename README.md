# kaggle-titanic

## to commit, add this to git config

```
[filter "strip-notebook-output"]
    clean = jupyter nbconvert --ClearOutputPreprocessor.enabled=True --ClearMetadataPreprocessor.enabled=True --to=notebook --stdin --stdout --log-level=ERROR
```
