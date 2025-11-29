# Hi-Fi Prototypes with Figma

## Project: The Land of Harmony - Virtual Tour

**Course:** ENSE 271 - People-Centred Design  
**Student:** Sheikh Chand Muhammad Shami  
**Date:** November 28, 2025

---

## Project Overview

This project is a **virtual tour prototype** created using Figma that showcases "The Land of Harmony" - a fictional peaceful land where people live in agricultural communities and respect the beauty of their nighttime environment. The prototype demonstrates interactive design concepts including navigation, prototyping workflows, and various animation techniques.

---

## Project Structure

### 1. Home Page
- Welcome screen introducing visitors to The Land of Harmony
- **Interactive Element:** Automatic carousel featuring rotating images
- Navigation hamburger menu for accessing all pages

### 2. Navigation Menu
- Slide-down animation effect
- Links to all major sections of the virtual tour
- Accessible from every page via hamburger icon

### 3. Three Landmark Pages

#### Landmark 1: **The Temple**
- **Description:** A sacred place of worship and meditation for the villagers
- **Interactive Element:** Lightbox gallery displaying temple architecture and ceremonies
- **Interaction Type:** Click-to-reveal lightboxes with overlay effect
- **Images:** Multiple views of the temple structure, interior designs, and religious ceremonies

#### Landmark 2: **The Lake**
- **Description:** A serene body of water that provides resources and tranquility to the community
- **Interactive Element:** Auto-fade animation showcasing different times of day at the lake
- **Interaction Type:** Slow automatic fade transitions between images
- **Smart Animate Usage:** ✓ Size transform on water reflections
- **Images:** Dawn, midday, sunset, and nighttime views of the lake

#### Landmark 3: **The Forest**
- **Description:** A lush woodland area surrounding the village, home to diverse wildlife
- **Interactive Element:** Draggable gallery with cover flow effect
- **Interaction Type:** Horizontal drag navigation with zoom effect on centered image
- **Smart Animate Usage:** ✓ Scale transform creating the cover flow zoom effect
- **Images:** Forest trails, wildlife, tree canopies, and seasonal changes

---

## Design Concepts Applied

### Prototyping Techniques
1. **Flow Creation:** Established default starting point for presentation mode
2. **Hotspot Connections:** Connected interactive elements to destination screens
3. **Trigger Actions:** Implemented tap, drag, and automatic triggers
4. **Transition Animations:** Applied slide, fade, push, and smart animate effects

### Interactive Elements Implemented

#### Automatic Carousel (Home Page)
- **Concept:** Inbetweening/Tweening animation
- **Implementation:** Three keyframes with automatic transitions
- **Settings:** Dissolve effect, 2000ms duration, 3000ms delay
- **Navigation:** Cycles automatically through image sequence

#### Lightbox Overlays (The Temple)
- **Concept:** Modal overlays with background dimming
- **Implementation:** Click triggers on text/images reveal detailed information
- **Settings:** Instant transition, overlay positioning
- **User Control:** Close button returns to main page

#### Auto-Fade Animation (The Lake)
- **Concept:** Smooth automatic transitions between scenes
- **Implementation:** Two keyframes with slow dissolve
- **Settings:** Dissolve effect, 2000ms duration, no delay
- **Smart Animate:** Applied to size transforms on water elements

#### Draggable Gallery with Cover Flow (The Forest)
- **Concept:** Touch/drag navigation with focus emphasis
- **Implementation:** Six keyframes forming a navigation loop
- **Settings:** Smart Animate, 300ms duration, ease-out easing
- **Smart Animate:** Scale transform enlarges centered image
- **User Control:** Drag left/right to navigate through images

---

## Smart Animate Details

### Location 1: The Lake - Size Transform
**How to View:**
1. Navigate to "The Lake" landmark page
2. Observe the automatic fade between different times of day
3. Notice how the water reflections smoothly scale and transform

**Smart Animate Settings:**
- Property animated: Size/Scale of water reflection elements
- Easing: Ease-in-out
- Duration: 2000ms

### Location 2: The Forest - Cover Flow Zoom
**How to Navigate:**
1. Go to "The Forest" landmark page
2. Drag the image gallery horizontally (left or right)
3. Watch as the centered image scales up while adjacent images scale down

**Smart Animate Settings:**
- Property animated: Scale transform
- Effect: Cover flow zoom on focus
- Duration: 300ms
- Easing: Ease-out

---

## Navigation Guide

### Main Menu Access
- Click the **hamburger icon** (≡) on any page
- Menu slides down from the top
- Select any destination from the menu

### Page Connections
- **Home** → All pages via hamburger menu
- **Landmarks** → Accessible from home and menu
- **Back Navigation** → Back buttons return to previous screens

---

## Technical Implementation

### Prototyping Workflow
1. Created frames for each page/screen
2. Set default flow starting point (Home page)
3. Added hotspots to interactive elements
4. Connected destinations with appropriate transitions
5. Configured animation settings for each interaction
6. Created keyframes for complex animations
7. Applied Smart Animate for smooth transforms
8. Tested all navigation paths and interactions

### Design Considerations
- **Mobile-first design** optimized for phone screens
- **Consistent navigation** across all pages
- **Visual hierarchy** guiding user attention
- **Interaction feedback** confirming user actions
- **Performance** optimized animation timings

---

## Files Included

- `Land-of-Harmony-Design.pdf` - Visual documentation of the design
- `Land-of-Harmony.fig` - Figma source file (available upon request)
- Screenshots showing key interactions and frames

---

## Key Learning Outcomes

1. Understanding of Figma prototyping workflow
2. Implementation of various transition animations
3. Creation of interactive hotspots and connections
4. Use of Smart Animate for smooth transforms
5. Keyframe animation techniques (tweening/inbetweening)
6. User flow design and navigation patterns
7. Mobile prototype presentation methods

---

## Design Principles Applied

- **Affordances:** Clear visual indicators for interactive elements
- **Constraints:** Guided navigation preventing user confusion
- **Feedback:** Visual responses to user interactions
- **Consistency:** Uniform design language throughout
- **Simplicity:** Clean interface focusing on content
- **Harmony:** Peaceful aesthetic matching the theme

---

## Future Enhancements

- Additional landmarks and points of interest
- Sound effects for ambient atmosphere
- More complex animation sequences
- Interactive map overview
- User preferences and customization
- Multilingual support

---

## Notes

- This project demonstrates educational use of prototyping tools
- Images used are for non-commercial educational purposes
- Design created as part of ENSE 271 coursework at University of Regina

---

**Repository:** [Design-project](https://github.com/Dooms-d/Design-project)  
**Contact:** Sheikh Chand Muhammad Shami
