# Mental Models Box (Data)

This is the repository for the data used in the [mentalmodelsbox.com](https://www.mentalmodelsbox.com) website. 

A separate [app repository](https://github.com/deepkanwal/mentalmodelsbox-app/) is used to manage the front-end application.

## Overview

Models are stored as YAML files. The one liner, description, and example fields use Markdown. Use of HTML tags within Markdown is not supported.

The overall structure of a file is:

```
id: some-id
name: Mental Model Name
oneliner: >
  Short overview of the model (preferably one line).
description: >
  Longer description of the model.
wikipedia: Link to Wikipedia article (if available).
examples:
  - >
    An example of the model in use.
  - >
    Another example--the goal is to have at least two for each model.
categories:
  - Category 1
  - Category 2
```

File names use the following structure:

```
[incrementing-integer]-[model-id].yml
```

Models currently use one or more of the following categories:

* behavioral-economics
* biases
* decision-making
* rational-thinking
* social-dynamics

If you are adding additional categories, please update past models with them (if applicable). 

## Style

This repo uses the [Red Hat YAML VSCode extension](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) for formatting with the following settings: 

* Print Width: 80
* Single Quote `'`
* Prose Wrap: Always

## License

<a href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 License</a>

Most of the model information has been sourced from Wikipedia and a link to the corresponding article is provided for each model when available.