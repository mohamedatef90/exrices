# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML page displaying a knee rehabilitation and strengthening exercise program. The interface is in Arabic (RTL layout) and presents exercises organized into three categories via a tab-based UI.

## Structure

Single file: `index.html` - self-contained with inline CSS and JavaScript. No build process or dependencies.

## Running

Open `index.html` directly in a browser. No server required.

## Architecture

- **CSS**: CSS custom properties for theming (dark glassmorphism design), responsive grid layout
- **JavaScript**: Single `show(event, id)` function handles tab switching
- **Content**: Three exercise sections (pre-workout, post-workout, daily) with cards displaying exercise images from external URLs
