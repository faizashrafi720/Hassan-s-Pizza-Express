# Hassan's Pizza Express 🍕🚚

An educational browser game that teaches basic programming logic, math, and letter recognition through a fun pizza delivery adventure. Designed for elementary-age children with a Montessori-inspired adaptive learning approach.

## How to Play

Open **`pizza_menu.html`** in any web browser. No server or installation required.

### Game Flow

1. **Main Menu** (`pizza_menu.html`) — Click PLAY to start a delivery.
2. **Level 1** (`level_1.html`) — Navigate a 4×4 grid by building a sequence of up to 5 directional commands (UP, DOWN, LEFT, RIGHT). Press GO! to execute. Reach the school to earn coins!
3. **Toll Booth** (`toll_booth.html`) — Answer a math or letter-matching question to raise the barrier and continue.
4. **Garage** (`garage.html`) — Spend coins on new vehicles (School Bus, Double-Decker Bus) with different capacities and speeds.
5. **Parents Dashboard** (`parents_dashboard.html`) — View learning analytics (math & alphabet accuracy, coin economy, vehicle fleet). Accessed via a parental math gate from the main menu.

### Educational Pillars

- **Sequencing & Logic** — Building command chains to navigate a grid
- **Counting & Addition** — Pizza slice sums at toll booths
- **Letter Recognition** — Matching uppercase to lowercase letters
- **Financial Literacy** — Earning and spending coins on vehicle upgrades

## Project Structure

```
├── pizza_menu.html          — Main menu / hub
├── level_1.html             — Core grid-programming gameplay
├── toll_booth.html          — Educational puzzle checkpoint
├── garage.html              — Vehicle upgrade shop
└── parents_dashboard.html   — Parent/teacher analytics dashboard
```

## Technical Details

- **Stack:** Vanilla HTML5, CSS3, JavaScript (ES6) — no frameworks or build tools
- **Graphics:** CSS-drawn visuals and inline SVG sprites — no image files
- **Audio:** Web Audio API synthesized sound effects — no audio files
- **Persistence:** `localStorage` for coins, owned vehicles, and active vehicle
- **Fonts:** Google Fonts (Fredoka)
- **Responsive:** CSS media queries for mobile layouts
