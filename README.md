# `harper-obsidian-plugin`

The Harper plugin is a powerful, privacy-first grammar and spell-checking tool designed specifically for Obsidian users. Unlike many other grammar checkers, Harper operates entirely offline, ensuring your data remains secure while providing real-time, high-performance corrections. This plugin is ideal for writers, academics, and developers who value privacy and efficiency in their workflows.

![A screenshot of Obsidian with Harper installed](./screenshot.webp)

## Key Features

### Privacy-Focused

- Harper runs entirely on your device, meaning no data is sent to external servers.
- Unlike tools like Grammarly or LanguageTool (when not self-hosted), Harper ensures complete ownership and confidentiality of your notes.

### Real-Time Grammar and Spell Checking

- The plugin automatically scans your text as you type, highlighting grammatical errors, spelling mistakes, and stylistic inconsistencies.
- Hovering over an error provides instant suggestions for corrections, making editing seamless.

### Lightweight and Fast

- Built with performance in mind, Harper delivers corrections in milliseconds without slowing down even large vaults.
- It has a minimal memory footprint compared to alternatives like LanguageTool, which can require significant resources.

### Open Source

- Harper is fully open source, allowing transparency and community contributions to improve its functionality.
- Developers can review the codebase or contribute directly via the [GitHub repository](https://github.com/automattic/harper-obsidian-plugin).

## How It Compares to Other Plugins

| Feature                | Harper                        | LanguageTool                      |
| ---------------------- | ----------------------------- | --------------------------------- |
| **Privacy**            | 100% offline                  | Requires self-hosting for privacy |
| **Real-Time Checking** | Yes                           | Yes                               |
| **Language Support**   | American English (extensible) | 30+ languages                     |
| **Open Source**        | Yes                           | Partially                         |
| **Ease of Use**        | Simple setup                  | Requires API/self-hosting setup   |
| **Performance**        | Fast and lightweight          | Resource-intensive                |

## Installation Guide

1. Open Obsidian and navigate to **Settings → Community Plugins → Browse**.
2. Search for "Harper" in the plugin library.
3. Click "Install" and then "Enable."
4. Start typing in your notes—Harper will automatically highlight errors as you go!

> **Warning**
> Harper expects an up-to-date version of Electron. If you have issues, [reinstall Obsidian](https://obsidian.md/download) or otherwise update your Electron version.

## Future Development

The team behind Harper welcomes feedback and [contributions from the community](https://github.com/automattic/harper). Planned updates include:

- Support for additional languages.
- Advanced customization options for grammar rules.
- Improved performance for extremely large documents.

## Why Choose Harper?

Harper stands out as a reliable, private, and efficient grammar checker tailored to Obsidian users' needs. Whether you're drafting essays, documenting code, or simply jotting down ideas, Harper ensures your writing is polished without sacrificing speed or security.

For more details or to contribute to the project, visit the [GitHub page](https://github.com/automattic/harper).

## Where's all the code?

All of the code for the Harper Obsidian plugin lives [in the main Harper monorepo](https://github.com/automattic/harper/tree/master/packages/obsidian-plugin).
This repository exists to satisfy the [requirements](https://docs.obsidian.md/Plugins/Releasing/Submit+your+plugin) laid out by the Obsidian team for their plugins.

## I have a problem or feature request...

Let me know if you have any problems, feature requests, or feedback of any kind by filling out an [issue on the main repository](https://github.com/automattic/harper/issues/new).
