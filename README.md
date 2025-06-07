# Woodmart Child RPG Theme

This repository contains a WordPress child theme based on Woodmart. The theme adds RPG features such as races, abilities and coupon management.

## Checking a user's abilities

Use the WP‑CLI command `wp rpg-check-ability` to view a user's race, level and passive bonuses.

```bash
wp rpg-check-ability --user_id=1
```

If the `--user_id` option is omitted, the command uses the currently logged‑in user.

## Installing

1. Copy the `woodmart-child` folder to your WordPress `wp-content/themes` directory.
2. Activate the "Woodmart Child" theme in the WordPress admin area.
3. Ensure you can run WP‑CLI inside your environment to use the provided command and manage abilities.

## Notes

- PHP must be available for WP‑CLI and linting.
- Some features rely on plugins such as WooCommerce and Dokan.

