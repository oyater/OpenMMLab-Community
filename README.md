# OpenMMLab-Community

## Join OpenMMLab
 All the contributors are welcomed to claim your reward by filing this form.
 
 ### As a developer：
|**Role**     |  **contributor** | **Active contributor** | **committer** | **maintainer** | 
|:----:   |  :----:      | :----:             |:----:     |:----:      |
|**Definition**  | Submit standard Pr and be merged 1 or more times| Submit standard pr and be merged 3 times or more     | Submitted 5 standard pr or more times and merged, and through (two-way) self-referral/selected by Maintainer              |    Released after review and long-term maintenance of MM series algorithm library, sub-project members       |   
|**Medal**  | ![Image text](https://github.com/oyater/OpenMMLab-Community/blob/main/image/be07b70e-a563-47ae-bfad-33f0bc6ec969.jpeg)     | ![Image text](https://github.com/oyater/OpenMMLab-Community/blob/main/image/1acba771-1375-427d-b700-33491961fc0b.jpeg)      | ![Image text](https://github.com/oyater/OpenMMLab-Community/blob/main/image/e691bacd-c49f-4f34-9bcf-552c69205166.jpeg)              | ![Image text](https://github.com/oyater/OpenMMLab-Community/blob/main/image/9c27baa5-5e97-4450-a4c7-1bf0633bc11a.jpeg)        |   
|**Rights**   | 单元格     | 单元格       | 单元格              |           |   
|**Rights**   | 单元格     | 单元格       | 单元格              |           |   

 ### As a user：
|**Role**     |  **contributor** | **Active contributor** | **committer** | **maintainer** | 
|:----:   |  :----:      | :----:             |:----:     |:----:      |
|Definition   | Submit standard Pr and be merged 1 or more times| Submit standard pr and be merged 3 times or more       | Submitted 5 standard pr or more times and merged, and through (two-way) self-referral/selected by Maintainer              |    Released after review and long-term maintenance of MM series algorithm library, sub-project members       |   
|**Medal**  | 单元格     | ![Image text](https://github.com/oyater/OpenMMLab-Community/blob/main/image/1acba771-1375-427d-b700-33491961fc0b.jpeg)   | 单元格              |           |   
|**Rights**   | 单元格     | 单元格       | 单元格              |           |   
|**Rights**   | 单元格     | 单元格       | 单元格              |           |   


## Learn about OpenMMLab

[**OpenMMLab Course**](https://github.com/wangruohui/OpenMMLabCourse)

## Contribute to OpenMMLab

All kinds of contributions are welcome, including but not limited to the following.

* Fix typo or bugs
* Add documentation or translate the documentation into other languages
* Add new features and components

**Workflow
1. fork and pull the latest OpenMMLab repository
2. checkout a new branch (do not use master branch for PRs)
3. commit your changes
4. create a PR
    If you plan to add some new features that involve large changes, it is encouraged to open an issue for discussion first.

**Code style

Python
We adopt PEP8 as the preferred code style.

We use the following tools for linting and formatting:

flake8: A wrapper around some linter tools.
isort: A Python utility to sort imports.
yapf: A formatter for Python files.
codespell: A Python utility to fix common misspellings in text files.
mdformat: Mdformat is an opinionated Markdown formatter that can be used to enforce a consistent style in Markdown files.
docformatter: A formatter to format docstring.
Style configurations of yapf and isort can be found in setup.cfg.

We use pre-commit hook that checks and formats for flake8, yapf, isort, trailing whitespaces, markdown files, fixes end-of-files, double-quoted-strings, python-encoding-pragma, mixed-line-ending, sorts requirments.txt automatically on every commit. The config for a pre-commit hook is stored in .pre-commit-config.

After you clone the repository, you will need to install initialize pre-commit hook.

pip install -U pre-commit
From the repository folder

pre-commit install
After this on every commit check code linters and formatter will be enforced.

Before you create a PR, make sure that your code lints and is formatted by yapf.

C++ and CUDA
We follow the Google C++ Style Guide.

## License
This project is released under the Apache 2.0 license.

