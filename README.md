# AppFlowy Plugins

Powerful add-ons for the flexible and popular rich-text editor [AppFlowy Editor](https://pub.dev/packages/appflowy_editor) for Flutter.

## Available plugins

- [Link Preview](https://github.com/AppFlowy-IO/appflowy-plugins/blob/main/packages/af_link_preview)

Looking for a plugin but cannot find it on the list? Submit a [Plugin request](https://github.com/AppFlowy-IO/appflowy-plugins/issues/new)!

## Melos

To make it easier to manage a federated package approach, we use [Melos](https://pub.dev/packages/melos). If you need to develop across multiple packages, you can bootstrap melos by running `melos bootstrap`.

Scripts available:

- `melos run analyze`: Run `dart analyze .` in all packages.
- `melos run format`: Run `dart format --set-exit-if-changed` in all packages.
- `melos run get`: Run `flutter pub get` in all packages.
