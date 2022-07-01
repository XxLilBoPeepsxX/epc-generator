# Laravel EPC Generator

[![Latest Version on Packagist](https://img.shields.io/packagist/v/xxlilbopeepsxx/epc-generator.svg?style=flat-square)](https://packagist.org/packages/xxlilbopeepsxx/epc-generator)
[![Total Downloads](https://img.shields.io/packagist/dt/xxlilbopeepsxx/epc-generator.svg?style=flat-square)](https://packagist.org/packages/xxlilbopeepsxx/epc-generator)

A library to generate Energy Performance Graph.

Sample:

```
$report = (new EpcGenerator())
    ->setAddress('1 Test Address, Success street.')
    ->setReference('ABC123')
    ->setCurrentEnergyEfficiencyRating(40)
    ->setPotentialEnergyEfficiencyRating(50)
    ->setCurrentEnvironmentalImpactRating(60)
    ->setPotentialEnvironmentalImpactRating(70)
    ->stream();
```

## Installation

You can install the package via composer:

```
composer require xxlilbopeepsxx/epc-generator
```


