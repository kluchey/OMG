# Contribute to the Project

## Feedback

Please email k@cluchey.ca with corrections, better examples or problems, or ideas to make this project better.

## Cup of Tea

You can provide a small donation to the project to help keep the author(s) motivated. E-transfer to k@cluchey.ca.

## Content

### You will need:
* A Github Account and [Github Desktop](https://desktop.github.com/) software
* A Markdown software (such as [Obsidian](https://obsidian.md))
* A tried and tested lesson or problem to contribute, or
* A penchant for writing documentation

### Instructions
1. Fork a copy of the Github Repository for this project (found here: https://github.com/kluchey/ont-math-graph)
2. Clone your forked repository using Github Desktop to your local machine
3. Import the project into your Markdown software (such as a Vault in Obsidian)
4. Make changes
5. Push changes to your repository using Github Desktop
6. Optional:  If you want to share changes to the official branch, initiate a pull request with my repo

### Markdown Rules for the Math Graph

These are helpful markdown syntax that allow me to publish this resource in HTML with Material for MkDocs

#### Snippets

Sections in .md files that should be referenced dynamically in other .md files should contain Snippets. Here is the rule:
	\--8<-- \[start:name]
	Surround a referenceable section with start and end snippet codes seen here.
	\--8<-- \[end:name]
	After this section is named, you can reference the absolute path in another OMG file by using:
	\--8<-- "path\\to\\\file.md:name"