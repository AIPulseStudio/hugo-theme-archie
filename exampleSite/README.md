# Hugo Theme Archie - Example Site

This is an example site using the hugo-theme-archie theme, featuring a Belgian Challenger Pro League football theme style.

## Quick Start

### Method 1: Run from current directory

```bash
cd D:\src\project\AIPulseStudio\hugo-themes\hugo-theme-archie\exampleSite
hugo server -D --port 1314
```

## Configuration

### params.logo parameters

The theme supports the same parameters as hugo-theme-paper:

```toml
[params.logo]
# Navigation logo (text/emoji or image path)
navlogo = "⚽"
# Hero section content
text = "🇧🇪"
title = "CHALLENGER PRO"
subtitle = "Belgian Challenger Pro League"
```

- `navlogo`: Navigation logo (text/emoji or image path)
- `text`: Hero section large icon
- `title`: Main heading in hero
- `subtitle`: Subtitle text

### Menu configuration

```toml
[[menu.main]]
name = "Home"
url = "/"
weight = 1

[[menu.main]]
name = "Posts"
url = "/posts/"
weight = 2
```

## Article Parameters

```yaml
---
title: "Article Title"
date: 2024-03-08T10:00:00+07:00
draft: false
description: "Short description"
image: "/images/article-cover.jpg"  # optional
category: "Category"
tags: ["tag1", "tag2"]
---
```

## Theme Features

- 🇧🇪 Belgian football theme style
- ⚽ Black and yellow colors (#000000, #FDDA24)
- 📰 Responsive design
- 🔗 Social media links
- 📱 Mobile-friendly
- 🏷️ Category and tag support

## Access

After starting the Hugo server, visit http://localhost:1314 to see the result.
