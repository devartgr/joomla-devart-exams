# DevArt Exams for Joomla

Modern examination and quiz component for Joomla 6, designed for certification systems, training platforms, learning portals, and large question banks.

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.2%2B-green)
![Release](https://img.shields.io/badge/Version-1.0.1-orange)
![License](https://img.shields.io/badge/License-GPLv3-red)

---

## Overview

DevArt Exams is a modern Joomla 6 examination and quiz component built for stable, secure, scalable exam delivery and learning workflows.

It is designed for certification exams, educational platforms, radio amateur preparation systems, employee training, online testing environments, and large-scale question banks.

The component focuses on clean Joomla 6 architecture, production reliability, frontend usability, security, social sharing compatibility, and performance under real-world workloads.

---

## Features

## Exam Engine

- Real exam mode
- Learning / practice mode
- configurable pass percentage
- configurable question limits per level
- configurable attempts limits
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
- study systems
- educational portals
- exam rehearsal workflows

---

## Question Bank Management

Structured hierarchy:

- Packages
- Levels
- Sections
- Questions
- Embedded Answers

Features:

- multiple choice question workflows
- 4-answer support
- image support for questions
- image support for answers
- explanations
- optional difficulty field
- publishing controls
- administrator filtering
- sorting
- bulk operations

---

## Bulk Tools

Administrator bulk tools include:

- bulk section reassignment
- bulk difficulty updates
- bulk publish / unpublish
- bulk delete workflows

Designed for large question banks.

---

## Import / Export

### CSV Import

Production-ready question bank import:

- CSV preview before import
- validation before import
- required column validation
- duplicate detection
- per-row validation
- UTF-8 safe Greek support
- package auto creation
- level auto creation
- section auto creation
- answer import validation
- duplicate handling policies

---

### Export

- CSV export
- JSON export
- backup workflows

---

## Results & Analytics

### Exam Results

- official exam result storage
- user exam history
- optional guest result storage
- pass / fail badges
- score tracking
- package / level tracking
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
- fixed package frontend delivery
- fixed level frontend delivery
- real exam mode
- learning mode
- compact question navigator
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
- X / Twitter cards

Metadata priority:

1. Joomla Menu Item social metadata
2. Package social metadata
3. Global component social metadata
4. Site fallback metadata

Designed to avoid conflicts with existing SEO extensions while preserving social sharing compatibility.

---

## Administrator Features

- operational dashboard
- quick navigation cards
- package management
- level management
- section management
- question management
- results management
- options panel
- diagnostics
- data tools

---

## Data Tools

Built-in maintenance tools:

- orphan data checks
- duplicate question finder
- integrity diagnostics
- cleanup tools
- stale data review

Designed for production administration.

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
- no N+1 question loading patterns
- frontend no-store cache protection for active exam sessions
- large question bank support
- efficient results handling
- bulk administrator operations
- Cloudflare-friendly architecture
- high-traffic safe design

Validated with:

- 1000+ imported questions
- 4000+ answers
- large CSV import workflows

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

- fixed exam package
- fixed exam level
- real exam delivery
- learning mode delivery
- learning all questions mode
- user choice learning mode

Ideal for:

- certification portals
- training portals
- educational websites
- radio amateur preparation systems
- internal training platforms

---

## Joomla Native Updates

DevArt Exams supports Joomla native updates via GitHub.

After installation:

`System → Extensions → Update`

Update server:

`https://raw.githubusercontent.com/devartgr/joomla-devart-exams/main/update.xml`

---

## Compatibility Notes

Supported:

- Joomla 6.x
- PHP 8.2+
- Joomla native update system
- Cloudflare deployments
- modern Joomla MVC architecture
- Facebook crawler compatibility
- X / Twitter social sharing previews

Not supported:

- Joomla 3
- Joomla 4
- Joomla 5
- legacy PHP versions

---

## Current Version

1.0.1

---

## Release Highlights

### Included

- full modern Joomla 6 architecture
- production-ready exam engine
- learning engine
- question bank management
- CSV import/export
- analytics
- diagnostics
- data tools
- ACL permissions
- social metadata support
- clean installer
- GitHub update support

---

## Recommended Production Workflow

### Exam Systems

1. Create package
2. Create levels
3. Create sections
4. Import questions
5. Configure level rules
6. Configure social metadata if needed
7. Create frontend menu items
8. Publish

---

### Large Question Banks

Recommended:

- use CSV import
- organize by sections
- use level-specific limits
- enable diagnostics review periodically

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

DevArt shall not be held liable for any damages, data loss, downtime, security issues, or other problems resulting from the use or misuse of this software.

Users are responsible for testing the software in their own environment and maintaining proper backups before installation or upgrades.

Always test on a staging environment before using in production.

---

## License

GNU General Public License v3 or later
