# Cursor Rules Collection

This is a personal collection of Cursor rules inspired by Geoffrey Huntley's project [groundhog](https://github.com/ghuntley/groundhog/) project and his blog post on building a "stdlib" for Cursor AI. You can find the original article at [ghuntley.com/stdlib/](https://ghuntley.com/stdlib/).

## About This Collection

This repository contains a growing collection of Cursor rules that help automate and standardize development workflows. The rules are designed to be composed together like Unix pipes, creating a powerful set of automated tools and processes.

## Goal Structure Analysis

The goals in the original blog post are structured in several key ways:

1. **Location and Organization**
   - Rules are placed in `.cursor/rules/` directory
   - Files use `.mdc` extension
   - Naming follows kebab-case convention

2. **Rule Components**
   - Each rule has a clear name and description
   - Rules include filters for when they should be applied
   - Actions define what should happen when conditions are met
   - Examples are provided to demonstrate usage
   - Metadata includes priority and version information

3. **Composition Approach**
   - Rules are designed to work together
   - Each rule focuses on a specific task
   - Rules can be chained together for complex workflows

4. **Learning and Iteration**
   - Rules are updated based on learnings
   - Failed attempts are documented and corrected
   - Rules evolve to handle edge cases

## Getting Started

To use these rules:

1. Create a `.cursor/rules` directory in your project
2. Copy the desired rule files into this directory
3. Configure the rules according to your project's needs
4. Let Cursor AI use these rules to automate your development workflow

## Contributing

Feel free to contribute to this collection by:
- Adding new rules
- Improving existing rules
- Providing examples and documentation
- Suggesting improvements to rule structure

## License

This project is licensed under the GNU AFFERO GENERAL PUBLIC LICENSE. This license ensures that any modifications or extensions to this software must also be made available under the same terms, even when the software is accessed over a network.

For the full license text, please see the [LICENSE](LICENSE) file in this repository.

