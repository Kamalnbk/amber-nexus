# About the project
This project has no affiliation or endorsement by ElevenLabs. This is a fork and is independently maintained.


# AmberNexus Agents SDK

Build multimodal agents with the [AmberNexus Agents platform](). 

![LOGO](./assets/logo.svg)

Our SDKs provide seamless integration with popular JavaScript/TypeScript frameworks, enabling you to create multimodal AI agents.


## Overview

The AmberNexus Agents SDKs provide a unified interface for integrating multimodal AI agents into your applications.

### Available Packages

| Package                                               | Description                                      | Version                                                                                                                               | Links                                                                                                                 |
| ----------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| [`@ambernexus/client`](#ambernexusclient)             | Core TypeScript/JavaScript client                | [![npm](https://img.shields.io/npm/v/@ambernexus/client)](https://www.npmjs.com/package/@ambernexus/client)                           | [README](packages/client/README.md) • [Docs](https://ambernexus.io/docs/agents-platform/libraries/java-script)        |

## Package Details

### @ambernexus/client

The core TypeScript/JavaScript client provides the foundation for all AmberNexus agent integrations.

#### Features

- **Real-time Communication**: WebRTC-based audio streaming for low-latency agent interactions
- **Event-driven Architecture**: Comprehensive event system for agent session lifecycle management
- **Client Tools**: Support for custom client-side tools and functions
- **Flexible Authentication**: Support for both public and private agent configurations
- **Audio Controls**: Fine-grained control over audio input/output devices

#### Installation

```bash
npm install @ambernexus/client
```

## Documentation

For detailed documentation, visit:

- [TypeScript/JavaScript Client API](packages/client/README.md)

## Support

- [Support Email](mailto:ambernexus-support@myambergroup.com)

### Development Setup

This project uses [Turbo](https://turborepo.com) and pnpm to manage dependencies.

```bash
# Install pnpm globally
npm install -g pnpm

# Install dependencies
pnpm install

# Build all packages
pnpm run build

# Run tests
pnpm run test

# Start development mode
pnpm run dev
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Attribution:
Portions of this software are © ElevenLabs, used under license.
