# Awesome iOS AI with stars

> Making AI coding assistants experts at Swift and iOS development.

AI coding tools write Swift like it is 2020. They use `ObservableObject` when `@Observable` exists. They ignore actor isolation. They produce views with no accessibility modifiers. Skills, agents, and MCP servers fix that by giving AI assistants expert-level Swift knowledge on demand.

## Contents

* [Skills](#skills)
* [Agents](#agents)
* [MCP Servers](#mcp-servers)
* [Tools](#tools)
* [Resources](#resources)

## Skills

[Agent Skills](https://agentskills.io/) are an open standard for giving AI coding agents specialized knowledge. Skills work across GitHub Copilot, Claude Code, Cursor, Codex, and more. Install any skill with the [skills CLI](https://skills.sh/docs/cli): `npx skills add <owner/repo@skill-name> -g -y`

### SwiftUI

* [SwiftUI Pro](https://github.com/twostraws/SwiftUI-Agent-Skill) ⭐ 4,452 | 🐛 11 | 📅 2026-04-20 - Modern APIs, accessibility, data flow, navigation, and performance.
* [SwiftUI Performance Audit](https://github.com/Dimillian/Skills/tree/main/swiftui-performance-audit) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - Diagnose slow rendering, janky scrolling, excessive view updates, and layout thrash.
* [SwiftUI View Refactor](https://github.com/Dimillian/Skills/tree/main/swiftui-view-refactor) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - Consistent view structure, MV patterns, @Observable usage, and dependency injection.
* [SwiftUI UI Patterns](https://github.com/Dimillian/Skills/tree/main/swiftui-ui-patterns) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - Component references for TabView, NavigationStack, Sheets, and view composition.
* [SwiftUI Liquid Glass](https://github.com/Dimillian/Skills/tree/main/swiftui-liquid-glass) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - iOS 26+ Liquid Glass API with `glassEffect`, `GlassEffectContainer`, and availability fallbacks.
* [SwiftUI Expert](https://github.com/AvdLee/SwiftUI-Agent-Skill) ⭐ 3,404 | 🐛 3 | 🌐 Python | 📅 2026-08-12 - State management, view composition, performance, and iOS 26+ Liquid Glass.

### Swift Concurrency

* [Swift Concurrency Expert](https://github.com/Dimillian/Skills/tree/main/swift-concurrency-expert) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - Swift 6.2+ actor isolation, data-race safety, and minimal-change fixes for compiler errors.
* [Swift Concurrency](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) ⭐ 1,615 | 🐛 6 | 📅 2026-08-12 - Async/await, actors, Sendable, and strict concurrency for Swift 6.

### Architecture

* [Swift Architecture](https://github.com/efremidze/swift-architecture-skill) ⭐ 65 | 🐛 0 | 🌐 Python | 📅 2026-08-04 - Select and apply MVP, MVVM, MVI, TCA, Clean Architecture, VIPER, Coordinator, and Reactive patterns with concrete playbooks, anti-pattern fixes, and review checklists.

### Data and Persistence

* [SwiftData](https://github.com/dpearson2699/swift-ios-skills/tree/main/skills/swiftdata) ⭐ 991 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - @Model schemas, @Query, predicates, relationships, and migration patterns.
* [Core Data Expert](https://github.com/AvdLee/Core-Data-Agent-Skill) ⭐ 295 | 🐛 2 | 📅 2026-08-07 - Data modeling, fetch requests, CloudKit sync, migration, and performance.

### Testing

* [Swift Testing Expert](https://github.com/AvdLee/Swift-Testing-Agent-Skill) ⭐ 435 | 🐛 4 | 📅 2026-08-07 - Modern Swift Testing framework with `#expect`, `#require`, traits, tags, parameterized tests, and XCTest migration.

### Debugging

* [iOS Debugger Agent](https://github.com/Dimillian/Skills/tree/main/ios-debugger-agent) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - Build, run, and debug iOS apps on simulators via XcodeBuildMCP.

### AI and Machine Learning

* [Apple On-Device AI](https://github.com/dpearson2699/swift-ios-skills/tree/main/skills/apple-on-device-ai) ⭐ 991 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - Foundation Models, on-device inference, and Apple Intelligence integration.

### Design and Platform

* [iOS HIG](https://github.com/johnrogers/claude-swift-engineering/tree/main/plugins/swift-engineering/skills/ios-hig) ⭐ 225 | 🐛 3 | 🌐 Python | 📅 2026-01-18 - Apple Human Interface Guidelines compliance checks.
* [iOS 26 Platform](https://github.com/johnrogers/claude-swift-engineering/tree/main/plugins/swift-engineering/skills/ios-26-platform) ⭐ 225 | 🐛 3 | 🌐 Python | 📅 2026-01-18 - Platform APIs and patterns for iOS 26.

### App Frameworks

* [App Intents](https://github.com/dpearson2699/swift-ios-skills/tree/main/skills/app-intents) ⭐ 991 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - Siri, Shortcuts, and App Intents framework integration.
* [Live Activities](https://github.com/dpearson2699/swift-ios-skills/tree/main/skills/live-activities) ⭐ 991 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - Dynamic Island and Lock Screen live updates with ActivityKit.
* [WidgetKit](https://github.com/dpearson2699/swift-ios-skills/tree/main/skills/widgetkit) ⭐ 991 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - Home Screen and Lock Screen widget development.

### Workflow and Automation

* [App Store Changelog](https://github.com/Dimillian/Skills/tree/main/app-store-changelog) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - Generate App Store release notes from Git history.
* [GH Issue Fix Flow](https://github.com/Dimillian/Skills/tree/main/github) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - End-to-end GitHub issue resolution with read, fix, build, test, and push.
* [macOS SwiftPM Packaging](https://github.com/Dimillian/Skills/tree/main/macos-spm-app-packaging) ⭐ 3,900 | 🐛 11 | 🌐 Shell | 📅 2026-03-29 - Scaffold, build, and package SwiftPM macOS apps without Xcode.

### Accessibility

* [iOS Accessibility](https://github.com/dpearson2699/swift-ios-skills/tree/main/skills/ios-accessibility) ⭐ 991 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - VoiceOver support, accessibility modifiers, and Dynamic Type patterns for iOS.

### WebAssembly

* [SwiftWasm Skills](https://github.com/swiftwasm/skills) ⭐ 47 | 🐛 0 | 🌐 Python | 📅 2026-08-10 - Swift on WebAssembly with JavaScript interop, BridgeJS, and compatibility checks.

## Agents

* [Claude Swift Engineering](https://github.com/johnrogers/claude-swift-engineering) ⭐ 225 | 🐛 3 | 🌐 Python | 📅 2026-01-18 - Eleven agents for planning, implementing, reviewing, and testing Swift and TCA code.
* [Swift Agents](https://github.com/Techopolis/swift-agents) ⭐ 32 | 🐛 5 | 🌐 Shell | 📅 2026-04-25 - Sixteen orchestrated specialists covering concurrency, SwiftUI, accessibility, security, testing, StoreKit, SwiftData, visionOS, Core ML, MLX, and Foundation Models.

## MCP Servers

* [awesome-copilot MCP](https://github.com/github/awesome-copilot) ⭐ 37,786 | 🐛 40 | 🌐 Python | 📅 2026-08-13 - Search and install agents, skills, and MCP servers from GitHub.
* [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) ⭐ 6,229 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-12 - Build, run, test, and debug Xcode projects from AI agents.
* [MCP Swift SDK](https://github.com/modelcontextprotocol/swift-sdk) ⭐ 1,463 | 🐛 95 | 🌐 Swift | 📅 2026-05-07 - Official Swift SDK for building MCP servers and clients.
* [Apple Docs MCP](https://github.com/kimsungwhee/apple-docs-mcp) ⭐ 1,358 | 🐛 14 | 🌐 TypeScript | 📅 2026-03-17 - Search Apple developer documentation, WWDC videos, and Swift API references from AI assistants.
* [Xcode MCP Server](https://github.com/r-huijts/xcode-mcp-server) ⭐ 385 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-02 - Xcode project management, simulator control, and build automation for AI assistants.
* [Swift Patterns MCP](https://github.com/efremidze/swift-patterns-mcp) ⭐ 12 | 🐛 27 | 🌐 TypeScript | 📅 2026-06-20 - Swift and SwiftUI best practices from leading iOS developers with intelligent search across YouTube, Patreon, and other sources.

## Tools

* [Copilot for Xcode](https://github.com/github/CopilotForXcode) ⭐ 6,260 | 🐛 225 | 🌐 Swift | 📅 2026-08-12 - GitHub Copilot extension for Xcode with agent mode, completions, and code review.

## Resources

* [skills.sh](https://skills.sh) - Searchable directory of all agent skills with install counts and security audits.
* [Agent Skills Specification](https://agentskills.io/specification) - The open standard for building agent skills.
* [VS Code Copilot Customization](https://code.visualstudio.com/docs/copilot/copilot-customization) - Official guide for workspace instructions, agents, prompts, hooks, and skills.
* [The State of Agentic iOS Engineering](https://dimillian.medium.com/the-state-of-agentic-ios-engineering-in-2026-c5f0cbaa7b34) - Overview of AI-assisted iOS development in 2026.

## Contributing

Contributions welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

## Footnotes

Created by [Taylor Arndt](https://github.com/taylorarndt). Maintained by [Techopolis](https://github.com/Techopolis).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
