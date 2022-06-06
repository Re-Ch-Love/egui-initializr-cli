# egui-initializr-cli

`egui-initializr-cli` is the initializer cli app for egui.

It can help programmers create `egui` projects more easily.

Sections:

- [Usage](#usage)
- [What can it do?](#what-can-it-do)

## Usage

1. Clone this repo locally.
2. 
3. Run.
4. Follow the instructions.

## What can it do?

**Receive your input, then clone the repo and modify it. It just reduces some repetitive, unnecessary and error-prone manual operations.**

For example, to create an `egui` project with `eframe` integration, we need the following three steps:

1. click `Use this template` button on GitHub
2. `git clone ...`
3. Modify the names in the template one by one according to the entries listed in the `README.md`.

It's too much trouble, and it's easy to forget to change something.

With this project, we just need the following steps:

1. click `Use this template` button on GitHub
2. `egui-initializr-cli create`
3. According to the instructions of the program, enter `repo address`, `app name`, and `integration/template name` (for example, `eframe`).

The program will then initialize the project automatically.