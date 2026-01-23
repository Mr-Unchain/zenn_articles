# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a Zenn articles repository for publishing technical blog posts to [zenn.dev](https://zenn.dev). It uses zenn-cli for local preview and article management.

## Commands

```bash
# Install dependencies
npm install

# Preview articles locally (starts local server)
npx zenn preview

# Create a new article
npx zenn new:article

# Create a new book
npx zenn new:book
```

## Repository Structure

- `articles/` - Markdown files for individual articles (filename becomes the slug)
- `books/` - Book content (multi-chapter articles)

## Article Frontmatter Format

Articles use YAML frontmatter with the following fields:

```yaml
---
title: "Article title"
emoji: "📱"           # Single emoji for the article icon
type: "tech"          # "tech" for technical, "idea" for ideas/opinions
topics: ["topic1"]    # Array of topic tags (1-5 required)
published: false      # Set to true when ready to publish
---
```

## Reference

- [Zenn CLI Guide](https://zenn.dev/zenn/articles/zenn-cli-guide)
