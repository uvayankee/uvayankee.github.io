# Working with the AI Agent Instructions Repository

This document provides instructions for maintaining and contributing to the AI Agent Instructions repository.

## Repository Overview

This repository hosts a GitHub Pages site that provides examples of workable instructions to constrain AI agents to modern software engineering practices. The site is built using Jekyll and follows a simple structure:

- `_pages/`: Contains individual instruction pages in Markdown format
- `_config.yml`: Jekyll configuration file
- `index.md`: Main landing page
- `_layouts/`: Contains layout templates for the site
- `assets/`: Contains static assets for the site
  - `css/`: Custom CSS styles
  - `favicon/`: Favicon files
  - `images/`: Images used on the site
- `CNAME`: Contains a placeholder for custom domain configuration (currently commented out)
- `Gemfile`: Defines Ruby dependencies for Jekyll

## Adding New Instructions

To add a new instruction:

1. Create a new Markdown file in the `_pages` directory with a descriptive filename: `your-instruction-name.md`
2. Include the Jekyll front matter at the top of the file:
   ```
   ---
   layout: page
   title: "Your Instruction Title"
   permalink: /your-instruction-name/
   ---
   ```
3. Add your content below the front matter
4. Keep instructions concise and focused on a single software engineering practice
5. Use clear, direct language that an AI agent can easily interpret

## Modifying Existing Instructions

When updating existing instructions:

1. Maintain the same permalink to avoid breaking links
2. Keep the instructions concise and focused
3. Ensure the title accurately reflects the content
4. Test the changes locally before pushing to the repository

## Local Development

To run the site locally:

1. Install Jekyll and its dependencies
2. Run `bundle install` to install required gems
3. Run `bundle exec jekyll serve` to start the local server
4. Visit `http://localhost:4000` in your browser to preview the site

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch. No additional steps are required for deployment.

## Best Practices for Instructions

When writing instructions for AI agents:

1. Be specific and unambiguous
2. Focus on one principle or practice per instruction
3. Provide clear steps or guidelines
4. Use simple language that's easy for AI to parse
5. Consider including examples where appropriate
6. Keep instructions concise - AI agents work best with clear, direct guidance
