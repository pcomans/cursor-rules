# Cursor Rules Collection

This is a personal collection of Cursor rules inspired by Geoffrey Huntley's blog post on building a "stdlib" for Cursor AI. You can find the original article at [ghuntley.com/stdlib/](https://ghuntley.com/stdlib/).

## About This Collection

This repository contains a growing collection of Cursor rules that help automate and standardize development workflows. The rules are designed to be composed together like Unix pipes, creating a powerful set of automated tools and processes.

## Usage

To use these rules in your project:

1. Clone this repository:
   ```bash
   git clone https://github.com/pcomans/cursor-rules.git
   ```

2. Switch to the repository you want to use these rules in

3. Create a symlink to the rules in your project:
   ```bash
   # From your project root
   ln -s /path/to/cursor-rules/.cursor .cursor
   ```

4. Verify the symlink:
   ```bash
   ls -la .cursor/rules/
   ```

Now Cursor will use these rules when working with files in your project.

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

## Attribution

The `cursor-rules-location` rule in this collection is based on the implementation from [groundhog](https://github.com/ghuntley/groundhog/blob/trunk/.cursor/rules/cursor-rules-location.mdc) by Geoffrey Huntley. This rule establishes the standard structure and location for Cursor rules within a project.

The `scratch-task-planning` rule is based on the task planning methodology from [devin.cursorrules](https://github.com/grapeot/devin.cursorrules/blob/master/.cursorrules) by grapeot, which provides a structured approach to task organization and progress tracking.

## Contributing

Feel free to contribute to this collection by:
- Adding new rules
- Improving existing rules
- Providing examples and documentation
- Suggesting improvements to rule structure

## License

This project is licensed under the GNU AFFERO GENERAL PUBLIC LICENSE. This license ensures that any modifications or extensions to this software must also be made available under the same terms, even when the software is accessed over a network.

For the full license text, please see the [LICENSE](LICENSE) file in this repository.

