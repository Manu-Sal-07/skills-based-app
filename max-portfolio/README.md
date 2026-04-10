## Max Verstappen Portfolio - Hero Section

**Note**: At the start of the project, you will just have SKILL.md and 2 images inside public folder. Src is created or vibe coded afterwards. To begin with just download the images from the public folder and copy the below prompt to Google Antigravity. 

> Prompt used:

Create a full-screen interactive Max Verstappen hero website for portfolio in React + Vite using exactly two uploaded images (public/img1.png, public/img2.png) of him. Design direction: minimalist, premium, white background, black typography, elegant serif (Playfair Display), clean editorial spacing. 

Core interaction:

- Use img2.png as the always-visible base portrait.
- Add a smooth circular spotlight cursor (with slight lag) that reveals img1.png only inside the circle, so moving the mouse feels like scanning an alternate layer of Max’s portrait.
- On fast cursor movement, spawn soft circular echo reveals behind the main spotlight; echoes must be subtle, small, and fade quickly to avoid clutter.
- Add a very subtle animated grid background that gently reacts to cursor position. 
- Add light opposite-direction parallax on key layers/text. 

Layout/content (must match):

- Top-left: large two-line name block: Max Verstappen
- Top-right: uppercase link text: Oracle Red Bull Racing (external link)
- Bottom-left: small uppercase subtitle: 4x World Champion.
- Bottom-right: social icons/links for Instagram and X (Twitter). 

Implementation requirements:

- Use requestAnimationFrame for animation loops
- Keep motion smooth and restrained, not aggressive.
- Responsive desktop/mobile behavior.
- Proper React hook cleanup for listeners/RAF.
- Final result should feel polished, refined, and interaction-first, with imagery as the visual centerpiece.