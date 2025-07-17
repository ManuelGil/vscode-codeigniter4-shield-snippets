# CodeIgniter 4 Shield Snippets

[![VS Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-codeigniter4-shield-snippets?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-codeigniter4-shield-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-codeigniter4-shield-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-codeigniter4-shield-snippets?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets&ssr=false#review-details)
[![GitHub Stars](https://img.shields.io/github/stars/ManuelGil/vscode-codeigniter4-shield-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets)
[![License](https://img.shields.io/github/license/ManuelGil/vscode-codeigniter4-shield-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets/blob/main/LICENSE)

> Comprehensive snippet support and autocomplete for CodeIgniter 4's Shield authentication and authorization module.

## Overview

CodeIgniter 4's Shield library provides a robust foundation for authentication, authorization, and token management. This extension delivers over 80 context‑aware snippets and autocomplete entries for all common Shield methods, reducing lookup time and ensuring consistent, error‑free code.

## Getting Started

1. Ensure your project uses **CodeIgniter 4.3.0** or later.
2. Install **Visual Studio Code** version 1.46.0 or higher (or a compatible editor such as VSCodium).
3. Navigate to the **Extensions** view in VS Code (`Ctrl+Shift+X` on Windows/Linux or `⌘+Shift+X` on macOS).
4. Search for **CodeIgniter 4 Shield Snippets** or install directly from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets).
5. Reload VS Code to activate the extension.

## Features

- **Authentication Snippets**
  Snippets for `auth()->login()`, `auth()->logout()`, `auth()->user()`, `auth()->id()`, and more.
- **Token Management**
  Support for access and HMAC token generation, revocation, and inspection.
- **Group & Permission Handling**
  Snippets for adding, removing, syncing groups and permissions, and checking roles.
- **User Lifecycle Methods**
  Autocomplete for `$user->activate()`, `$user->ban()`, and related methods.
- **Context‑Aware Autocomplete**
  Snippets appear only in PHP files and under appropriate contexts.

## Usage

Type the snippet prefix in a PHP file and press **Tab** or **Enter** to expand:

```php
// Example: Insert login snippet
ci:auth:login
// expands to:
auth()->login();
```

A selection of prefixes:

| Prefix                        | Expands To                                                                                                                  |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| `ci:auth:login`               | `auth()->login()`                                                                                                           |
| `ci:auth:logout`              | `auth()->logout()`                                                                                                          |
| `ci:auth:user`                | `auth()->user()`                                                                                                            |
| `ci:auth:generateAccessToken` | `generateAccessToken()`                                                                                                     |
| `ci:auth:addGroup`            | `addGroup()`                                                                                                                |
| `ci:auth:hasPermission`       | `hasPermission()`                                                                                                           |
| `ci:auth:isActivated`         | `$user->isActivated()`                                                                                                      |

## Contributing

CodeIgniter 4 Shield Snippets is open-source and welcomes community contributions:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets).
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request against the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. Open an Issue if you find a bug or want to request a new feature.

## Code of Conduct

We are committed to providing a friendly, safe, and welcoming environment for all, regardless of gender, sexual orientation, disability, ethnicity, religion, or other personal characteristic. Please review our [Code of Conduct](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets/blob/main/CODE_OF_CONDUCT.md) before participating in our community.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

See also the list of [contributors](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets/contributors) who participated in this project.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-codeigniter4-shield-snippets/blob/main/LICENSE) file for details.
