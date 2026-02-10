# Implementation Plan: Valentine Email

## Overview

Build a fun Valentine's Day prank with 3 static HTML pages. No backend, no tests - just cute, working code.

## Tasks

- [x] 1. Create the Landing Page with Dodging Button
  - [x] 1.1 Create valentine.html with basic structure
    - Add Valentine question title with optional name personalization from URL param
    - Add Yes and No buttons with Valentine styling
    - _Requirements: 2.1, 2.2_
  
  - [x] 1.2 Implement the dodging No button logic
    - Add mouseover/mouseenter event listener to No button
    - Calculate new position away from cursor
    - Keep button within viewport bounds
    - Animate button movement with CSS transition
    - _Requirements: 3.1, 3.2_
  
  - [x] 1.3 Wire up Yes button to navigate to success page
    - Add click handler to navigate to success.html
    - _Requirements: 4.1_

- [x] 2. Create the Success Celebration Page
  - [x] 2.1 Create success.html with celebration content
    - Add big celebratory title with heart emoji
    - Add sweet message
    - Add cute image (heart, romantic illustration, or gif)
    - Style with Valentine theme matching landing page
    - _Requirements: 4.2_

- [x] 3. Create the Sender Page
  - [x] 3.1 Create index.html with link generator
    - Add title and instructions
    - Add optional name input field
    - Add button to generate/copy shareable link
    - Display the generated link for easy copying
    - _Requirements: 1.1, 1.2_

- [x] 4. Final Polish
  - [x] 4.1 Add consistent Valentine styling across all pages
    - Pink/red color scheme
    - Heart decorations or emoji
    - Playful, rounded button styles
    - Mobile-friendly layout
    - _Requirements: 2.2_

## Notes

- All files are static HTML/CSS/JS - can be hosted on GitHub Pages, Netlify, or any static host
- No build step required - just open index.html in a browser to test
- Keep the code simple and fun - this is a prank, not production software!
