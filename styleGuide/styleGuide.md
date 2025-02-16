# YAML Tags

These tags are at the top of each .md file and are written in YAML. These are the tags we suggest modules require but it is very easy to add additional categories if required

## id

A unique identifier for each module

## Title

The heading for the module that gives a brief overview of the task

## Tags

A short list of buzz words that relate to what the task involves e.g language, backend/frontend

## Dependencies

A list of modules that are required to be completed before attempting this task

# Example

```c
//YAML inside the --- describes the module for our JSON

---
id: Module2
title: Exploring Java and React
tags:
  - Java
  - React
dependencies:
  - Module1
---

//Everything below is the body of the module

# Heading For Module Body

Lorem ipsum dolor sit amet, _consectetur_ adipisicing elit, sed do eiusmod
tempor incididunt ut **labore et dolore magna aliqua**. Ut enim ad minim veniam

## Another Heading For Task

Lorem ipsum dolor sit amet, _consectetur_ adipisicing elit, sed do eiusmod
consequat.

[Link to repo](https://github.com)
```
