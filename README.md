# PBR-Scripts
Set of Control Scripts for PSI Bioreactor Client software developed in Department of Adaptive Biotechnologies

1. [PP-GrowthOptimizer](https://gcri-doab.github.io/PBR-Scripts/PP-GrowthOptimizer.js)
Script for automatic quazi-continous characterization and consequent optimization of microorganism cultivated in PBRs based on programatic control of selected PBR parameters. The script is activated on a peristaltic pump scripting protocol.
2. [O2-PIcurveMeasurement](https://gcri-doab.github.io/PBR-Scripts/O2-PIcurveMeasurement.js)
Script for automatic measurement of oxygen evolution and respiration under different irradiances (PI curve measurements). The script is activated on the oxygen probe (O2 dissolved) scripting protocol.

## Installation

Put the .js file content to PSI Bioreactor Client software protocol scripting part and modify appropriately UserDefined section (object).

## Examples

2. lightStepMultiplierValues: [ 1, 1, 1 ] // this setting enables measurement of O2 evolution/respiration in triplicate

## License

Licensed under [MIT license](https://gcri-doab.github.io/PBR-Scripts/LICENSE)
