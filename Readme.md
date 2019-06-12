# Drupal json schemas
This schemas can be used to validate Drupal 8 yaml files.

## Supported yamls:
* *.info.yml (not completed)
* *.libraries.yml (wip) 
* *.breakpoints.yml (not completed)
* *.layouts.yml (wip)
* *.schema.yml (not-supported)

## TODO:
1. Add this schemas to schemastore.org
1. Add schema mappings to PhpStorm via bundled Drupal support or other custom plugin.  

## Usage
### PhpStorm
1. Open `File | Settings | Languages & Frameworks | Schemas and DTDs | JSON Schema Mappings`
1. Add needed:
   * *Drupal info*   
   url: `https://5n00p4eg.github.io/Drupal-json-schemas/info.json`   
   pattern: `*.info.yml`
   * *Drupal layouts*   
   url: `https://5n00p4eg.github.io/Drupal-json-schemas/layouts.json`   
   pattern: `*.layouts.yml`
   * *Drupal libraries*   
   url: `https://5n00p4eg.github.io/Drupal-json-schemas/libraries.json`   
   pattern: `*.libraries.yml`
