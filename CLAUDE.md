# AI Agent Instructions for Portfolio Template

This file provides guidance for AI coding agents customizing this Next.js portfolio template.

## Quick Start

1. **Personal Info**: Look for data files or config in the project
2. **Pages**: Edit files in `app/` or `pages/` directory
3. **Components**: Customize reusable components

---

## Files to MODIFY (Customize These)

### Content
| Location | Purpose |
|----------|---------|
| Data/config files | Personal info, projects, skills |
| `app/` or `pages/` | Page content |
| `public/` | Images, resume, favicon |

### Styling
| File | Purpose |
|------|---------|
| Tailwind config | Theme colors |
| CSS files | Custom styles |

---

## Build and Test

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Start production server
npm run start
```

---

## Deployment Notes

This is a Next.js app. For static export, add to `next.config.js`:

```javascript
module.exports = {
  output: 'export',
  images: { unoptimized: true }
};
```

Then run `npm run build` - output goes to `out/` folder.
