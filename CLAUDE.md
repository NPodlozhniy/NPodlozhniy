# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the GitHub profile repository for [NPodlozhniy](https://github.com/NPodlozhniy). The `README.md` is rendered automatically on the GitHub profile page at `github.com/NPodlozhniy`.

## Structure

- `README.md` — Profile page content, written in HTML (not Markdown) for fine-grained layout control
- `LinkedInQr.png` — QR code image displayed in the top-right corner of the profile, linking to LinkedIn

## README Conventions

- Layout uses raw HTML (`<table>`, `<p align>`, `<a>`, `<img>`) rather than Markdown syntax
- Skill icons are sourced from external CDNs: `devicons`, `jsdelivr`, `svgrepo`, `brandfetch`
- Icon sizes follow an established pattern: `width="40" height="40"` for most icons, with occasional exceptions (e.g. dbt logo uses `width="60"`)
- The QR code image is referenced via an absolute GitHub raw URL pointing to the `master` branch

## Making Changes

When updating skills or tools in the README, use `href` links to official product pages and source icon SVGs from `https://cdn.jsdelivr.net/gh/devicons/devicon@latest/` (preferred) or `https://raw.githubusercontent.com/devicons/devicon/master/` for Devicons assets. Always verify that image URLs resolve correctly before committing.
