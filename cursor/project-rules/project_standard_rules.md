# Project Standards

This is the primary rules file that defines the structure for all projects' rules. Each project MUST contain two rule files:

1. **project_standard_rules.md**: Common rules shared across all projects (copy of this file)
2. **project_specific_rules.md**: Project-specific rules, patterns, and exceptions

All other rule files referenced here serve as templates and detailed guidelines that inform both standard and specific rules.

## Related Rule Files
- [Code Standards](code_rules.md) - Detailed coding practices and patterns
- [Directory Structure](directory_structure_rules.md) - Project organization and file hierarchy
- [Version Control](version_control_rules.md) - Git workflow and repository management
- [Testing Standards](testing_rules.md) - Test organization and quality assurance
- [Markdown](markdown_rules.md) - Documentation formatting and structure
- [AI Limitations](ai_limitations_rules.md) - Known operational limitations of the AI Assistant

## Project Health
   - Documentation completeness
   - Dependency updates
   - Security patches
   - Performance monitoring
   - Resource optimization

## Regular Maintenance
   - Documentation updates
   - Dependency management
   - Security audits
   - Performance reviews
   - Resource monitoring

## Project Organization

1. **Repository Structure**
   - Follow defined directory hierarchy
   - Maintain clean workspace
   - Group related files together
   - Use consistent naming conventions

2. **Resource Management**
   - Environment configurations
   - External service connections
   - API keys and secrets
   - Database management

3. **Dependency Management**
   - Version control
   - Compatibility checking
   - Security auditing
   - Update scheduling

## Cross-Project Standards

1. **Pattern Recognition**
   - Identify common code patterns
   - Document reusable solutions
   - Create shared utilities
   - Standardize approaches

2. **Best Practices**
   - Follow industry standards
   - Implement security measures
   - Use modern development practices
   - Keep up with technology trends

## Project Lifecycle

1. **Development Workflow**
   - Feature planning
   - Sprint organization
   - Release management
   - Deployment strategy

2. **Environment Management**
   - Development setup
   - Testing environment
   - Staging configuration
   - Production deployment

## Documentation

1. **Project Documentation**
   - README maintenance
   - Architecture documentation
   - API documentation
   - Deployment guides

2. **Process Documentation**
   - Development workflows
   - Setup procedures
   - Troubleshooting guides
   - Maintenance procedures

## Documentation Standards

1. **Rule Files Structure**
   - Clear section hierarchy
   - Consistent formatting
   - Comprehensive coverage
   - Practical examples

2. **Meta Section Pattern**
   - Source: references/cursor_rules/[filename]
   - Repository: https://github.com/phil71x/references (if applicable)
   - Parent: [parent_file] (if applicable)
   - Last Updated: YYYY-MM-DD

## AI Assistant Operational Note
Before attempting tasks, the AI Assistant will proactively consider its known operational limitations relevant to the request, as documented in [ai_limitations_rules.md](ai_limitations_rules.md). If any limitations prevent fulfilling the request directly or require user facilitation, the Assistant will state this clearly.

## Implementation Requirements
   - Every project MUST have two rule files:
     1. `project_standard_rules.md`: Copy of this file, containing common standards
     2. `project_specific_rules.md`: Project-specific rules and exceptions
   - project_standard_rules.md:
     - Must be an exact copy of this file
     - Cannot be modified directly in projects
     - Must be updated through references repository sync.
       **Note:** Due to AI limitations, the user must facilitate this sync (e.g., provide updated files from the repository).
     - Serves as the common foundation across all projects
   - project_specific_rules.md:
     - Must follow the same structure as this file
     - Can only extend or provide exceptions to standard rules
     - Must document and justify any deviations
     - Should reference relevant sections in project_standard_rules.md
   - Regular sync with references repository is mandatory, facilitated by the user.
   - New common patterns should be proposed to references repository.

## Meta
- Source: references/cursor/project-rules/project_standard_rules.md
- Repository: https://github.com/phil71x/references
- Last Updated: 2024-04-05 