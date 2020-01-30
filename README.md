# GetCar's Flutter linter options

To standardize linter settings across Flutter projects in GetCar, this repository will hold the settings which can be included in Flutter projects inside `analysis_options.yaml`, i.e.:

## pubspec.yaml

```yaml
dev_dependencies:
  getcar_flutter_lints:
    git:
      url: git@gitlab.com:getcar/flutter-linter-options.git
```

## analysis_options.yaml

```yaml
include: package:getcar_flutter_lints/analysis_options.yaml
```
