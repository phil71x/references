# AI Assistant Operational Limitations

This document outlines known operational limitations of the AI Assistant.

## General Limitations

1. **No Real-Time Execution State:** Cannot maintain live execution state of the codebase. Relies on explicitly provided information through file reads and command outputs.

2. **No Long-Term Memory Across Sessions:** Context and instructions are limited to the current session.

3. **Potential for Misinterpretation:** May misinterpret complex or ambiguous instructions.

4. **Limited Creativity/Innovation:** Follows established patterns and instructions but may struggle with novel solutions.

5. **Tool Dependency:** Operations are limited to the specifically provided tools.

## Specific Limitations

1. **No Direct External Web/API Access:** Cannot directly browse websites, access external APIs, or read files from URLs (including public repositories). Note: MCP server implementation in progress to enable public repository access.

2. **No Direct GUI Interaction:** Cannot interact with graphical user interfaces or IDE features beyond provided tools.

## Meta
- Source: references/cursor/project-rules/ai_limitations_rules.md
- Repository: https://github.com/phil71x/references
- Last Updated: 2024-04-05 