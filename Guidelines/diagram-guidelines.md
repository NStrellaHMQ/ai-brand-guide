# Color Palette

## 1. Global Color Tokens
* **Yellow:** `#FFC000` (Core Identity)
* **Teal:** `#037DA5` (Tertiary Accent)
* **Black:** `#000000` (Accent/Canvas)
* **White:** `#FFFFFF` (Structure/Canvas)

## 2. Light Theme Profile
* **Canvas (60–70%):** White. Focus on maximum breathable white space.
* **Primary Highlight (10–30%):** Yellow. Use for nodes, title bars, and key elements.
* **Details and Accents (10–20%):** Black. Use for text, borders, structural lines and small accents.
* **Tertiary Accent (0–5%):** Teal. Very limited use for small accents only.
* * **Secondary Structure (0–10%):** Neutral Grey. Use as an alternative to Black or Yellow for secondary containers, background dividers, or decorative structural lines (e.g., node backgrounds that need to recede).

## 3. Dark Theme Profile
* **Canvas (50–70%):** Black. Use deep charcoal or true black.
* **Primary Highlight (10–30%):** Yellow. Use for high-visibility focal points.
* **Structural Detail (10–20%):** White. Strictly for body text and secondary labels.
* * **Structural Alternative (0–10%):** Neutral Grey. Use for secondary elements or structural lines where White is too bright.
* **Tertiary Accent (0–10%):** Teal. Use for only for subtle accents.

## 4. Logic & Constraints
* **Teal Restriction:** Never use Teal for large backgrounds or primary headings.
* **Legibility (Yellow):** Only use Black (`#000000`) text or icons on Yellow backgrounds.
* **Legibility (Dark):** Use Yellow (`#FFC000`) for headlines and White (`#FFFFFF`) for body copy on dark backgrounds.

* 5. Grey Usage Constraints**
* **Grey Restriction:** Grey is **NOT** a canvas (background) alternative.
* **Structural Only:** Grey is strictly for defining structural elements (borders, dividers, secondary container fills).
* **Primary Hierarchy:** Do not use Grey as a headline text color or a primary accent. It must remain a secondary element.


---


## Typography

## 1. Primary Heading: Raleway
**Role:** All primary headings (H1, H2), titles, and hero sections.
- **Personality:** Modern, geometric, and elegant.
- **Key Weight:** Bold (700) or Extra Bold (800).
- **Styling Tip:** Use sentence case. DO NOT use all caps.

## 2. Body & UI: Roboto
**Role:** Paragraphs, bullet points, captions, and functional UI elements.
- **Personality:** Neutral, professional, and highly legible.
- **Key Weight:** Regular (400) for blocks of text; Medium (500) for emphasis.
- **Styling Tip:** Maintain a line-height of **1.5x** to ensure readability across all applications.

---

## Type Hierarchy & Roles

| Element | Font | Weight | Character |
| :--- | :--- | :--- | :--- |
| **Main Title** | Raleway | 800 | Impactful |
| **Section Head** | Raleway | 700 | Modern & Structured |
| **Subhead** | Roboto | 700 | Clear & Bold |
| **Body Text** | Roboto | 400 | Readable & Functional |
| **Small Print** | Roboto | 500 | Efficient & Compact |

---



---


## 1. Shape Language & Containers
Our diagrams use a specific "geometry of intent" to distinguish between fixed systems, fluid data, and organizational boundaries.

| Element | Visual Style | Functional Role |
| :--- | :--- | :--- |
| **Primary Nodes** | Perfect Circles | Represents a core system, a major actor, or a central hub. |
| **Data/Event Objects** | Rounded Rectangles (Pills) | Represents a specific message, a data point, or a status update. |
| **Boundary Boxes** | Sharp Rectangles (Thin stroke or light fill) | Defines "zones," physical locations, or logical groupings. |
| **Icons** | Minimalist 2D | Used sparingly inside or above nodes to provide instant visual context. |

---

## 2. Connector Logic (Lines & Paths)
The lines are the "connective tissue" of the diagram. Their style must remain consistent to indicate the nature of the relationship.

* **Standard Connection:** Straight, solid lines (2pt weight). Used for direct, point-to-point relationships.
* **Hierarchical/Ortho Paths:** 90-degree "elbow" connectors. Used to show parent-child relationships or organized tree structures.
* **Cyclical Paths:** Large, sweeping arcs. Used only to represent continuous loops, lifecycles, or feedback rotations.

---

## 3. Arrowhead Specifications
Arrowheads must be uniform across all assets to maintain a "single-hand" look.

* **Shape:** "open" V-shaped arrowheads.
* **Scale:** The width of the arrowhead base should be roughly $3\times$ the width of the line weight.
* **Directionality:**
    * **Single Head:** Indicates a command, a push, or a one-way flow.
    * **Double Head:** Indicates a synchronized relationship or a two-way exchange.
    * **Placement:** The tip of the arrowhead should touch the outer edge of the destination shape without overlapping the stroke.



---

## 4. Spacing, Alignment & "White Space"
To ensure diagrams remain scannable and professional, follow these spatial rules:

* **The "Rule of Proximity":** Objects with a functional relationship should be placed closer to each other than to unrelated objects.
* **Grid Consistency:** All node centers must align to a common horizontal or vertical axis. Avoid "loose" or staggered placement.
* **Padding:** Maintain a "Clear Zone" around every shape. No line should come within 10% of a shape's diameter/width unless it is a connected arrow.
* **Visual Balance:** Distribute peripheral nodes evenly around a central hub to ensure the "weight" of the diagram is centered.

---
## 5. Color Strategy (Functional Only)
Color is used to encode the **type** of flow, not for aesthetic variety.

* **The Focal Color (Yellow):** Reserved for the most important "active" node or the core subject of the diagram.
* **Structural Color (Black/Dark Grey):** Used for physical "pipes," command lines, and primary nodes. Use **Dark Grey** for secondary structural lines to provide depth without the weight of pure black.
* **Information Color (Teal):** Used for secondary "reporting" lines, performance metrics, or feedback loops.
* **Subtle Context (Medium/Light Grey):** Used for boundary boxes or "background" systems. Use **Medium Grey** for non-active paths and **Light Grey** for large containers or ghosted nodes that need to recede.


---


# Critical Prohibitions

Strict constraints. These override all other layout suggestions.

* **NO Honeycombs:** Under no circumstances use hexagonal or honeycomb patterns.
* **Legibility Rule:** NEVER place Yellow (#FFC000) text or icons on White/Light-Grey backgrounds. Yellow is for dark backgrounds or as a background fill only.
* **No Clutter:** Remove any element that does not serve a direct functional or informational purpose.
* **No thick or tapered lines.


---


