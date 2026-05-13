# Label Organization Guide

## Label Categories

| Label Name | Category | Description |
| ---------- | -------- | ----------- |
| bug | issue-type | Something isn't working |
| enhancement | issue-type | New feature or request |
| duplicate | issue-type | This issue or pull request already exists |
| question | issue-type | Further information is requested |
| documentation | issue-type | Improvements or additions to documentation |
| platform:macos | platform | Affects macOS platform |
| platform:linux | platform | Affects Linux platform |
| platform:windows | platform | Affects Windows platform |
| area:core | area | Core functionality |
| area:tools | area | Tools and integrations |
| area:tui | area | Terminal user interface |
| area:ide | area | IDE integration |
| area:mcp | area | Model Context Protocol |
| area:api | area | API layer |
| area:security | area | Security related |
| area:model | area | Model behavior or configuration |
| area:auth | area | Authentication and authorization |
| area:packaging | area | Packaging and distribution |
| has repro | status | Issue has a reproducible test case |
| memory | area | Memory-related issue |
| perf:memory | performance | Memory performance issue |
| external | status | External dependency or upstream issue |

## Usage Guidelines

### issue-type labels
Use these labels to classify the nature of the issue or pull request:
- **bug**: Apply when reporting something that isn't working as expected
- **enhancement**: Apply when requesting a new feature or improvement
- **duplicate**: Apply when the issue or PR already exists elsewhere
- **question**: Apply when seeking clarification or further information
- **documentation**: Apply when the issue or PR relates to docs improvements

### platform labels
Use platform labels to indicate which operating system is affected:
- **platform:macos**: Issues specific to macOS
- **platform:linux**: Issues specific to Linux
- **platform:windows**: Issues specific to Windows

### area labels
Use area labels to identify which part of the codebase is affected:
- **area:core**: Issues affecting core functionality
- **area:tools**: Issues related to tools and integrations
- **area:tui**: Issues related to the terminal user interface
- **area:ide**: Issues related to IDE integration
- **area:mcp**: Issues related to the Model Context Protocol
- **area:api**: Issues affecting the API layer
- **area:security**: Security-related issues
- **area:model**: Issues related to model behavior or configuration
- **area:auth**: Issues related to authentication and authorization
- **area:packaging**: Issues related to packaging and distribution
- **memory**: Issues related to memory usage

### status labels
Use status labels to provide additional context about the issue state:
- **has repro**: Apply when a reproducible test case is available
- **external**: Apply when the issue is caused by an external dependency or upstream problem

### performance labels
Use performance labels to track performance-related concerns:
- **perf:memory**: Apply when the issue involves memory performance problems
