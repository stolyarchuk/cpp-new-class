# VSCode CPP New Class Extension

## Features

* Auto creates header and source files from the given class name
* Filenames are transformed to snake case (configurable)
* Handles namespace names in class name
* Namespace names are transormed to lower case (configurable)
* Follows current active directory

## Usage

* Open command pallete (`ctrl+shift+p`)
* Type `C/C++: Create New Class...`

## Keyboard Shortcut

* CTRL+K N

## Settings

* `cpp.newclass.hppExtension` - extension for the header file created (defaults to `'h'`)
* `cpp.newclass.cppExtension` - extension for the source file created (defaults to `'cc'`)
* `cpp.newclass.useIfndef` - whether to to use `'ifndef'` header guard or `'#pragma once'` one
* `cpp.newclass.lowerCaseNamespace` - transform namespace names to lower case
* `cpp.newclass.snakeCaseFilename` - transform filenames to snake case
