# Tailwind: creating card components

## Quick Start with UI-Tailwind-Boilerplate

This repository has been set-up with support for Tailwind CSS. Please follow the setup instructions below to use the boilerplate correctly:

<br>

1. Upon cloning the repository, go into the project directory and Install the required dev-dependencies by running

   ```bash
       npm install
   ```

<br>

2.  To start using the project, run the watch command. This would compile your `input.css` file to `output.css` in the `dist` folder.

    ```bash
        npm run tailwind:watch
    ```

    This starts the Tailwind CLI build process<br>
    **Note: You still need to use the live-server (Go Live) extension to preview your HTML. To stop the watch-mode simply press `ctrl + c`**

---

# Task

Create a grid with the speculative listing of items (e.g. cards with properties, events, items in the store, members of the team and so on).

Card (aka component) should contain following information:

- [Optional] Image (use placeholders, e.g. [https://placehold.co/](https://placehold.co/))
- Title
- Short description (1-2 sentences)
- Link(s) or button(s)
- Icon to mark item as a favourite
- [Optional] Any additional information that might be relevant for your speculative use case (e.g. rating, list of icon list to social channels and so on)

Listing should:

- be responsive and layout of the components should adjust as well when needed.
- contain 3+ cards to reflect the responsive behaviour of the layout.

Your demo page should explicitly contain a variant of the card when the item is added to favourite.

## Bonuses

1. Card should have a hover effect with use of animation
2. Create one more variant for a featured item in the list. E.g. it takes up more space, has more prominent typography and different color schemes.
