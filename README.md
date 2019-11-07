# Drupal JSON schemas
This schemas can be used to validate Drupal 8+ yaml files.

## Usage
### PhpStorm (config file)
*Note:* this may override your existing JSON Schema Mappings.   

1. Copy thge file [jsonSchemas.xml](https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/configs/jsonSchemas.xml) to `.idea` directory in your PhpStorm project root.
2. Restart IDE

### PhpStorm (manual)
1. Open `File | Settings | Languages & Frameworks | Schemas and DTDs | JSON Schema Mappings`
2. Add the following schemas as needed

|Name|Url|Pattern|
|----|---|-------|
|Drupal info|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/info.yml.json`|`*.info.yml`|
|Drupal layouts|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/layouts.yml.json`|`*.layouts.yml`|
|Drupal libraries|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/schema/drupal/libraries.yml.json`|`*.libraries.yml`|
|Drupal links (task)|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/links.task.yml.json`|`*.links.task.yml`|
|Drupal links (menu)|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/links.menu.yml.json`|`*.links.menu.yml`|
|Drupal links (contextual)|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/links.contextual.yml.json`|`*.links.contextual.yml`|
|Drupal links (action)|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/links.action.yml.json`|`*.links.action.yml`|
|Drupal permissions|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/permissions.yml.json`|`*.permissions.yml`|
|Drupal routing|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/routing.yml.json`|`*.routing.yml`|
|Drupal services|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/services.yml.json`|`*.services.yml`|
|Drupal breakpoints|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/breakpoints.yml.json`|`*.breakpoints.yml`|
|Drupal migrations|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/migration.yml.json`|`*/migrations/*.yml`, `*.migration.*.yml`|
|Drupal configs schemas|`https://raw.githubusercontent.com/5n00p4eg/Drupal-json-schemas/master/schema/drupal/schema.yml.json`|`*/config/schema/*.schema.yml`|
|Drush site aliases|`http://json.schemastore.org/drush.site.yml`|`*/sites/*.site.yml`|

## TODO:
1. Add this schemas to schemastore.org [issue](https://github.com/SchemaStore/schemastore/issues/710)
2. Add schemas to Drupal core [issue](https://www.drupal.org/project/drupal/issues/3061454)
3. Add schema mappings to PhpStorm via bundled Drupal support or other custom plugin.  
