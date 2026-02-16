# UAV Aerial Photography — Webapp

A single-page webapp that presents the UAV Aerial Photography course (based on Artem Mazurok, St Petersburg University) with clear structure, visuals, and explanations.

## How to open

- **From the repo root**: Open `webapp/index.html` in a browser (e.g. double-click or `open webapp/index.html`). Images are loaded from `../img/`, so the repo root must be `UAV/` when opening the file.
- **Local server** (recommended if images don’t load): From the `UAV` folder run  
  `python3 -m http.server 8000`  
  then go to `http://localhost:8000/webapp/`.

## Contents

- **Intro**: What is aerial photography, short history.
- **Week 1**: UAV types (fixed-wing, multirotor, hybrid), construction, payload (RGB, NIR, LiDAR, etc.).
- **Week 2**: Coordinate systems, GNSS, geodetic control (GCPs vs onboard GNSS/PPP).
- **Week 3**: Aerial photography requirements, reconnaissance, ground control station (GCS).
- **Week 4**: GNSS data processing (static, kinematic, RTK, PPP).
- **Summary**: Key takeaways.

No build step required; one HTML file plus course images in `../img/`.
