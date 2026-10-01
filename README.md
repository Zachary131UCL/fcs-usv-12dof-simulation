# FCS–USV 12DOF Simulation

Public, browser-based review of the coupled floating charging station (FCS) and unmanned surface vessel (USV) hydrodynamic model.

## Open the site

The published site is served through GitHub Pages. For a local preview, open `index.html` in a modern browser.

## Contents

- Interactive 3D regular-wave replay
- Coupled 12DOF response amplitude operators
- Docking-interface relative motion
- Added-mass and radiation-damping matrices
- Explanation of the modeling workflow

The page is self-contained: styles, scripts, meshes, and the selected simulation data are embedded in `index.html`.

## Updating the public site

1. Regenerate `../02_Dynamics_6DOF/REVIEW.html`.
2. Copy it over `index.html` in this directory.
3. Commit and push the change to the `main` branch.
4. GitHub Pages will deploy the new version automatically.

## Model scope

This is a model-scale linear potential-flow simulation. It does not include experimentally calibrated viscous damping, mooring, propulsion control, arm loads, capture contact, or an operational safety envelope.
