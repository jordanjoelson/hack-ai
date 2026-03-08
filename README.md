# SCHWEP  
## Precision Design Discovery Engine

SCHWEP is a visual design discovery engine that helps users explore and define their aesthetic style without writing prompts. Instead of describing design preferences in text, users interact directly with designs, and the system learns their taste through four fast discovery rounds.

The goal of SCHWEP is to make design exploration feel more like curating inspiration than configuring AI models.

---

## What SCHWEP Does

SCHWEP guides users through a four-round discovery process:

### Frame
Users select structural foundations such as bento grids, Swiss grids, or hero canvas layouts.

### Shape
Users define geometric identity by adjusting border radius and edge styles.

### Tone
Users explore typography pairings that represent different design voices.

### Finish
Users apply atmospheric effects such as glow, grain texture, or glass-style depth.

As selections are made, SCHWEP builds a mathematical profile of the user’s aesthetic taste.

---

## Core Technology

### Preference Vector Engine
Each design card is encoded as a multi-dimensional vector representing visual attributes such as structure, edge curvature, density, warmth, and depth.

The system uses **cosine similarity** to rank designs based on how closely they match the user’s profile.

---

### Generative AI Integration
I used AI models to help generate design variants based on the learned aesthetic profile. This allows SCHWEP to produce new UI concepts that are aligned with the user’s style.

---

### Rendering Pipeline
SCHWEP includes a custom script that generates SVG layouts from blueprint outputs.

These SVGs can be exported and used in Figma or other design tools.

---

## Tools I Used

- Figma – Design prototyping and interface development  
- GitHub & Git – Code version control and project management  
- Generative AI tools – Idea exploration and variant generation  
- Antigravity – Parallel multi-agent workflow for faster iteration  

---

## Why SCHWEP Matters

Many design tools require users to describe what they want using technical language. SCHWEP flips this approach by learning design preference through interaction.

Instead of writing prompts, users discover their aesthetic identity visually.

---

## Future Ideas

- Expand design catalog coverage  
- Improve aesthetic vector modeling  
- Generate more complex component systems  
- Enhance Figma plugin integration  
- Support collaborative style discovery
