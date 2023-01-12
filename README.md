# ImportProcess Module
[![Build Status](https://travis-ci.org/spryker/import-process.svg)](https://travis-ci.org/spryker/import-process)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.3-8892BF.svg)](https://php.net/)

CategoryExporter contains the client to read categories from key-value storage.

## Installation

```
composer require spryker-projects/import-process
```

## Configuration

Register the `SprykerDemo` namespace.

```
// config/Shared/config_default.php

$config[KernelConstants::CORE_NAMESPACES] = [
    // ...
    'SprykerDemo',
    // ...
];
```

## Integration
You need to configure DataImportByImportProcessPlugin
in your own `ImportProcessDependencyProvider::createDataImportByImportProcessPlugin()`
to be able to import data.

## Documentation

[Module Documentation](https://academy.spryker.com/developing_with_spryker/module_guide/modules.html)
