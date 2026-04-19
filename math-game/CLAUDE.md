# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Interactive circle geometry learning for 8th graders. Self-contained HTML pages with all CSS and JavaScript inline (no build system, no dependencies).

## Files

- **index.html** — Math games hub page linking to available games
- **circle-explorer-8th.html** — Interactive circle explorer with Learn, Playground, and Quiz tabs
- **chapter7-prep.html** — Chapter 7 (Marshall Cavendish Course 2B) prep page: composite area, prism volume, surface area — formula cards + worked examples with canvas diagrams

## Development

No build step. Open any HTML file directly in a browser. All files are fully self-contained with no external dependencies.

## Architecture Notes

- Interactivity is implemented via inline `<script>` tags using vanilla JS and HTML5 Canvas.
- Styles are embedded in `<style>` blocks within each file.
- Links use relative paths so files work when opened directly from Finder.
