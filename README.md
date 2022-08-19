## Create helm chart project
```
cd charts
helm create <project>
```

## Create package
```
cd chart/<project>
helm package .
```

## Move package to docs folder
```
mv <project>.tgz ../../docs
```

## Update index.yaml
```
cd docs/
helm repo index .
```
