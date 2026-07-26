# Contribution Snake Animation

This branch contains the auto-generated contribution graph snake animation, updated daily via GitHub Actions using [Platane/snk](https://github.com/Platane/snk).

## Files

| File | Description |
|------|-------------|
| `github-contribution-grid-snake.svg` | Snake animation — light mode |
| `github-contribution-grid-snake-dark.svg` | Snake animation — dark mode |

## How It Works

1. A GitHub Actions workflow runs daily at midnight UTC
2. The workflow generates SVG animations of the contribution graph
3. The SVGs are deployed to this `output` branch
4. The main `README.md` references these SVGs for display

## Updating

Trigger the workflow manually from the **Actions** tab using "Run workflow", or wait for the daily schedule.
