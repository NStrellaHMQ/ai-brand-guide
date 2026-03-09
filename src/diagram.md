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
