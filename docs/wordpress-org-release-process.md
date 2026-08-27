# WordPress.org Release Process

SEO Repair Kit production releases are distributed through WordPress.org.

## Public Plugin Page

https://wordpress.org/plugins/seo-repair-kit/

## Release Flow

1. Development happens in the private company repository.
2. Code is reviewed and prepared for production release.
3. Stable version is updated.
4. Plugin package is released to WordPress.org.
5. Public documentation and release notes are updated here.
6. When safe, a sanitized public evidence snapshot is added for reviewer visibility.

## GitHub vs WordPress.org

GitHub releases and WordPress.org releases are separate systems.

A GitHub release does not automatically update WordPress.org unless a deployment pipeline is configured.

This repository is used for public project documentation and release transparency.

## Current Public Evidence

- v2.1.7: sanitized production snapshot retained for historical comparison
- v2.1.8: WordPress 7.0 compatibility metadata and 404 Monitor pagination repair represented in the release trail
- v2.1.9: sanitized Spam Monitor launch evidence snapshot and compatibility audit retained
- v2.1.10: current WordPress.org release snapshot with WordPress 7.1 compatibility metadata and hardened editor asset loading
