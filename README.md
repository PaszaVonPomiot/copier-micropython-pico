# Copier template for Micropython projects

## Installation
```sh
uv tool install copier
```

## Usage
Create project from template.

```
copier copy <template_folder> <destination_folder>  
copier copy https://github.com/PaszaVonPomiot/copier-micropython-pico.git project-name  
copier copy gh:PaszaVonPomiot/copier_template_core project-name --vcs-ref develop
```