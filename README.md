# Jenkins Shared Library

It is a concept of having a common pipeline code in the version control system that can be used by any number of pipelines just by referencing it.Mutliple team can use the same shared library for their team.

Folder Structure 

vars: This directory holds all the global shared library code that can be called from a pipeline. it has all the libary files with .groovy extension
src: it is added to the class path during every script compilation. We can add custom groovy code to extend our shared libary code.
resources: All the non-groovy files required for your pipelines can be managed in this folder.

```
Project Root
|
|
|-------Vars 
        |
        |----hello.groovy 
        |
        src 
        |
        |----Utitlity.groovy 
        |
        resources
        |
        |----config.json
```
