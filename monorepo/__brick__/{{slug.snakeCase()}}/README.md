# {{name}}

This monorepo contains {{name}}'s Dart packages and Flutter apps and is managed by [Melos](https://github.com/invertase/melos).

## Getting Started

### Install Flutter

First you'll need to install the Flutter SDK. Follow the [installation instructions](https://flutter.dev/docs/get-started/install/).

### Install Dart global packages required

Then run the following commands to set up your development environment:

```bash
dart pub global activate melos
dart pub global activate lockpick
```

### Clone the repo

```bash
git clone {{{repo-url}}}
```

### Run commands for init [melos](https://github.com/invertase/melos)

```bash
cd {{slug.snakeCase()}}
melos bs
```
