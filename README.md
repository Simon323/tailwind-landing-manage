# Tailwind Landing Manage

## Table of contents

- [Tailwind Landing Manage](#tailwind-landing-manage)
  - [Table of contents](#table-of-contents)
  - [Demo](#demo)
  - [Initialize project](#initialize-project)
  - [Install tailwind](#install-tailwind)
  - [Create dev scripts](#create-dev-scripts)
  - [How run](#how-run)

## Demo

| Desktop                           | Mobile                            |
| --------------------------------- | --------------------------------- |
| ![Screen](./assets/screen_01.jpg) | ![Screen](./assets/screen_02.jpg) |

## Initialize project

```bash
npm init - y
```

## Install tailwind

```bash
npm install -D tailwindcss
npx tailwindcss init
```

## Create dev scripts

In `package.json` paste this scripts section

```json
{
  ...
  "scripts": {
    "build": "tailwindcss -i ./input.css -o ./css/main.css",
    "watch": "tailwindcss -i ./input.css -o ./css/main.css --watch"
  },
  ...
}
```

## How run

```bash
npm run watch
```
