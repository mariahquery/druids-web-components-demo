# DRUIDS Web Components demo

Welcome to the DRUIDS Web Components demo! This README provides an overview of the project, setup instructions, and other essential information.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The DRUIDS Web Components demo was created to demonstrate how one of the DRUIDS components can be developed using the Web Components technologies, along with Lit and Vite frameworks. In this case, I developed the Avatar component, based on the DRUIDS by Datadog.

## Installation

To install the DRUIDS Web Components demo, you can use npm on app:

```bash
npm install
```

To run the project with vite, you can use npm on app:
```bash
npm run dev
```

## Usage

Here is a basic example of how to use the DRUIDS Web Component in your project:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./src/index.css" />
    <script type="module" src="/src/component/druids-avatar.ts"></script>
    <title>DRUIDS Web Component Example</title>
  </head>
  <body>
    <druids-avatar src="https://images.unsplash.com/photo-1517849845537-4d257902454a?h=208&fit=crop&w=208&q=80" size="xxl" title="I‘m a size xxl avatar"></druids-avatar>
  </body>
</html>
```
