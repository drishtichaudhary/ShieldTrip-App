# ShieldTrip — Smart travel-safety app 🚀

Short technical description: A design-first prototype and documented project for a travel-safety mobile app focused on location-aware safety insights, alerts, and emergency features (design and documentation artifacts only).

## Overview
ShieldTrip addresses the need for clearer, context-aware safety information while travelling, especially in unfamiliar or higher-risk areas. Intended users include travellers, students, and individuals who want accessible safety guidance — for example: quick situational safety indicators on a map, place-level safety details, and an emergency-contacts interface.

## Motivation
People make route and location decisions under uncertainty; ShieldTrip's premise is that timely, location-aware safety cues (visualized on a map or surfaced in a place-details view), paired with low-friction emergency contact actions and alerts, can improve situational awareness and speed of response.

## Project status
- Evidence in this repository: design assets (Figma reference and exported screen images), contribution tasks, and project documentation (README, contributions/tasks.md).
- What is implemented in the repository: UI design artifacts and documentation only. There is no runnable application code, backend, API, or deployed service in this repository.
- What is not implemented here (but noted in the project plan): a Flutter / Web frontend, data collection or safety scoring backend, authentication, or production deployment.

## Current design artifacts (what is present in the repo)
The repo contains a Figma link and exported UI screens (PNG). The visible screen exports include (files under assets/screens):
- opening-screen.png, home.png, map.png, place_details.png
- emergency-contacts.png, notifications.png, profile.png, settings.png
- login.png, sign-up.png, language-choice.png
- tourist-id-generated.png, tourist-id-details.png
- custom-location.png, ShieldTrip Logo files

These images represent visual designs and flows (home, map/risk visualization, place details, emergency contacts, login/signup, profile/settings). Treat these as design prototypes — they do not contain interactive or executable app code.

## Technical / Design architecture (repository view)
This repository is organized around design artifacts and contributor-facing documentation. Key modules and their roles:

```
README.md                         - Project overview and contribution notes
figma                             - Small file containing the canonical Figma URL
assets/                           - Exported design assets
  screens/                        - PNG exports of UI screens and logos
contributions/                    - Contribution tasks and onboarding (tasks.md)
```

How it fits together: the Figma workspace (linked from the repo) contains the source UI designs; exported PNGs in assets/screens document the current visual state. The contributions/tasks.md file provides a curated list of design and UI tasks for contributors.

## Technology stack
Implemented (in-repo evidence):
- Design: Figma (canonical design file linked in repo)
- Static assets: PNG images (exported screens and logo)
- Documentation: Markdown (README.md, contributions/tasks.md)
- Collaboration: GitHub Issues and Discussions (project links provided)

Planned (explicitly referenced, not present as code here):
- Frontend: Flutter / Web (planned in repository README but no source code present)
- Any backend services, data pipelines, or models (no evidence present in this repo)

## Repository structure (annotated)

```
README.md                      # This file — rewritten for research-quality presentation
figma                          # Plain file that contains the Figma canonical link
assets/
  screens/                     # PNG exports of UI screens and logos (design artifacts)
contributions/
  tasks.md                     # Task list and contributor onboarding notes
```

## Contribution & maintenance workflow
- Issues: feature requests and implementation tasks should be tracked via GitHub Issues: https://github.com/drishtichaudhary/ShieldTrip-App/issues
- Discussions: idea-level conversations, design questions, and coordination should use GitHub Discussions: https://github.com/drishtichaudhary/ShieldTrip-App/discussions
- Design work process (documented in repository): duplicate the main Figma file before editing (the Figma file is view-only); share a link to your working copy and screenshots on the relevant Issue when submitting work.
- Task selection: contributors pick an issue or a task from contributions/tasks.md and link their work to that issue/Discussion thread.
- Reviews: design contributions should include screenshots and a short explanation of changes (what, why, and where in Figma). Maintain visual consistency with the existing design system (see Design System section).

## Design system & documentation (in-repo standards)
The repository explicitly documents these design expectations:
- Typography: use Poppins font (not enforced by code in this repo; a design guideline)
- Maintain consistent spacing, visual hierarchy, and component consistency across screens
- Figma workflow: annotate screens in Figma, add documentation pages, and include any design decisions in the Figma file or issue thread

The repository currently holds exported images and a reference to the Figma file where the canonical design and component definitions are expected to live.

## Roadmap (Planned / Proposed features — not implemented in this repo)
- Emergency contact setup & management: improved add/edit flows, clearer distinction between personal contacts and authorities.
- Trip history screen: display of past trips and routes (data-backed feature).
- Safety insights dashboard: aggregated trends and visualizations of safety metrics.
- Splash / loading screen with branding and optional animation.
- UI improvements: reduce clutter and refine layout for Home, Settings, and Place Details screens.
- Add in-repo Figma documentation pages (typography, color, components).

All roadmap items above are proposals recorded in repository documentation; they are not implemented as runnable code here.

## Getting started (for contributors and reviewers)
1. Review the canonical Figma file (repository points to the file below).
2. Inspect exported screens in assets/screens to understand current visual state.
3. Read contributions/tasks.md for suggested tasks and priorities.
4. Open or search existing Issues and Discussions to avoid duplicate work.
5. Duplicate the Figma file before editing; attach screenshots and a link to your working Figma file when posting progress to an Issue or Discussion.

Minimum deliverables for a design contribution:
- A short issue or Discussion linking the work and describing the goal
- Screenshots (exported PNGs) or a shared Figma link to the contributor's copy
- Short changelog notes explaining visual changes and rationale

## Contribution guidelines (expectations)
- Keep designs consistent with the documented system (Poppins font, spacing, hierarchy).
- Describe changes clearly in Issues or Discussions; prefer small, reviewable increments.
- Credit and link to the duplicated Figma file used for edits.
- Tests/code: there are no application tests in this repository. If code is added in the future, follow the repository's Issue workflow and provide a clear README update describing how to run and test new components.

## Project links
- Repository: https://github.com/drishtichaudhary/ShieldTrip-App
- Issues: https://github.com/drishtichaudhary/ShieldTrip-App/issues
- Discussions: https://github.com/drishtichaudhary/ShieldTrip-App/discussions
- Figma (canonical design): https://www.figma.com/design/qD4ygHXOrWyuc1jwsc6yVD/ShieldTrip-App
- Contribution tasks: https://github.com/drishtichaudhary/ShieldTrip-App/blob/main/contributions/tasks.md
- Assets (exported screens): https://github.com/drishtichaudhary/ShieldTrip-App/tree/main/assets/screens

## Limitations / current scope
- This repository contains design artifacts and contributor documentation; it does not contain a runnable application, backend services, or production deployment.
- Any references in earlier documentation to features such as "location-based safety insights" or "alerts/SOS functionality" refer to design prototypes rather than implemented, data-driven features.

## Maintainers
- The repository owner (GitHub user: drishtichaudhary) is the contact point for project coordination. Use Issues or Discussions for questions and proposals.
