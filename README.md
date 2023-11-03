# dyathara
Framework for building modular Flutter apps with TypeScript &amp; Prisma

Inspired by [React Native](https://reactnative.dev/), provides a way to build fast stable apps that can lean on the existing Flutter & JS ecosystems.

Utilizes several technologies:
 - [Flutter](https://flutter.dev/) - Native cross-platform app framework using the Dart language, built by Google.
 - [TypeScript](https://www.typescriptlang.org/) - Transpiled JavaScript flavor providing an experience closer to languages like C#, built by Microsoft.
 - [Prisma](https://www.prisma.io/) - Database ORM framework with a blazing fast Rust core to interface your schema with TypeScript without manually writing/generating query language.
 - [@openwebf/mercury](https://github.com/openwebf/mercury) - Flutter library for running a full JavaScript environment via an optimized fork of the [QuickJS engine](https://bellard.org/quickjs/) & W3C-compliant polyfills, based on a webapp framework initially developed with Alibaba.
 - [@medz/prisma-library](https://github.com/medz/prisma-library) - C bindings for the Rust Prisma Engine.
 - [sqflite_common_ffi](https://pub.dev/packages/sqflite_common_ffi) - Flutter library for using sqlite.