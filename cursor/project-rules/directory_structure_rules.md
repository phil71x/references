# Directory Structure Standards

## Project Root Structure
```
project_root/
├── .cursor/              # Cursor-specific configurations
│   ├── rules/           # Project rules and standards
│   └── settings.json    # Cursor IDE settings
├── src/                 # Source code
│   ├── components/      # Reusable components
│   ├── utils/          # Utility functions
│   ├── services/       # Service integrations
│   └── types/          # Type definitions
├── tests/              # Test files
│   ├── unit/          # Unit tests
│   ├── integration/   # Integration tests
│   └── e2e/           # End-to-end tests
├── docs/              # Documentation
│   ├── api/          # API documentation
│   ├── setup/        # Setup guides
│   └── architecture/ # Architecture docs
├── scripts/          # Build and utility scripts
├── config/           # Configuration files
├── .github/          # GitHub specific files
├── notes/            # Project notes and records
│   ├── experiments/  # Experiment documentation
│   ├── features/    # Feature development notes
│   ├── bugs/       # Bug tracking and fixes
│   └── meta/       # Process documentation
└── fixes/          # Solutions to major issues
```

## Language-Specific Structures

1. **Python Projects**
```
project_root/
├── src/
│   └── package_name/
│       ├── __init__.py
│       ├── core/
│       ├── utils/
│       └── cli/
├── tests/
├── docs/
└── requirements/
    ├── base.txt
    ├── dev.txt
    └── prod.txt
```

2. **Node.js Projects**
```
project_root/
├── src/
│   ├── components/
│   ├── hooks/
│   ├── contexts/
│   └── styles/
├── public/
├── tests/
└── config/
    ├── webpack/
    └── jest/
```

## Environment-Specific Directories

1. **Development**
```
project_root/
├── .vscode/        # VS Code settings
├── .idea/         # IntelliJ settings
└── .env.dev      # Development environment variables
```

2. **Production**
```
project_root/
├── dist/         # Compiled code
├── build/       # Build artifacts
└── .env.prod   # Production environment variables
```

## Special Purpose Directories

1. **Version Control**
```
project_root/
├── .git/
├── .github/
│   ├── workflows/
│   └── ISSUE_TEMPLATE/
└── .gitignore
```

2. **Documentation**
```
project_root/
├── docs/
│   ├── _static/
│   ├── _templates/
│   └── _build/
└── README.md
```

## Directory Naming Conventions

1. **Standard Names**
   - Use lowercase for directories
   - Use hyphens for multi-word names
   - Prefix tool configs with dot
   - Use clear, descriptive names

2. **Special Cases**
   - Component directories: PascalCase
   - Test directories: match source
   - Generated directories: camelCase
   - Temporary directories: prefix with underscore

## Implementation Guidelines

1. **Directory Creation**
   - Create directories as needed
   - Remove empty directories
   - Keep structure flat when possible
   - Maximum depth of 4 levels

2. **Directory Management**
   - Regular cleanup of temp files
   - Archive unused directories
   - Document special directories
   - Maintain README files

## Meta
- Source: references/cursor_rules/directory_structure.md
- Repository: https://github.com/phil71x/references 