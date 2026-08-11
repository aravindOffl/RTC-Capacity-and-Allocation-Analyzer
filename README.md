# RTC Capacity and Allocation Analyzer

An interactive, high-fidelity standalone HTML dashboard designed to analyze and forecast multi-year classroom, laboratory, faculty room, and utility capacity deficits.

## Key Features

- **Multi-Year Forecast Switcher**: Easily toggle between academic years:
  - **2026-27 (Current)**: Focuses on the physical infrastructure baseline. To keep the view focused, the student breakdown and summary KPI cards are dynamically hidden.
  - **2027-28**: Displays the student enrollment stats (7,911 total students) along with detailed breakdown by program and cumulative/incremental capacity deficits.
  - **2028-29**: Displays incoming cohort progressions (9,283 total students) and forecasts future deficits to help guide administrative resource allocation.
- **Deficit Matrices**: Breaks down physical capacity into four matrices: Classrooms, Laboratories, Faculty Rooms, and Utilities. Shows baseline availability, required capacity, total deficit, and incremental year-over-year required spaces.
- **Dynamic Capacity Met Visualizers**: Visual progress bars representing the percentage of target capacity fulfilled.
- **Dark & Light Mode Toggle**: A modern theme switch in the header that persists settings via `localStorage`.

## Technologies Used

- **HTML5** for page structure and semantic elements.
- **Vanilla CSS** with CSS Custom Properties (Variables) for theme controls, glassmorphic layout styling, and animations.
- **Vanilla JavaScript** for dynamic state management, calculations, year toggles, and UI interactions.

## How to View
Simply open `index.html` in any web browser to view and interact with the capacity matrices.
