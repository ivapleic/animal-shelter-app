<div align="center">

<img src="public/icons8-animal-shelter-50.png" alt="logo" width="70" />

# Azil za životinje

**An animal shelter web app — browse pets up for adoption, read shelter news and get in touch.**

</div>

<br />

## About

A single-page web app for an animal shelter, built as my final project on the **Junior Developer** course at **EDIT CodeSchool** (a free applied-programming school in Split, Croatia). Visitors can browse the animals available for adoption, filter them, read the shelter's notifications and contact the shelter. An admin mode allows adding new animals, notifications and donations.

The data is served from a local JSON file through `json-server`.

<br />

## Features

- **Animals** — browse all shelter animals, filter by species, gender and adoption status
- **About us** — shelter info, location map and a contact form
- **Notifications** — shelter news, with important ones highlighted
- **Donations** — list of donations
- **Admin mode** — add new animals, notifications and donations

<br />

## Screenshots

<br />

### Animals

<p align="center">
  <img src="docs/screenshots/animals.png" alt="Animals page" width="100%" />
</p>

<br />

### About us

<p align="center">
  <img src="docs/screenshots/about.png" alt="About us page" width="850" />
</p>

<br />

### Notifications

<p align="center">
  <img src="docs/screenshots/notifications.png" alt="Notifications page" width="850" />
</p>

<br />

## Run locally

```bash
npm install

# terminal 1 — backend (data):
npx json-server --watch azil.json --port 3000

# terminal 2 — app:
npm run dev
```

Then open the address Vite prints (usually http://localhost:5173).

<br />

## Built With

React · TypeScript · Vite · React Router · Axios · json-server
