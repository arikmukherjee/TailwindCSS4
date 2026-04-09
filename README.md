# TailwindCSS4

Tailwind CSS v4 is a major release that introduces significant improvements and modernization to the framework.

## Core Improvements

**CSS-First Engine**: Built from the ground up with CSS as the foundation, eliminating many complexities from previous versions. The 3-4x faster processing makes development and builds much quicker.

**CSS Variables**: Tailwind v4 uses CSS custom properties (variables) extensively, enabling:
- True runtime theme switching
- Better dynamic styling
- Easier customization without rebuilds
- Cleaner generated CSS

## Key Features

**Simplified Configuration**: 
- `tailwind.config.js` is now optional for basic projects
- Theme values are defined using CSS variables
- Easier to extend and customize

**New Syntax**:
- `@theme` directive for defining design tokens
- `@apply` works better with CSS variables
- `@source` replaces `content` configuration

**Typography & Performance**:
- Improved font handling with better defaults
- Smaller baseline CSS output
- Better tree-shaking and code splitting

**Container Queries**: Native support for modern container queries without complex setup

**Gradient Improvements**: Enhanced gradient stops and more intuitive syntax

**Better Dark Mode**: 
- Simpler dark mode configuration
- Works seamlessly with CSS variables

## Compatibility & Migration

- Requires Node.js 18+
- PostCSS 8+
- Breaking changes from v3 (but migration tools available)
- Most existing Tailwind knowledge still applies

## Why Upgrade?

- Significantly faster builds
- Smaller CSS footprint
- More powerful customization
- Better alignment with modern CSS standards
- Improved developer experience

The v4 release represents Tailwind's evolution toward leveraging modern CSS capabilities rather than fighting against them.

## How to Run

### Tailwind with CDN
Simply open the `index.html` file in the "Tailwind with CDN" folder directly in your browser. No installation or build step required—Tailwind CSS is loaded from a CDN link.

```bash
# Navigate to the folder and open in browser
Tailwind with CDN/index.html
```

### Tailwind with CLI
This folder demonstrates Tailwind CSS v4 with a local build setup using the CLI tool.

1. **Install dependencies**:
```bash
cd "Tailwind with CLI"
npm install
```

2. **Build CSS**:
```bash
npm run build
```

3. **Watch mode** (for development):
```bash
npm run watch
```

Or run the CLI directly with:
```bash
npx @tailwindcss/cli -i style.css -o .\output.css --watch
```

4. **Open files in your browser**:
Open any `.html` file from the "Tailwind with CLI" folder in your browser to see the compiled Tailwind styles in action.

The CLI version allows you to customize Tailwind's configuration via `tailwind.config.js` and use all advanced features of Tailwind CSS v4.

Ref:

- https://www.youtube.com/playlist?list=PL8p2I9GklV471sLqkGuf0eKAu9sVNmKFV
- https://tailwindcss.com/docs/installation/using-vite
- https://getbootstrap.com/
- https://fonts.google.com/
