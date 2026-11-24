# EVERWELL Projectile Optimizer

**Less overhead. Smoother worlds.**

A lightweight Minecraft optimization mod focused on improving projectile and falling-block processing while preserving vanilla gameplay behavior.

Developed by **EVERWELL Studios**.

---

## Overview

EVERWELL Projectile Optimizer is a performance-focused Minecraft Fabric mod designed to reduce unnecessary processing associated with projectiles and falling blocks.

The goal is to improve performance without changing the gameplay mechanics players expect from vanilla Minecraft.

## Features

- Projectile processing optimization
- Falling-block processing optimization
- Configuration-controlled optimization systems
- Diagnostic reporting and performance metrics
- Compatibility-conscious architecture
- Automated testing and build verification

Features are considered available only when implemented and verified in the supported Minecraft environment.

## Compatibility

| Component | Target |
|---|---|
| Minecraft | 1.20.1 |
| Mod loader | Fabric |
| Java | 17 |
| Fabric API | Required |
| License | Apache-2.0 |

Additional versions and loaders will be announced only after testing.

## Installation

1. Install Minecraft 1.20.1.
2. Install a compatible Fabric Loader.
3. Install the required Fabric API version.
4. Download the appropriate Projectile Optimizer release.
5. Place the `.jar` file in your Minecraft `mods` folder.
6. Launch Minecraft using your Fabric installation.

Always check the release notes for version-specific requirements.

## Performance

Performance improvements are evaluated through controlled benchmarking.

Results should include:
- Minecraft and Java versions
- Entity counts and test conditions
- Baseline measurements
- Optimized measurements
- Any observed behavioral differences

Performance claims will be published only when supported by reproducible results.

## Development

This repository contains the source code, tests, documentation, and release history for EVERWELL Projectile Optimizer.

### Build

The project uses Gradle.

Run the automated tests:

```bash
./gradlew clean test
```

Build the mod:

```bash
./gradlew build
```

On Windows, use:

```powershell
.\gradlew.bat clean test
.\gradlew.bat build
```

The resulting artifacts are generated in the project's `build/libs/` directory.

## Bug Reports

If you encounter a problem:
1. Check existing GitHub issues.
2. Confirm your Minecraft and Fabric versions.
3. Include your mod list.
4. Attach relevant crash reports or logs.
5. Describe the steps required to reproduce the issue.

Use GitHub Issues for bug reports and feature requests.

## Contributing

Contributions are welcome.

Please review `CONTRIBUTING.md` before submitting a pull request. All contributions must respect the project's licensing and compatibility requirements.

## Security

Please report security vulnerabilities responsibly. See `SECURITY.md` for reporting instructions.

## License

This project is licensed under the Apache License 2.0.

See the `LICENSE` file for the complete license text.

## Links

- **Source code:** EVERWELL Studios GitHub organization
- **Downloads:** Official GitHub Releases
- **Modrinth:** Official project page (when published)
- **CurseForge:** Official project page (when published)

---

**EVERWELL Studios**

*Less overhead. Smoother worlds.*
