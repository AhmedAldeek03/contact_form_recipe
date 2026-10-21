# Contact form

Adds a **Contact us** webform (`contact_us`) at `/contact-us`.

## What it adds

- Name, email, phone, subject and message
- Sends each message to the site email address, with the visitor as reply-to
- Shows a thank-you message after sending

## Blocks and pages

- Place it anywhere with the **Webform** block, or link to `/contact-us`.

## Requirements

- Drupal 11
- Webform

## Installation

```bash
composer config repositories.contact_form_recipe '{"type": "vcs", "url": "https://github.com/AhmedAldeek03/contact_form_recipe", "no-api": true}'
composer require drupal/contact_form_recipe:1.0.x-dev@dev
drush recipe ../recipes/contact_form_recipe
drush cache:rebuild
```

With DDEV, put `ddev` before each command.
