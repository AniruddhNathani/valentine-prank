# Requirements Document

## Introduction

A fun, scrappy Valentine's Day email prank inspired by viral social media posts. Send someone a "Will you be my Valentine?" email with Yes/No buttons - but the No button dodges away when they try to click it! When they inevitably click Yes, they see a cute celebration page.

## Glossary

- **Landing_Page**: The web page with the Yes/No buttons that the recipient sees
- **Success_Page**: The cute celebration page shown after clicking Yes
- **Dodging_Button**: The "No" button that runs away from the cursor

## Requirements

### Requirement 1: Valentine Email

**User Story:** As a sender, I want to send a Valentine's email with a link to the interactive page.

#### Acceptance Criteria

1. THE Email_Service SHALL send an email with subject "Will you be my Valentine?" containing a link to the Landing_Page
2. THE Email_Service SHALL include a cute Valentine-themed message in the email body

### Requirement 2: Interactive Landing Page

**User Story:** As a recipient, I want to see a cute page with Yes and No buttons.

#### Acceptance Criteria

1. WHEN a recipient clicks the email link, THE Landing_Page SHALL display "Will you be my Valentine?" with Yes and No buttons
2. THE Landing_Page SHALL have Valentine-themed styling (pink/red colors, hearts, etc.)

### Requirement 3: Dodging No Button

**User Story:** As a sender, I want the No button to dodge away so the recipient can't click it.

#### Acceptance Criteria

1. WHEN a recipient hovers over or moves toward the "No" button, THE Dodging_Button SHALL move to a random position away from the cursor
2. THE Dodging_Button SHALL stay within the visible screen area when dodging

### Requirement 4: Yes Button Success

**User Story:** As a recipient, I want to see a celebration when I click Yes.

#### Acceptance Criteria

1. WHEN a recipient clicks the "Yes" button, THE Landing_Page SHALL navigate to the Success_Page
2. THE Success_Page SHALL display a celebratory message and a cute image
