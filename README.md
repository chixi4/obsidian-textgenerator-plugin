<h1 align="center">obsidian-textgenerator-plugin</h1>

<div align="center">
  <a href="https://bit.ly/tg_docs">Documentation</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://discord.gg/mEhvhkRfq5">Discord</a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="https://img.shields.io/twitter/follow/TextGenPlugin?style=social)](https://twitter.com/intent/follow?screen_name=TextGenPlugin">Twitter</a>
  <br />
  <br />
  <br />
</div>

## Fork Branch Changes vs Upstream

This repository has a fork branch named `fix-ai-callout-margin`.

### What changed in this fork branch

Compared with upstream before merge, this branch contains one functional UI fix:

- Commit: `251b05e1ccf2d56165b13d57c99329a900a1f9a0`
- Date: 2026-01-08
- Author: chixi4
- File: `src/css/global.css`
- Change:
  - `.callout[data-callout="ai"] > .callout-title` `margin-left` changed from `-1rem` to `0`
  - `.callout[data-callout="ai"] > .callout-content` `margin-left` changed from `2rem` to `0`

### Why this change was made

The previous margin settings caused abnormal indentation in AI callout blocks.  
This fix removes the offset so callout title and content align correctly in Obsidian.

### Current upstream status

- This branch change is already merged upstream:
  - Upstream merge commit: `2e5e7d07e30663efdd787e19fe864ae0a7ff8a96`
  - PR: `#375`
- As of 2026-02-11, the branch itself has no extra patch beyond upstream merge content.

## What is Text Generator?

**Text Generator** is an open-source AI Assistant Tool that brings the power of Generative Artificial Intelligence to the power of knowledge creation and organization in Obsidian.

For example, use Text Generator to generate ideas, attractive titles, summaries, outlines, and whole paragraphs based on your knowledge database.

The possibilities are endless!

If you're looking for a place to discuss the use cases of this plugin and share your experiences, head over to our [**Discord Server (Updated)**](https://discord.gg/BRYqetyjag) or the [Discussion](https://github.com/nhaouari/obsidian-textgenerator-plugin/discussions/categories/use-cases). There, you'll find a community of like-minded users who are eager to help you make the most of this powerful tool.

## Features

There are many benefits to using a Text Generator Plugin, including the following:

- **Free and Open Source**: The Text Generator Plugin is free and open source, so you can use it without worrying about licensing fees.

- **Beside Obsidian**: Obsidian is very powerful and extensible Personal Knowledge Management software so you can use Text Generator Plugin alongside Obsidian to create a more powerful Personal Knowledge Management system.

- **Flexible Prompts**: The context of the prompt is straightforward using all the available options in the Considered Context which gives you a higher flexibility.

- **Template Engine**: You can create templates to make repetitive tasks more manageable.

- **Community Templates**: Through this option you can discover new use cases of Generative Artificial Intelligence using the shared templates and you can share your use cases easier.

- **Highly Flexible Configuration**: Using Frontmatter Configuration, it is possible to use different services such as Google Generative AI(contains `Gemini-Pro`), OpenAI, HuggingFace ...etc.

## Demonstration

[![Youtube Demonstration](https://img.youtube.com/vi/OergqWCdFKc/0.jpg)](https://www.youtube.com/watch?v=OergqWCdFKc)


## Installation

### Method 1: From Obsidian Community Plugins

1. Open Obsidian
2. Go to Settings > Community plugins
3. Turn off Safe mode if it's on
4. Click on "Browse" and search for "Text Generator"
5. Click Install and then Enable

### Method 2: Manual Installation

If you prefer to install the plugin manually or want to use the latest development version:

1. Clone this repository to your Obsidian vault's plugins folder:
   ```bash
   git clone https://github.com/nhaouari/obsidian-textgenerator-plugin.git
   ```

2. Navigate to the plugin directory:
   ```bash
   cd obsidian-textgenerator-plugin
   ```

3. Install dependencies:
   ```bash
   pnpm install
   ```

4. Build the plugin:
   ```bash
   pnpm run build
   ```

   Alternatively, for development:
   ```bash
   pnpm run dev
   ```


5. Restart Obsidian and enable the plugin in Settings > Community plugins
   
   Alternatively, You can use the [Hot-Reload plugin](https://github.com/pjeby/hot-reload) to reload plugins without restarting Obsidian

### Troubleshooting

If you encounter any issues during installation, please:
- Check our [documentation](https://bit.ly/tg_docs)
- Join our [Discord server](https://discord.gg/mEhvhkRfq5) for community support
- Open an issue on our [GitHub repository](https://github.com/nhaouari/obsidian-textgenerator-plugin/issues)



## Contributors

<a href="https://github.com/nhaouari/obsidian-textgenerator-plugin/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=nhaouari/obsidian-textgenerator-plugin" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

