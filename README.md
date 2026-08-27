# DevArt Exams for Joomla

Modern examination and quiz package for Joomla 6, designed for certification systems, training platforms, learning portals, educational websites, and large question banks.

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.3%2B-green)
![Release](https://img.shields.io/badge/Version-1.0.6-orange)
![License](https://img.shields.io/badge/License-GPLv3-red)

---

## Overview

DevArt Exams is a modern Joomla 6 examination and quiz package built for secure, scalable and production-ready exam delivery.

It is designed for certification systems, radio amateur preparation platforms, employee training programs, educational websites, online testing environments and large question banks.

The package focuses on clean Joomla 6 architecture, frontend usability, production reliability, secure exam handling and efficient administration workflows.

---

## Features

### Exam Engine

- Real exam mode
- Learning / practice mode
- Configurable pass percentage
- Configurable question limits per level
- Configurable attempt limits
- Optional guest access
- Timer support with server-side enforcement
- Automatic pass / fail evaluation
- Official exam result storage
- Instant feedback in learning mode
- Answer explanations support
- Flagged questions for review
- Progress tracking
- Section-based performance analytics
- Weak area analysis
- Duplicate submission protection
- Attempt question whitelist and session integrity protections
- Cache-safe exam session handling (`Cache-Control: no-store`)

### Learning Mode

- Random exam-sized practice sessions
- Full level question bank learning
- Menu-controlled learning behavior
- Optional frontend user mode selection

### Question Bank Management

Structured hierarchy:

- Packages
- Levels
- Sections
- Questions
- Answers

Features:

- Multiple choice question workflows
- Unlimited answer options per question
- Image support for questions and answers
- CSV import with validation preview
- JSON import/export for site-to-site migrations
- Data tools for diagnostics and safe cleanup
- ACL-aware administrator workflow
- Hub-style administrator dashboard

---

## Requirements

- Joomla 6.0+
- PHP 8.3.0+
- MySQL/MariaDB with utf8mb4 support

---

## Installation

Install `pkg_devartexams_v1.0.6.zip` through Joomla Extensions → Install.

The package contains only `com_devartexams`.

Joomla native updates use a single package update URL:

https://raw.githubusercontent.com/devartgr/joomla-devart-exams/main/update.xml

---

## Languages

Bundled locales:

`en-GB`, `el-GR`, `fr-FR`, `de-DE`, `es-ES`, `it-IT`, `pt-BR`, `cs-CZ`,
`nl-NL`, `pl-PL`, `ru-RU`, `uk-UA`, `ja-JP`, `tr-TR`, `zh-CN`

---

## Cloudflare / full page cache

Active exam runner, submit and result pages must remain excluded from Cloudflare full page cache.

Recommended bypass: frontend `option=com_devartexams` (or the exam menu item).

Excluding only the submit URL is **not** sufficient for real exam mode.

---

## Uninstall data policy

The component option **Keep Data on Uninstall** defaults to **No**. When disabled, uninstall removes DevArt Exams database tables. Enable it only when you intentionally want to preserve data across uninstall/reinstall.

---

## License

GNU General Public License version 3 or later.

## Author

Stathopoulos Kostas - DevArt  
https://devart.gr
