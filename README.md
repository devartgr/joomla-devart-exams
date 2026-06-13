# DevArt Exams for Joomla

Modern examination and quiz component for Joomla 6, designed for certification systems, training platforms, learning portals, educational websites, and large question banks.

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.2%2B-green)
![Release](https://img.shields.io/badge/Version-1.0.2-orange)
![License](https://img.shields.io/badge/License-GPLv3-red)

---

## Overview

DevArt Exams is a modern Joomla 6 examination and quiz component built for secure, scalable and production-ready exam delivery.

It is designed for certification systems, radio amateur preparation platforms, employee training programs, educational websites, online testing environments and large question banks.

The component focuses on clean Joomla 6 architecture, frontend usability, production reliability, Cloudflare compatibility, secure exam handling and efficient administration workflows.

---

## Features

## Exam Engine

- Real exam mode
- Learning / practice mode
- configurable pass percentage
- configurable question limits per level
- configurable attempt limits
- optional guest access
- timer support
- automatic pass / fail evaluation
- official exam result storage
- instant feedback in learning mode
- answer explanations support
- flagged questions for review
- compact frontend navigation
- progress tracking
- section-based performance analytics
- weak area analysis
- duplicate submission protection
- cache-safe exam session handling

---

## Learning Mode

Learning mode supports multiple workflows:

- random exam-sized practice sessions
- full level question bank learning
- menu-controlled learning behavior
- optional frontend user mode selection

Ideal for:

- certification preparation
- educational portals
- training systems
- exam rehearsal workflows
- self-study platforms

---

## Question Bank Management

Structured hierarchy:

- Packages
- Levels
- Sections
- Questions
- Answers

Features:

- multiple choice question workflows
- unlimited answer options per question
- image support for questions
- image support for answers
- explanations support
- publishing controls
- administrator filtering
- sorting
- bulk operations
- large question bank support

---

## Dynamic Answer Options

Questions are no longer limited to four answers.

Features:

- unlimited answer options
- add answer button
- remove answer button
- flexible certification workflows
- advanced exam support
- large educational question bank compatibility

Ideal for:

- certification systems
- government exams
- technical examinations
- educational institutions
- radio amateur examinations

---

## Bulk Tools

Administrator bulk tools include:

- bulk section reassignment
- bulk publish / unpublish
- bulk delete workflows
- batch maintenance operations

Designed for large question banks and production administration.

---

## Import / Export

### CSV Import

Production-ready CSV import system:

- CSV preview before import
- validation before import
- required column validation
- duplicate detection
- per-row validation
- UTF-8 safe Greek support
- package auto creation
- level auto creation
- section auto creation
- answer validation
- duplicate handling policies

---

### JSON Import

Full DevArt Exams migration support:

- import exported DevArt Exams backups
- package import
- level import
- section import
- question import
- answer import
- validation before processing
- production migration workflows

Ideal for:

- moving exam systems between websites
- staging to production migrations
- backup restoration
- question bank distribution

---

### Export

- CSV export
- JSON export
- backup workflows
- migration workflows

---

## Results & Analytics

### Exam Results

- official exam result storage
- user exam history
- optional guest result storage
- pass / fail badges
- score tracking
- package tracking
- level tracking
- timestamp tracking

---

### Review & Analysis

- detailed answer review
- correct answer display
- wrong answer display
- explanations
- section statistics
- weak area detection
- learning improvement insights

---

## Frontend Features

- Joomla menu item integration
- fixed package delivery
- fixed level delivery
- real exam mode
- learning mode
- compact navigator
- progress display
- jump to question
- flagged review workflow
- mobile-friendly frontend
- cache-safe runtime behavior

---

## Social Sharing Metadata

DevArt Exams includes social sharing support for public exam pages.

Supported:

- Facebook Open Graph
- X / Twitter Cards

Metadata priority:

1. Joomla Menu Item metadata
2. Package metadata
3. Global component metadata
4. Site fallback metadata

Designed to coexist with SEO and social sharing extensions.

---

## Administrator Features

- operational dashboard
- package management
- level management
- section management
- question management
- results management
- diagnostics tools
- data tools
- ACL permissions integration
- component options panel

---

## Data Tools

Built-in maintenance tools:

- orphan data checks
- duplicate question detection
- integrity diagnostics
- cleanup tools
- stale data review

Designed for production administration and long-term maintenance.

---

## Security Highlights

- Joomla ACL permissions
- Joomla Permissions integration
- CSRF protection
- SQL injection protection
- XSS-safe output handling
- attempt token validation
- duplicate submit protection
- rate limiting safeguards
- secure uninstall workflows
- optional Keep Data uninstall behavior

---

## Performance

Built for production environments.

Features include:

- optimized database query workflows
- efficient question loading
- large question bank support
- efficient results handling
- bulk administrator operations
- Cloudflare-friendly architecture
- high-traffic safe design

Production exam pages use protected runtime handling to prevent cached submissions and stale session data during active exams.

Validated with:

- 1000+ imported questions
- 4000+ answers
- large CSV imports
- large JSON migrations

---

## Cloudflare Compatibility

DevArt Exams is designed for Cloudflare-powered Joomla websites.

Recommended configuration:

- cache normal content pages
- cache categories
- cache articles
- cache static assets

Do not cache:

- active exam runner pages
- exam submission pages
- active exam result processing pages

This prevents invalid session tokens and stale exam submissions.

---

## Requirements

- Joomla 6.x
- PHP 8.2+

---

## Installation

1. Download the latest release from GitHub

2. Go to:

`System → Extensions → Install`

3. Upload the component ZIP package

4. Open:

`Components → DevArt Exams`

5. Configure component options

6. Create packages, levels, sections and questions

7. Create frontend menu items

---

## Joomla Menu Integration

DevArt Exams supports Joomla frontend menu items.

Examples:

- fixed package
- fixed level
- real exam mode
- learning mode
- all questions learning mode
- user choice learning mode

Ideal for:

- certification portals
- educational websites
- radio amateur preparation systems
- training organizations
- employee training platforms

---

## Joomla Native Updates

DevArt Exams supports Joomla native updates through GitHub.

After installation:

`System → Extensions → Update`

Update server:

`https://raw.githubusercontent.com/devartgr/joomla-devart-exams/main/update.xml`

---

## Compatibility Notes

Supported:

- Joomla 6.x
- PHP 8.2+
- Joomla native updates
- Cloudflare deployments
- modern Joomla MVC architecture
- Facebook crawler compatibility
- X social sharing previews

Not Supported:

- Joomla 3
- Joomla 4
- Joomla 5
- legacy PHP versions

---

## Current Version

1.0.2

---

## Release Highlights

### Included

- real exam engine
- learning engine
- unlimited answer options
- CSV import/export
- JSON import/export
- results analytics
- diagnostics
- data tools
- ACL permissions
- social metadata support
- Cloudflare compatibility improvements
- GitHub update support

---

## Recommended Production Workflow

### Exam Systems

1. Create package
2. Create levels
3. Create sections
4. Import questions
5. Configure level rules
6. Configure social metadata if required
7. Create frontend menu items
8. Publish

---

### Large Question Banks

Recommended:

- use CSV import for bulk content
- use JSON export for backups
- organize questions by sections
- use level-specific limits
- run diagnostics periodically
- test imports on staging environments

---

## Author

Kostas Stathopoulos  
DevArt  
https://devart.gr

GitHub Repository:

https://github.com/devartgr/joomla-devart-exams

---

## Disclaimer / Limitation of Liability

This software is provided "as is", without warranty of any kind.

DevArt shall not be held liable for any damages, data loss, downtime, security issues, business interruption, or other problems resulting from the use or misuse of this software.

Users are responsible for testing the software in their own environment and maintaining proper backups before installation or upgrades.

Always test on a staging environment before deploying updates to production systems.

---

## License

GNU General Public License v3 or later
