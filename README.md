# Learning Harness

Your agent gets better. You should too.

A local learning companion alongside your coding agent. It notices useful ideas in the work, offers questions and visual explanations, and keeps learner memory on your device. Learning requests use your existing host model connection and additional tokens from your allowance.

[Website](https://learningharness.dev) · [Install guide](https://learningharness.dev/install.md) · [Documentation](https://learningharness.dev/docs/)

## Install the public beta

**Start with the [canonical install guide](https://learningharness.dev/install.md).** You can paste this into Codex or Claude Code:

> Install LearningHarness using the instructions at https://learningharness.dev/install.md

The current beta packages are hosted on **learningharness.dev**, under its downloads directory. The [release manifest](https://learningharness.dev/install.json) lists the current package URLs, SHA-256 checksums, requirements and limitations for each host. The install guide uses that manifest to select and verify the right package. Use those links rather than guessing a version or download URL.

Codex desktop is public early access on macOS. Claude Code support is experimental. Follow the host-specific [Codex setup guide](https://learningharness.dev/docs/codex/) or [Claude Code setup guide](https://learningharness.dev/docs/claude-code/) for the current requirements and limitations.

For Codex, installation includes a **full desktop app restart and your review and approval of local hooks**. Installer success alone does not mean setup is complete. Follow the Codex guide through reopening the app, reviewing hooks and opening LearningHarness beside a fresh coding chat.

## What this repository contains

This is the public **distribution repository**, not the development source repository. The beta installers currently live on the website as described above; a package does not need to appear in this repository's [GitHub Releases](https://github.com/learningharness/learning-harness-plugins/releases) to be available through the canonical install guide.

Do not treat this repository as an installable plugin marketplace or invent an npm package name. The default GitHub **Source code** archives contain this distribution repository's documentation; they are not plugin installers.

A plugin package contains the files needed to run the local plugin: a host manifest, launcher, bundled runtime, prompts and UI, plus required notices. It excludes development history, internal evaluations and personal learner data.

Local code is inspectable. Public availability does not imply an open-source license. See the terms and third-party notices shipped with each package.

## Privacy and control

There is no Learning Harness backend receiving your code, prompts or learner answers. Selected work and learner context go through your existing host's model connection. Learning consumes additional allowance; memory stays local. Anonymous usage metadata is on by default when configured and can be disabled in Settings. Code, prompts and learner answers are excluded. Check the [privacy documentation](https://learningharness.dev/docs/privacy/) for the data flow.

## Feedback

Open an issue with your host version, plugin version, steps and a redacted screenshot. Do not post private code, learner memory, prompts, credentials or raw diagnostic logs.
