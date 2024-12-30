# MCP Claude Client

Modern macOS MCP client for Claude with elegant SwiftUI interface and plugin support.

## Features

- Native macOS interface with SwiftUI
- Full MCP protocol support
- Plugin system (wcgw, webresearch, sequentialthinking)
- Elegant and intuitive design

## Development

### Requirements

- macOS 13.0+
- Xcode 15.0+
- Swift 5.9+

### Setup

1. Clone the repository
2. Open MCPClaudeClient.xcodeproj in Xcode
3. Build and run

## Architecture

```
MCPClaudeClient/
├── Sources/
│   ├── Core/
│   │   ├── MCPClient.swift       # MCP protocol implementation
│   │   └── PluginManager.swift   # Plugin system management
│   ├── Views/
│   │   ├── ContentView.swift     # Main view container
│   │   ├── ChatView.swift        # Chat interface
│   │   ├── PluginsView.swift     # Plugin management
│   │   └── SettingsView.swift    # App settings
│   └── main.swift                # App entry point
└── Tests/
    └── MCPClaudeClientTests/     # Unit tests
```

## License

MIT