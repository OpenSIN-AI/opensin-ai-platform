# OpenSIN Code

![](https://img.shields.io/badge/Node.js-18%2B-brightgreen?style=flat-square) [![npm]](https://www.npmjs.com/package/@opensin-ai/opensin-code)

[npm]: https://img.shields.io/npm/v/@opensin-ai/opensin-code.svg?style=flat-square

OpenSIN Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows -- all through natural language commands. Use it in your terminal, IDE, or tag @opensin on Github.

**Learn more in the [official documentation](https://code.opensin.com/docs/en/overview)**.

<img src="./demo.gif" />

## Get started
> [!NOTE]
> Installation via npm is deprecated. Use one of the recommended methods below.

For more installation options, uninstall steps, and troubleshooting, see the [setup documentation](https://code.opensin.com/docs/en/setup).

1. Install OpenSIN Code:

    **MacOS/Linux (Recommended):**
    ```bash
    curl -fsSL https://opensin.ai/install.sh | bash
    ```

    **Homebrew (MacOS/Linux):**
    ```bash
    brew install --cask opensin-code
    ```

    **Windows (Recommended):**
    ```powershell
    irm https://opensin.ai/install.ps1 | iex
    ```

    **WinGet (Windows):**
    ```powershell
    winget install OpenSIN.OpenSINCode
    ```

    **NPM (Deprecated):**
    ```bash
    npm install -g @opensin-ai/opensin-code
    ```

2. Navigate to your project directory and run `opensin`.

## Plugins

This repository includes several OpenSIN Code plugins that extend functionality with custom commands and agents. See the [plugins directory](./plugins/README.md) for detailed documentation on available plugins.

## Reporting Bugs

We welcome your feedback. Use the `/bug` command to report issues directly within OpenSIN Code, or file a [GitHub issue](https://github.com/opensins/opensin-code/issues).

## Connect on Discord

Join the [OpenSIN Developers Discord](https://opensin.com/discord) to connect with other developers using OpenSIN Code. Get help, share feedback, and discuss your projects with the community.

## Data collection, usage, and retention

When you use OpenSIN Code, we collect feedback, which includes usage data (such as code acceptance or rejections), associated conversation data, and user feedback submitted via the `/bug` command.

### How we use your data

See our [data usage policies](https://code.opensin.com/docs/en/data-usage).

### Privacy safeguards

We have implemented several safeguards to protect your data, including limited retention periods for sensitive information, restricted access to user session data, and clear policies against using feedback for model training.

For full details, please review our [Commercial Terms of Service](https://www.opensin.com/legal/commercial-terms) and [Privacy Policy](https://www.opensin.com/legal/privacy).
