GIT 337 — Module 4 Assessment
Layered Feature Story

Project Title:
Beyond the Numbers: Exploring the Ten Spiritual Vibrations

Author:
Brian Love

Project Overview:
This project is a responsive editorial feature story based on my original
Telepathic Race: Secrets of the Ten Spiritual Vibrations concept. The story
explores ten symbolic spiritual vibrations from Nothing through Perfection.

Build Boundaries:
This project uses native HTML and CSS only. No JavaScript is used. The primary
page layout uses CSS Grid, while positioning is limited to bounded spatial
relationships. The page preserves a logical source order and remains complete
and readable without its positioning, layering, or shape enhancements.

Workflow:
I began with the required starter scaffold and replaced the placeholder content
with my own story and visual assets. I merged my Module 1 design-system tokens,
typography, spacing, and focus styles into styles.css. I completed and updated
composition-plan.html while developing the positioned, layered, and shaped
elements. I used responsive Grid and normal document flow for the primary
layout before adding progressive enhancements.

Enhancements:
The wide-screen issue badge uses absolute positioning within the feature
header. The story guide uses bounded sticky positioning. The pull quote uses
a controlled overlap and the project's layer tokens. The Infinity medallion
uses border-radius, shape-outside, and shape-margin for an editorial text wrap.
The Revelation portal uses clip-path as a decorative enhancement.

Fallbacks:
The page remains complete and readable when CSS is disabled. At narrower
viewports, positioned relationships return to normal-flow presentations where
appropriate. Disabling shape-outside returns the Infinity text wrap to a
rectangular boundary. Disabling clip-path returns the Revelation portal to its
rectangular baseline without removing essential content.

Testing:
The project was tested at 320px, 768px, and 1280px and at 200% browser zoom.
Keyboard focus, pointer activation, CSS-disabled reading order, long-title and
doubled-paragraph content growth, sticky boundaries, stacking contexts, and
shape fallbacks were tested. The HTML passed validation with no errors. The
W3C CSS Validator reported shape-outside and shape-margin as unrecognized;
these required CSS Shapes features were retained and verified using current
MDN documentation and browser testing.

Project Progress:
L1 — Story and source order completed.
L2 — Responsive flow and primary layout completed.
L3 — Positioned relationships completed.
L4 — Layer system and stacking behavior completed.
L5 — Shapes and fallback behavior completed.
L6 — Documentation, support research, testing, credits, and AI disclosure
completed.