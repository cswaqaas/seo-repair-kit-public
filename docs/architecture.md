# Architecture Overview

SEO Repair Kit follows a modular WordPress plugin architecture.

## Main Areas

### Admin Layer

Handles WordPress dashboard screens, settings pages, feature interfaces, and user workflows.

### Includes Layer

Contains core plugin services, loaders, activators, AJAX handlers, helpers, and backend logic.

### Public Layer

Handles frontend-facing SEO output, schema rendering, public assets, and site-facing behavior.

### Feature Modules

Current and planned feature areas include:

- Link Scanner
- Schema Manager
- Meta Manager
- Redirect Manager
- KeyTrack
- Spam Monitor
- Internal Linking

## Engineering Principles

- modular feature isolation
- WordPress coding standards
- nonce and capability checks
- limited global asset loading
- admin-only assets where possible
- database safety
- extensible hooks and filters
- backward compatibility
- production-safe migrations