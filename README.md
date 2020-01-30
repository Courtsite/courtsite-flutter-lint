# Courtsite's Flutter linter options

To standardize linter settings across Flutter projects in Courtsite, this repository will hold the settings which can be included in Flutter projects inside `analysis_options.yaml`. The rules are a combination of rules from [pedantic](https://github.com/dart-lang/pedantic) and [effective_dart](https://github.com/tenhobi/effective_dart) as well as some custom rules on top of it.

## Usage

### pubspec.yaml

```yaml
dev_dependencies:
  courtsite_flutter_lints:
    git:
      url: https://github.com/Courtsite/courtsite-flutter-lint.git
```

### analysis_options.yaml

```yaml
include: package:courtsite_flutter_lints/analysis_options.yaml
```

## Disabled options

By default the `public_member_api_docs` is disabled because its a lot of noise on existing repositories. Enable it manually on new repositories if desired.
