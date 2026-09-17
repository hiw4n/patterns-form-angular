# Patterns Form Angular

Reusable, accessible, and configurable form patterns built with Angular.

This repository is part of a learning and experimentation project focused on designing reusable form architectures for real-world scenarios such as checkout, billing, shipping, and country-specific data requirements.

## Goals

The project aims to explore and implement:

- Reusable Angular form components
- Reactive Forms
- Dynamic fields and validation
- Country-specific form configuration
- Billing and shipping scenarios
- Individual and business customer requirements
- Accessible form patterns
- Responsive layouts
- Maintainable and scalable form architecture

## Tech Stack

- Angular 22
- TypeScript
- Reactive Forms
- SCSS
- RxJS
- Vitest
- ESLint
- Prettier
- GitHub Actions
- GitHub Codespaces

## Project Structure

This repository uses an Angular workspace containing a reusable library and a demo application.

```text
patterns-form-angular/
├── .devcontainer/
├── .github/
│   └── workflows/
│       └── ci.yml
├── projects/
│   ├── checkout-form/
│   │   └── Reusable Angular form library
│   └── demo/
│       └── Application used to develop and test the library
├── angular.json
├── package.json
└── tsconfig.json