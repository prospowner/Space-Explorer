# Space Explorer Hub

A responsive, multi-page web application designed to explore the structural layouts and fast facts of our solar system's planets and neighboring galaxies. This project utilizes native semantic document architecture, clean visual cards, smooth-scrolling fragment identifiers, and hardware-accelerated CSS link hover states.

## Project Architecture & Directory Layout

To ensure a clean, intuitive repository landing page, files are organized utilizing an engineering-first folder hierarchy. Secondary page views are forced into a unified module to keep the repository root uncluttered:

```text
space-explorer-hub/
├── pages/                    # Secondary application views (Forced Folder)
│   ├── About.html            # Informational site summary & project purpose
│   ├── Galaxies.html         # Data layout profiling 6 major galaxies
│   └── Planets.html          # Data layout profiling the 8 solar planets
├── index.html                # Main application entrance hub (Root)
├── .gitignore                # System artifact & workspace environment filters
└── README.md                 # Project documentation and engineering manifest
