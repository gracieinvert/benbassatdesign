# Trifecta-Inspired Redesign (V2)

## Files Created
- `index-v2.html` - New homepage with Trifecta-inspired layout
- `style-v2.css` - Modern, minimal stylesheet

## Design Features

### Typography
- **Headings:** 3-5rem (responsive with clamp)
- **Body:** 1rem base size
- **System fonts:** -apple-system, Helvetica Neue, Arial
- **Letter spacing:** Tight on headings (-0.02em), normal on body

### Color Palette
- **Text:** #000000 (pure black)
- **Background:** #ffffff (pure white)
- **Accent:** #f5f5f5 (subtle gray)
- **Borders:** #e0e0e0 (light gray)

### Layout
- **Grid:** 3 columns (desktop) → 2 (tablet) → 1 (mobile)
- **Spacing:** 80-120px between sections, 40px grid gaps
- **Max width:** 1600px centered container

### Project Cards
- Numbered format: `/001/` through `/015/`
- 4:3 aspect ratio images
- Hover effect: Scale 1.02x + brightness 0.95
- Transition: 0.3s cubic-bezier easing

### Hero Section
- Full viewport height (100vh)
- Centered "Alex BenBassat / UI/UX Designer"
- Large, bold typography
- Border bottom separator

### Animations
- Smooth hover states on all interactive elements
- Transform scale on cards
- Background/text swap on footer button
- Scroll-behavior: smooth

## Preview
To preview, simply open `index-v2.html` in a browser from the site directory.

## Notes
- All 15 project HTML files remain unchanged
- Images load from existing CDN URLs
- Responsive breakpoints: 1024px (tablet), 640px (mobile)
- Print styles included
- Lazy loading enabled on images
