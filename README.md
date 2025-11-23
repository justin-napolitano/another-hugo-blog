# another-hugo-blog

A personal data science and legal research blog powered by Hugo, featuring rich content on quantitative analysis, legal AI research, and energy sector insights.

## Features

- Static site generated with Hugo using the Anubis theme
- Multi-language support with translations in German, Polish, Portuguese, French, English, Chinese, Russian, and Taiwanese
- Blog posts on topics including Julia programming, legal research with AI, energy sector GIS analysis, and statistical methods
- Pagination, tagging, categories, and series taxonomy support
- Integrated Google Analytics and Disqus comments
- Syntax-highlighted code blocks with copy-to-clipboard functionality

## Tech Stack

- Hugo static site generator
- HTML, YAML for configuration
- Python and Julia for data analysis and research content
- JavaScript for UI enhancements (copy code button)

## Getting Started

### Prerequisites

- Hugo installed (https://gohugo.io/getting-started/installing/)
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/justin-napolitano/another-hugo-blog.git
cd another-hugo-blog
```

### Running Locally

```bash
hugo server -D
```

Open your browser at http://localhost:1313 to view the site.

### Building for Production

```bash
hugo
```

The generated site will be in the `public` directory.

## Project Structure

```
/archetypes       # Hugo archetypes for new content
/assets           # Site assets like CSS and JS
/config.yaml      # Site configuration
/content          # Markdown content for posts and pages
/i18n             # Internationalization files
/layouts          # Custom Hugo layouts
/public           # Generated static site output
/resources        # Hugo resource files
/static           # Static files like images
/themes           # Hugo themes (Anubis)
```

## Future Work / Roadmap

- Add more detailed documentation and contribution guidelines
- Expand multi-language support and translations
- Integrate additional analytics and SEO improvements
- Automate deployment to hosting providers
- Enhance UI with more interactive features

---

*Note: This repository contains rich blog content primarily authored by Justin Napolitano, focusing on data science, legal AI research, and energy sector analysis.*