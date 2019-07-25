# Westwing fork of Zend Framework 1

This is Zend Framework 1.12.20 fork with following changes:

- The following folders have been removed: `demos/`, `documentation/`, `tests/` 
in order to reduce repository size.
- Improved autoloading. Explicit `require_once` calls in the source code has 
been commented out to rely on composer autoloading, this reduces the number of 
included files to a minimum.

## How to use
   
Add `"westwing/zendframework1": "1.12.20"` to the require section of your 
`composer.json`, include the composer autoloader and you're good to go.
