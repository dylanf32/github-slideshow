# GitHub Slideshow — Learning Repository

A GitHub Learning Lab exercise for practicing commits and pull requests through a Markdown slide presentation.

**Stack:** Markdown · Jekyll · reveal.js  
**Purpose:** learning exercise, rather than a standalone portfolio application.

## Contents

| Path | Purpose |
| --- | --- |
| `_posts/` | Introductory and personal slides |
| `_layouts/`, `_includes/` | Presentation templates |
| `_config.yml` | Jekyll configuration |
| `node_modules/reveal.js/` | Checked-in presentation assets |
| `script/` | Setup, preview, and build helpers |

## Local preview

With Ruby and Bundler installed, run from the repository root:

```bash
sh script/setup
sh script/server
```

These are legacy course scripts and use the dependency versions in `Gemfile.lock`. Compatibility with current Ruby versions has not been verified. Keep the checked-in reveal.js assets: the templates rely on them.

## Attribution

Created from GitHub Learning Lab's introductory course and powered by [reveal.js](https://github.com/hakimel/reveal.js/). See [LICENSE](LICENSE) and the licenses included with the presentation assets.

<details>
<summary>Original course introduction</summary>

# Your GitHub Learning Lab Repository for Introducing GitHub

Welcome to **your** repository for your GitHub Learning Lab course. This repository will be used during the different activities that I will be guiding you through. See a word you don't understand? We've included an emoji 📖 next to some key terms. Click on it to see its definition.

Oh! I haven't introduced myself...

I'm the GitHub Learning Lab bot and I'm here to help guide you in your journey to learn and master the various topics covered in this course. I will be using Issue and Pull Request comments to communicate with you. In fact, I already added an issue for you to check out.

![issue tab](https://lab.github.com/public/images/issue_tab.png)

I'll meet you over there, can't wait to get started!

This course is using the :sparkles: open source project [reveal.js](https://github.com/hakimel/reveal.js/). In some cases we’ve made changes to the history so it would behave during class, so head to the original project repo to learn more about the cool people behind this project.

</details>
