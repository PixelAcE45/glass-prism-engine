# Glass Prism Engine

https://github.com/PixelAcE45/nexus-refined NEXUS — ADVANCED GLASS MATERIAL SYSTEM



Upgrade the existing Nexus glassmorphism system without redesigning the existing UI.



The current interface is already approved. Preserve the existing layout, navigation, typography, branding, animations, components and functionality.



The goal is to make the glass material substantially more transparent, dimensional and customizable.



━━━━━━━━━━━━━━━━━━━━━━

GLASS MATERIAL

━━━━━━━━━━━━━━━━━━━━━━



Make the existing glass surfaces visibly translucent.



Background lighting and shapes should remain subtly visible THROUGH the glass instead of being hidden behind opaque surfaces.



Increase transparency while maintaining readability.



Use a coordinated material system consisting of:



• surface transparency

• backdrop blur

• subtle background color diffusion

• delicate edge highlights

• controlled border opacity

• soft ambient shadows

• subtle depth

• very light internal highlights



Do NOT achieve the effect by simply making cards transparent.



The result should clearly read as actual layered glass.



Avoid:

• opaque cards

• excessive white overlays

• excessive neon

• heavy glow

• thick borders

• excessive shadows

• plastic/frosted-card appearance



━━━━━━━━━━━━━━━━━━━━━━

ADVANCED CUSTOMIZATION

━━━━━━━━━━━━━━━━━━━━━━



Add a new:



Settings → Appearance → Glass / Material



section.



Provide live controls for:



1. Glass Opacity

2. Background Blur

3. Border Intensity

4. Surface Brightness

5. Depth / Shadow

6. Ambient Lighting

7. Glass Saturation

8. Reflection / Highlight



Changes should update the interface immediately.



Use centralized CSS variables/theme tokens so these controls affect the entire UI consistently rather than individual components.



━━━━━━━━━━━━━━━━━━━━━━

PRESETS

━━━━━━━━━━━━━━━━━━━━━━



Add four presets:



• Subtle Glass

• Balanced Glass

• Crystal Glass

• Ultra Glass



Balanced Glass should remain the default.



Ultra Glass should noticeably increase transparency, background visibility and blur while preserving readability.



━━━━━━━━━━━━━━━━━━━━━━

DARK + LIGHT

━━━━━━━━━━━━━━━━━━━━━━



Apply the material system to BOTH themes.



Dark mode should retain its existing cinematic identity.



Light mode should become substantially more glass-like, with translucent bright surfaces, visible diffused background ambience and delicate highlights.



Do NOT simply invert the dark theme.



Each theme should have its own appropriate material values.



━━━━━━━━━━━━━━━━━━━━━━

PERFORMANCE

━━━━━━━━━━━━━━━━━━━━━━



Keep the system performant.



Use GPU-friendly CSS effects where possible.



Do not introduce unnecessary JavaScript animation loops.



━━━━━━━━━━━━━━━━━━━━━━

IMPORTANT

━━━━━━━━━━━━━━━━━━━━━━



Do NOT redesign the application.



Do NOT change the existing navigation.



Do NOT change the Nexus logo.



Do NOT remove existing animations.



Do NOT change the information architecture.



Do NOT modify backend functionality.



Do NOT regenerate existing pages.



This is specifically an upgrade to the existing glass material system and its customization controls.



The final result should make users immediately notice:



“I'm looking through glass.”



rather than:



“I'm looking at a transparent card.”

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/72402f65-b797-45fe-b6b5-ab24ab56fcb1).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
