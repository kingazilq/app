# STUDIHARDWARE - AI & Mathematical IT Website

## Design Guidelines

### Design References (Primary Inspiration)
- **OpenAI.com**: Clean tech aesthetic, dark mode, smooth animations
- **Stripe.com**: Premium feel, gradient accents, modern typography
- **Three.js Examples**: 3D backgrounds, particle systems, floating elements
- **Style**: Futuristic Tech + Dark Mode + 3D Elements + Educational Premium

### Color Palette
- Primary: #0A0A0A (Deep Black - background)
- Secondary: #1A1A2E (Dark Navy - sections)
- Accent 1: #6366F1 (Indigo - primary accent)
- Accent 2: #8B5CF6 (Purple - secondary accent)
- Accent 3: #3B82F6 (Blue - highlights)
- Text Primary: #FFFFFF (White)
- Text Secondary: #94A3B8 (Slate Gray)
- Glow: #A78BFA (Purple glow for 3D elements)

### Typography
- Heading1: Inter font-weight 800 (56px) - Hero titles
- Heading2: Inter font-weight 700 (40px) - Section titles
- Heading3: Inter font-weight 600 (28px) - Subsections
- Body/Normal: Inter font-weight 400 (16px)
- Body/Emphasis: Inter font-weight 600 (16px)
- Navigation: Inter font-weight 500 (14px)
- Math/Code: JetBrains Mono font-weight 400 (14px) - For mathematical notations

### Key Component Styles
- **Buttons**: Gradient background (indigo to purple), white text, 8px rounded, hover: glow effect
- **Cards**: Dark navy (#1A1A2E), 1px border (#2A2A4E), 16px rounded, backdrop blur
- **3D Elements**: Semi-transparent, glowing edges, floating animation
- **Menu**: Slide-in animation, backdrop blur, smooth transitions

### Layout & Spacing
- Hero section: Full viewport height with 3D background
- Section padding: 120px vertical, 80px horizontal
- Card spacing: 32px gaps between floating cards
- 3D effects: translateZ, rotateX/Y for depth
- Animations: 0.6s ease-in-out transitions

### Animation Effects
- Parallax scrolling on hero background
- Floating animation for mathematical cards (translateY oscillation)
- Fade-in on scroll for sections
- Glow pulse effect on hover
- Smooth menu slide-in (300ms)
- Particle system background movement

### Images to Generate
1. **hero-ai-neural-network.jpg** - Abstract 3D neural network with glowing nodes and connections, dark background, purple/blue lighting (Style: photorealistic, futuristic, high-tech)
2. **ecosystem-ai-research.jpg** - AI research laboratory with holographic displays, data visualization, futuristic workspace (Style: photorealistic, sci-fi)
3. **ecosystem-mathematical-modeling.jpg** - 3D mathematical formulas floating in space, geometric patterns, matrix visualizations (Style: photorealistic, abstract)
4. **ecosystem-it-infrastructure.jpg** - Server room with glowing lights, network connections, digital infrastructure (Style: photorealistic, tech)
5. **ecosystem-decentralized-innovation.jpg** - Blockchain network visualization, connected nodes, decentralized system (Style: photorealistic, digital art)
6. **floating-math-background.jpg** - Subtle background with mathematical symbols, formulas, matrices in dark space (Style: minimalist, abstract)

---

## Development Tasks

1. **Setup & Structure** - Create todo.md, understand template structure
2. **Generate Images** - Create all 6 images using ImageCreator.generate_images
3. **Global Styles** - Update index.css with custom animations, 3D effects, scrollbar styles
4. **Header Component** - Navbar with three-dot menu, smooth dropdown
5. **Hero Section** - Full-screen with animated background, headline, subtitle
6. **About Section** - Description of Studihardware platform
7. **Core Concept Section** - AI × IT × Mathematics flow visualization
8. **Floating Math Cards** - 3D hovering cards with mathematical topics
9. **Ecosystem Section** - Image carousel with 4 slides
10. **Blog Section** - Blog preview with link
11. **Social Media Section** - Icon links with hover effects
12. **Footer** - Copyright section
13. **Main Page Integration** - Combine all components in Index.tsx
14. **Testing** - Lint check, build verification
