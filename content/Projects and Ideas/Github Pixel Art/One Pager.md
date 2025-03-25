---
title: One Pager
draft: false
tags:
  - HobbyProject
  - PixelArt
---

# The Idea 💡

GitHub Pixel Art is a web application that transforms your GitHub contribution graph into a creative canvas. It allows users to design custom pixel art patterns that can be implemented through a strategic commit schedule, turning your GitHub contribution history into visual expression.

## Origin 🌱

During my role interviewing engineering candidates, I found myself routinely examining GitHub profiles to assess technical capabilities and project history. While browsing one candidate's profile, I noticed their contribution graph formed what appeared to be a letter. This serendipitous observation sparked curiosity—could the GitHub contribution graph be intentionally manipulated to create visual designs?

What started as a simple observation evolved into a creative challenge. Despite having limited practical application, the concept presented an intriguing technical exercise that combined visual design with programming logic in an unexpected way.

### GitHub Contribution Graphs 📊

GitHub profiles display contribution activity through a grid of colored squares—lighter squares indicating fewer contributions and darker green representing more active days. This standardised visualisation inadvertently creates a pixel-based canvas where each day represents a potential "pixel" in a 52×7 grid (representing weeks and days of the week).

Most developers use this graph as a passive representation of their coding activity. However, I saw potential for transformation—turning this productivity tracker into an intentional artistic medium.

### Implementation Approach 🛠️

I built GitHub Pixel Art as a React TypeScript application with a simple, intuitive interface that:

1. **Converts text to pixel patterns** - Users can input text that automatically generates the corresponding commit pattern
2. **Provides a visual editor** - A grid interface allows users to "paint" custom patterns by clicking or dragging across days
3. **Generates commit schedules** - The app calculates exactly when and how many commits are needed each day to create the desired pattern
4. **Enables sharing via URL** - Designs can be encoded in the URL for easy sharing and collaboration
5. **Supports data export** - Users can download their commit schedule as a CSV file for implementation

The different shades of green are achieved by varying commit frequency on specific days—from light green (few commits) to dark green (many commits)—creating a 5-level grayscale palette.

### Future Enhancements 🚀

The current implementation is functional but has room for expansion:

- **Canvas painting interface** - Enhancing the mouse-based pixel editing experience
- **Pattern library** - Creating a gallery of pre-designed patterns users can modify
- **Implementation scripts** - Providing automation tools to help execute the commit schedules
- **Community features** - Building functionality for users to share and extend each other's designs
- **Mobile optimisation** - Improving the experience on smaller screens
