# php_class_creator

## Description

Python script to create classes with their parents, interfaces or abstract classes

## Usage
```
usage: class [options]

Create a template for php classes, abstract classes and interfaces

positional arguments:
  class_name            name of the class you want to create

optional arguments:
  -h, --help            show this help message and exit
  -a ABSTRACT, --abstract ABSTRACT
                        create an abstract class of the class specified as first argument
  -i INTERFACE, --interface INTERFACE
                        create an interface of the class specified as first argument
  -p PARENT, --parent PARENT
                        create a parent of the class specified as first argument
  -v VISIBILITY, --visibility VISIBILITY
                        set the visibility of your classes [WIP]
```