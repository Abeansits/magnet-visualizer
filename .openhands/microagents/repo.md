# Magnet Visualizer Repository

## Project Overview
Interactive magnetic field visualizer designed for educational purposes, particularly for kids to learn about magnetism through hands-on experimentation.

## Live Demo
🌐 **GitHub Pages**: https://abeansits.github.io/magnet-visualizer/

## Repository Structure
```
magnet-visualizer/
├── index.html              # Main application (served by GitHub Pages)
├── claude4-impl/
│   └── index.html          # Original implementation
├── README.md               # Basic project description
├── LICENSE                 # Project license
└── .openhands/
    └── microagents/
        └── repo.md         # This documentation
```

## Features
- **Interactive Magnet Placement**: Click to place north/south pole magnets
- **Real-time Physics**: Drag and drop magnets with realistic magnetic interactions
- **Field Visualization**: Toggle magnetic field lines display
- **Anchor System**: Lock magnets in place with anchor tool
- **Friction Control**: Adjustable surface friction simulation
- **Modern UI**: Dark theme with glassmorphism effects
- **Responsive Design**: Works on desktop and mobile devices

## Version History

### v1.0.1 (Current) - UI Alignment Fix
- Fixed sidebar and canvas alignment issues
- Set sidebar height to 650px to match canvas
- Improved layout positioning and spacing
- Better visual balance and professional appearance

### v1.0.0 - Initial Release
- Added shimmering animation to title "Magnetic Field Simulator"
- Increased canvas size from 900×600 to 1000×650
- Implemented semantic versioning system
- Set up GitHub Pages deployment

## GitHub Pages Setup

### Configuration
- **Source**: Deploy from `main` branch, root directory (`/`)
- **URL**: https://abeansits.github.io/magnet-visualizer/
- **Build Type**: Legacy (static files)
- **HTTPS**: Enforced

### Deployment Process
1. Changes pushed to `main` branch automatically trigger GitHub Pages rebuild
2. Build typically takes 1-3 minutes
3. Version number visible in bottom-right corner for tracking updates
4. Hard refresh (Ctrl+F5 / Cmd+Shift+R) may be needed to see latest changes due to browser caching

## Development Workflow

### Version Management
- **Semantic Versioning**: Following semver.org standards
- **Version Display**: Current version shown in bottom-right corner of UI
- **Git Tags**: Each version tagged in repository
- **Increment Policy**: Version bumped for every change, no matter how small

### Version Increment Guidelines
- **PATCH (x.x.X)**: Bug fixes, UI tweaks, small improvements
- **MINOR (x.X.x)**: New features, backward compatible changes
- **MAJOR (X.x.x)**: Breaking changes or major redesigns

### Release Process
1. Make changes to `index.html`
2. Update version number in HTML: `<div class="version">vX.X.X</div>`
3. Commit with descriptive message
4. Create git tag: `git tag vX.X.X`
5. Push both: `git push origin main && git push origin vX.X.X`
6. GitHub Pages automatically deploys

## Technical Details

### Technologies Used
- **HTML5 Canvas**: For magnetic field visualization and interactions
- **Vanilla JavaScript**: Physics simulation and user interactions
- **CSS3**: Modern styling with animations and glassmorphism effects
- **GitHub Pages**: Static site hosting

### Key Components
- **Physics Engine**: Custom magnetic field calculations and particle interactions
- **UI Controls**: Sidebar with magnet placement tools and parameters
- **Animation System**: Smooth magnetic field particle animations
- **Responsive Layout**: Flexbox-based layout that adapts to screen sizes

### Performance Optimizations
- Particle limit (150 max) for smooth performance
- Efficient field calculations
- Optimized rendering loop
- Minimal DOM manipulation

## Educational Value
- **Visual Learning**: See magnetic fields in real-time
- **Interactive Experimentation**: Hands-on magnet manipulation
- **Physics Concepts**: Attraction, repulsion, field lines
- **Safe Environment**: Digital experimentation without physical magnets

## Future Enhancement Ideas
- Multiple magnet shapes (bar, horseshoe, ring)
- Magnetic field strength visualization with color coding
- Save/load magnet configurations
- Educational tutorials or guided experiments
- Sound effects for interactions
- 3D visualization mode
- Magnetic material simulation (iron filings)

## Maintenance Notes
- Monitor GitHub Pages build status for deployment issues
- Test across different browsers and devices
- Keep version numbers updated for all changes
- Maintain responsive design for mobile users
- Consider performance impact of new features

## Contact & Contributions
This is an educational project designed for kids to learn about magnetism. The focus is on simplicity, visual appeal, and educational value.