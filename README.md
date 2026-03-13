# LineSpec Homebrew Tap

Homebrew formulas for installing [LineSpec](https://github.com/livecodelife/linespec).

## Installation

```bash
# Tap this repository
brew tap livecodelife/linespec

# Install the stable version (Provenance Records only)
brew install linespec

# Or install the beta version (includes LineSpec Testing)
brew install linespec-beta
```

## Available Formulas

| Formula | Description | Status |
|---------|-------------|--------|
| `linespec` | Provenance Records - Structured YAML artifacts for documenting architectural decisions | ✅ Stable (v1.0.0) |
| `linespec-beta` | Provenance Records + Integration Testing features | 🚧 Beta |

## About LineSpec

**Provenance Records (v1.0.0 - Stable):**
- Structured YAML artifacts for architectural decisions
- Git integration with commit validation
- Scope enforcement and graph visualization
- CLI tooling for creation, linting, and management

**LineSpec Testing (Beta):**
- DSL-based integration testing
- Protocol-level proxy interception (MySQL, PostgreSQL, HTTP, Kafka)
- Containerized service testing

## Documentation

- [LineSpec Repository](https://github.com/livecodelife/linespec)
- [PROVENANCE_RECORDS.md](https://github.com/livecodelife/linespec/blob/main/PROVENANCE_RECORDS.md) - Complete provenance reference
- [README.md](https://github.com/livecodelife/linespec/blob/main/README.md) - Installation and quick start
- [LINESPEC.md](https://github.com/livecodelife/linespec/blob/main/LINESPEC.md) - Integration testing reference (beta)

## Updating

```bash
# Update the tap
brew update

# Upgrade to the latest version
brew upgrade linespec

# Or upgrade the beta version
brew upgrade linespec-beta
```

## Uninstalling

```bash
# Uninstall stable version
brew uninstall linespec
brew untap livecodelife/linespec

# Or uninstall beta version
brew uninstall linespec-beta
brew untap livecodelife/linespec
```

## How This Works

This repository is automatically updated by [GoReleaser](https://goreleaser.com/) whenever a new release is published in the [LineSpec repository](https://github.com/livecodelife/linespec). The formula files are generated and committed automatically - you don't need to manually update them.

## Support

- **Issues:** https://github.com/livecodelife/linespec/issues
- **Discussions:** https://github.com/livecodelife/linespec/discussions
- **Releases:** https://github.com/livecodelife/linespec/releases

## License

MIT License - See [LICENSE](https://github.com/livecodelife/linespec/blob/main/LICENSE) in the main repository.
