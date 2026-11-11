# Book Loop

> University group project (ESMAD, 2024). Not in active development.

Web app for Book Loop, a social platform for readers: catalogue books, review them, follow other readers and sell second-hand copies.

API: [book-loop-api](https://github.com/pgraca97/book-loop-api)

## My role

Built with [Victoria Martínez](https://github.com/pistashioz). I built the account and community side: login, registration and password reset, profiles with followers and following, account settings, favourite genres and authors, second-hand listings and the users admin page. Victoria built the book catalogue: works and editions, literary reviews and comments, and the catalogue admin pages.

## Tech stack

Nuxt 3 (client-side only), Vue 3, Pinia with persisted state, Tailwind CSS with Flowbite, Axios, and Azure Blob Storage for images.

## Highlights

- **Listing photos.** Sellers add photos, reorder them by dragging and rotate them before publishing.
- **Settings by concern.** Account, privacy, notifications and security each have their own section under a dedicated settings layout.
- **Profiles as a social hub.** Followers and following, favourite authors and genres, and the user's listings in one place.

## Status

The API this app talks to no longer runs (see [book-loop-api](https://github.com/pgraca97/book-loop-api#status)), so the app starts but can't load any data.

To start it anyway:

```bash
npm install
npm run dev
```

It reads `API_BASE_URL` (defaults to `http://localhost:3360/`) and `SAS_URL` for images.