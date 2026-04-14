# Astro + React + TypeScript + shadcn/ui

This is a template for a new Astro project with React, TypeScript, and shadcn/ui.

## Adding components

To add components to your app, run the following command:

```bash
npx shadcn@latest add button
```

This will place the ui components in the `src/components` directory.

## TODO

- Remove the AI generated mock data with mine
- Add contact form integration with Web3Forms or another provider
- Add a CV download action
- Adjust the styles to remove unnecessary artifacts and contrast issues
- Fix mobile layout
- Add a picture of me in the hero

## Using components

To use the components in your app, import them in an `.astro` file:

```astro
---
import { Button } from "@/components/ui/button"
---

<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Astro App</title>
  </head>
  <body>
    <div class="grid h-screen place-items-center content-center">
      <Button>Button</Button>
    </div>
  </body>
</html>
```

