# Version Control Rules

## Commit Guidelines

1. **Commit Types**
   - feat: New features or enhancements
   - fix: Bug fixes and corrections
   - docs: Documentation updates
   - style: Code style changes
   - refactor: Code restructuring
   - test: Test-related changes
   - chore: Maintenance tasks

2. **Commit Message Format**
```
type(scope): concise description

[optional body]

[optional footer]
```

3. **Message Guidelines**
   - Use present tense
   - Be descriptive but concise
   - Reference issues/PRs
   - Note breaking changes

## Branch Management

1. **Branch Types**
   - main: Primary branch
   - feature/*: New features
   - fix/*: Bug fixes
   - release/*: Release preparation

2. **Branch Workflow**
   - Create from latest main
   - Regular updates from main
   - Clean before merge
   - Delete after merge

3. **Protection Rules**
   - Protected branches
   - Required reviews
   - Status checks
   - Merge requirements

## Git Workflow

1. **Development Flow**
   - Pull latest changes
   - Create feature branch
   - Regular small commits
   - Push frequently

2. **Code Review**
   - Pull request creation
   - Review assignments
   - Feedback process
   - Merge procedures

3. **Conflict Resolution**
   - Update from main first
   - Resolve conflicts locally
   - Test after resolution
   - Document complex merges

## Repository Management

1. **Repository Setup**
   - Initialize with README
   - Add .gitignore
   - Configure branch protection
   - Set up CI/CD

2. **Maintenance**
   - Regular garbage collection
   - Remote pruning
   - Tag management
   - Release process

## Security

1. **Sensitive Data**
   - No credentials in code
   - Use .gitignore
   - Environment variables
   - Secrets management

2. **Access Control**
   - Repository visibility
   - Collaborator access
   - Deploy keys
   - Webhook security

## Best Practices

1. **General Guidelines**
   - Atomic commits
   - Clear history
   - Regular backups
   - Clean working tree

2. **Advanced Usage**
   - Interactive rebase
   - Cherry-picking
   - Bisect for debugging
   - Submodule management

## Meta
- Source: references/cursor_rules/version_control.md
- Repository: https://github.com/phil71x/references 