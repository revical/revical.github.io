<!-- Part of the Revical Project, under the MIT license. See '/LICENSE' for license information. SPDX-License-Identifier: MIT License. -->

# [revical.github.io](https://revical.github.io)

![Lines of Code](https://img.shields.io/github/languages/code-size/revical/revical.github.io)
[![Discord](https://img.shields.io/discord/1166348582689976411?label=discord)](https://discord.gg/djqx9Xzyjc)
[![WakaTime](https://wakatime.com/badge/user/b4317b02-0c6d-457b-82a4-a448b8a8d1df/project/018b6838-1bac-4195-820d-629beffd8116.svg)](https://wakatime.com/badge/user/b4317b02-0c6d-457b-82a4-a448b8a8d1df/project/018b6838-1bac-4195-820d-629beffd8116)


- [revical.github.io](#revicalgithubio)
  - [🛠️ Developer Documentation](#️-developer-documentation)
    - [🖥️ Environment Setup](#️-environment-setup)
    - [Cloning the Repository](#cloning-the-repository)
    - [Making Changes](#making-changes)

This is the repository containing the code for Revical's website. It is built using [Astro](https://astro.build/), and [Tailwind CSS](https://tailwindcss.com/).

> [!NOTE]\
> If you are a user, please visit [**`revical/revical`**](https://github.com/revical/revical). If you are a developer of this website, read on.


## 🛠️ Developer Documentation

### 🖥️ Environment Setup

> [!IMPORTANT]\
> GitHub Codespaces uses devcontainers to setup development environments. If you are using GitHub Codespaces, you can skip this section. This is because we have a devcontainer setup ready.

Requirements to setup the development environment for Revical's website:

- [**Git**](https://git-scm.com/downloads) - For cloning the repository.
- [**NPM**](https://www.npmjs.com/get-npm) - For installing dependencies.
  - Astro and Tailwind CSS are installed as dependencies.

### Cloning the Repository

To clone the repository, run the following command:

```bash
git clone https://github.com/revical/revical.github.io
cd revical.github.io
```

### Making Changes

Run **`npm run dev`** to start the development server. This will start the development server, which will be accessible at http://localhost:3000.

> [!NOTE]\
> NPM automatically monitors the directory for changes, and if it finds any, it rebuilds the application.