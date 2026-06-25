# Avo Counter - WordPress Plugin Standards

This plugin follows WordPress plugin development standards and best practices.

## Plugin Header

The plugin header in `avo-counter.php` includes:
- Plugin Name
- Plugin URI
- Description
- Version
- Author
- Author URI
- License

## Code Standards

- Uses WordPress hooks for functionality
- Follows WordPress naming conventions
- Uses proper escaping functions
- Implements security best practices
- Database queries use WordPress abstractions

## Security

- Sanitizes all inputs
- Validates user permissions
- Uses nonces for admin actions (where applicable)
- Escapes output appropriately

## Performance

- Minimal database queries
- Uses WordPress post meta efficiently
- No external API calls
- Lightweight CSS styling

## Compatibility

- Works with WordPress 5.0+
- Compatible with PHP 7.2+
- Theme-agnostic design
- Mobile responsive

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Clear labels for UI elements
