# Skyscanner Backpack React Task

A React web application built with **Skyscanner Backpack** as part of the **Skyscanner Software Engineering Virtual Experience**.

## Overview

This project demonstrates a flight-schedule interface using Skyscanner's Backpack component library. The current implementation provides an interactive calendar where a user can:

- View the current month and move between months.
- Select a travel date.
- See the selected date reflected in the calendar.
- Continue from the selected date using a Backpack button.

This is a frontend simulation and does not connect to a live flight-search API or backend.

## Tech Stack

- React 17
- JavaScript
- Sass (SCSS)
- Skyscanner Backpack Web
- `@skyscanner/backpack-react-scripts`
- npm

## Backpack Components

The interface uses:

- `BpkCalendar`
- `BpkButton`
- `BpkText`

The calendar is configured for single-date selection, month navigation, and accessible labels for its controls.

## Project Structure

```text
.
├── public/
│   ├── index.html
│   ├── manifest.json
│   └── ...
├── src/
│   ├── App.js
│   ├── App.scss
│   ├── App.test.js
│   └── index.js
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

## Running Locally

### Prerequisites

- Node.js
- npm

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm start
```

Open http://localhost:3000 in your browser.

### Run tests

```bash
npm test
```

### Create a production build

```bash
npm run build
```

## Project Context

This repository is part of the Skyscanner Software Engineering Virtual Experience and uses the Backpack design system to build a React travel interface.

The implementation is intentionally focused on the frontend task rather than a production flight-search service.
