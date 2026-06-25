# Avo Counter

A WordPress plugin that tracks page visits and displays last update information with clean, honest metrics.

## Overview

Avo Counter is a lightweight page visit tracker designed to show real engagement metrics without external dependencies. Each page displays how many times it's been visited and when it was last updated.

## Features

- Per-page visit tracking
- Displays last updated date for each page
- Clean card-based design with blue accent bar
- Admin dashboard showing all page statistics
- Shortcode-based display system
- Mobile responsive
- No external services required

## Installation

1. Clone or download this repository
2. Place the `avo-counter` folder in your WordPress `wp-content/plugins/` directory
3. Go to WordPress Admin > Plugins and activate "Avo Counter"
4. Add the shortcode `[avo_counter]` to your page or post footer

## Usage

### Display the Counter

Add this shortcode anywhere in your page or post content:

```
[avo_counter]
```

This will display a card showing:
- Page Activity label
- Number of visits to that specific page
- Last updated date

### View Statistics

1. Go to WordPress Admin
2. Navigate to Settings > Avo Counter
3. View all pages ranked by visit count
4. Customize the counter start date if needed

## Display Format

The counter displays as a clean card:

```
PAGE ACTIVITY
This page has been visited [count] times. Last updated: [date]
```

## Styling

The counter uses a card design with:
- White background
- Blue top accent bar (#002f6c)
- Responsive layout
- Hover effect that lifts the card

Custom styling can be modified by editing the CSS in the plugin settings or overriding classes in your theme.

## Technical Details

- Tracks visits per page using WordPress post meta
- Stores visit count in `avo_counter_page_[page_id]`
- Uses WordPress hooks for tracking and display
- No database tables required, uses existing wp_postmeta

## Requirements

- WordPress 5.0+
- PHP 7.2+

## License

GPL2 - See LICENSE file

## Author

AvocadoWeb Services

## Support

For issues or questions, visit the GitHub repository.
