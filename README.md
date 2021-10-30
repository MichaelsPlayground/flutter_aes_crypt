# flutter_aes_crypt

ACHTUNG: Library ist NICHT null safety

https://pub.dev/packages/aes_crypt

aes_crypt: ^0.1.1

https://github.com/alexgoussev/aes_crypt

An attempt to migrate to null safety, I have made minor changes and with them currently

Package is able to be compiled in null-safe projects.
File Decryption works just like before.
String Encryption works just like before.
I have not tested out other functions and features, nor have I checked the code itself for bugs. So I would request proper verification and modification before accepting the pull. The reason I have created this PR is to let everyone know that this version can successfully do the above tasks and hence be used with null-safe projects if needed.

If someone wants to include my package as-is right now, that is from my github then simply add:

aes_crypt:
git:
url: git://github.com/cryoelite/aes_crypt.git
ref: master

under dev_dependencies in pubspec.yaml of your project. (with proper indentation)

dev_dependencies:
flutter_test:
    sdk: flutter
    # for null safety
    aes_crypt:
        git:
            url: git://github.com/cryoelite/aes_crypt.git
            ref: master

oder hier: https://github.com/cryoelite/aes_crypt



A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
