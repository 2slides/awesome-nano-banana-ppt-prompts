# Contributing to Awesome Nano Banana PPT Prompts

Thank you for your interest in contributing to this open-source collection of Nano Banana Pro PPT slide generation prompts! This document provides guidelines and instructions for contributing.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Prompt Structure](#prompt-structure)
- [File Naming Conventions](#file-naming-conventions)
- [Preview Image Guidelines](#preview-image-guidelines)
- [Submission Process](#submission-process)
- [Review Process](#review-process)
- [Questions?](#questions)

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for all contributors. Be kind, constructive, and open to feedback.

## How to Contribute

We welcome contributions in the following forms:

1. **New Prompts**: Add new, high-quality prompts for generating PPT slides
2. **Improvements**: Enhance existing prompts with better descriptions or additional preview images
3. **Documentation**: Improve documentation, fix typos, or clarify instructions
4. **Bug Fixes**: Report and fix issues with existing prompts

## Prompt Structure

Each prompt should be organized in its own directory under the `prompts/` folder. The directory structure should follow this format:

```
prompts/
  └── your-prompt-name/
      ├── prompt.md
      ├── preview-1.webp (or .jpg)
      └── preview-2.webp (optional, if you have multiple previews)
```

### Prompt Markdown File (`prompt.md`)

Each `prompt.md` file must follow this structure:

```markdown
---
id: your-prompt-id
title: Your Prompt Title
tags: tag1, tag2, tag3
---

# Your Prompt Title

## Prompt Text

[Your detailed prompt text here. This should be clear, specific, and provide enough detail for users to generate high-quality slides.]

## Reference Images

![Preview 1](preview-1.webp)

![Preview 2](preview-2.webp)
```

#### Frontmatter Requirements

- **id**: A unique, URL-friendly identifier (lowercase, hyphens for spaces)
  - Example: `product-launch-deck-in-apple-style-minimalism`
- **title**: A clear, descriptive title for the prompt
  - Example: `Product launch deck in Apple-style minimalism`
- **tags**: Comma-separated list of relevant tags for categorization
  - Example: `apple, product launch, minimalism`

#### Content Sections

- **Title**: Repeat the title as an H1 heading
- **Prompt Text**: The actual prompt text that users will copy and use. Should be:
  - Clear and specific
  - Include design guidelines, style references, or specific requirements
  - Provide examples or bullet points when helpful
  - Written in a way that produces consistent, high-quality results
- **Reference Images**: Include all preview images using markdown image syntax

## File Naming Conventions

### Directory Names

- Use lowercase letters
- Separate words with hyphens (`-`)
- Be descriptive but concise
- Examples:
  - ✅ `mckinsey-company-presentation-style`
  - ✅ `travel-journal-collage`
  - ❌ `McKinsey Style` (spaces and capitals)
  - ❌ `travel_journal` (underscores)

### Preview Image Names

- Use the format: `preview-1.webp`, `preview-2.webp`, etc.
- Start from `preview-1` and increment for additional images
- Prefer `.webp` format for better compression, but `.jpg` is acceptable
- Ensure images are optimized for web (reasonable file size)

## Preview Image Guidelines

Preview images are essential for showcasing your prompt. Follow these guidelines:

1. **Quality**: Use high-quality screenshots or exports of slides generated with your prompt
2. **Format**: Prefer `.webp` format, but `.jpg` is acceptable
3. **Size**: Optimize images for web (aim for < 500KB per image)
4. **Dimensions**: Use consistent aspect ratios (16:9 is standard for slides)
5. **Quantity**: Include at least 1 preview image, but 2-3 are recommended to show variety
6. **Content**: Showcase different aspects of the prompt (e.g., different slide layouts, color schemes, or use cases)

## Submission Process

1. **Fork the Repository**
   - Click the "Fork" button on GitHub to create your own copy

2. **Create a Branch**
   - Create a new branch for your contribution
   - Use a descriptive name like `add-travel-journal-prompt` or `improve-apple-style-prompt`

3. **Add Your Prompt**
   - Create a new directory under `prompts/` following the naming conventions
   - Add your `prompt.md` file with proper frontmatter and content
   - Add preview images to the same directory

4. **Test Your Prompt**
   - Verify that your prompt works well with [2Slides](https://2slides.com)
   - Ensure preview images are clear and representative
   - Check that all markdown syntax is correct

5. **Commit Your Changes**
   - Write clear, descriptive commit messages
   - Example: `Add travel journal collage prompt`

6. **Submit a Pull Request**
   - Push your branch to your fork
   - Open a Pull Request on the main repository
   - Fill out the PR template (if available) or include:
     - Description of your prompt
     - What it's useful for
     - Any relevant tags or categories

## Review Process

After you submit a Pull Request:

1. **Automated Checks**: The repository may run automated checks on your submission
2. **Maintainer Review**: A maintainer will review your prompt for:
   - Quality and clarity
   - Proper formatting and structure
   - Appropriate tags and categorization
   - Preview image quality
3. **Feedback**: You may receive feedback or requested changes
4. **Merge**: Once approved, your prompt will be merged and appear in the gallery

### What Makes a Good Prompt?

- **Specificity**: Clear, detailed instructions that produce consistent results
- **Usefulness**: Addresses a real need or use case
- **Uniqueness**: Offers something new or different from existing prompts
- **Quality**: Well-written, easy to understand, and follows best practices
- **Visual Appeal**: Preview images showcase attractive, professional results

## Questions?

If you have questions or need help:

- Open an issue on GitHub for general questions
- Check existing issues and discussions
- Review the README.md for project overview

## Thank You!

Your contributions help make this collection more valuable for everyone. We appreciate your time and effort in sharing your prompts with the community!

---

**Note**: This repository is showcased at [https://2slides.com/prompts](https://2slides.com/prompts). All accepted prompts will be featured there.

