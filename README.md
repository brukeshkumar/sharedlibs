# Jenkins Shared Library

It is a concept of having a common pipeline code in the version control system that can be used by any number of pipelines just by referencing it.Mutliple team can use the same shared library for their team.

Folder Structure 

```
Project Root
|
|
|-------Vars ( we have main groovy scripts and reusable function defined )
        |
        |----hello.groovy 
        |
        src ( utility is a function which is used with in the function and if there is any  static variables can be defined)
        |
        |----Utitlity.groovy 
        |
        resources
        |
        |----config.json
```
