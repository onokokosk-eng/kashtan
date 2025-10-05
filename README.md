# kashtan
Task executioner for projects with multi-root workspace 

## Description

The idea behind the kashtan is similar to [VS Code tasks](https://code.visualstudio.com/docs/debugtest/tasks). But the goal of this project is to reuse tasks of sub-projects from the super-project and to be able to unite different unrelated projects in one build script.

## Schema

The kashtan must support the following commands:
  
  - clear
  - setup
  - build
  - package

Basically, they are all describes the same kind of `tasks` objects. This means that you can put all tasks under the `clear` command but it will make less sence, than to put them under corresponding commands
