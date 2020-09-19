# CodeAway

Codeaway is a Python package meant for developers to setup their project directory, with all necessary directories
, git tracking, virtual environment, auto documentation (Sphinx) and many more things. 
The user can setup the project using default configuration or go in detail through each configuration step. 

The directory structure will look as follows, with all components enabled:
* ```*```: folder or file not tracked in git
* ```+```: folder collapsed in description (not relevant)

```
project_name
|   README.md
|   setup.py
|   LICENSE
|   .gitignore
|   MANIFEST.in
|
└───package_name
|   |   __init__.py
|   └───data
|
└───test
└───data (*+)
└───secrets (*+)
|
└───docs
|   |   make.bat
|   |   Makefile
|   |
|   └───source
|   |   |   conf.py
|   |   |   index.rst
|   |   └───_static
|   |   └───_templates
|   |
|   └───build (*+)
|   
└───.github
|   └───workflows
|
└───.git (+)
└───.idea (*+)
└───.virtual_environment_name (*+)
```

To use the package, please refer to the [package documentation](https://github.com).
