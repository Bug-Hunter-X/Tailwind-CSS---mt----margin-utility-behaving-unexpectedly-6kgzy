# Tailwind CSS Unexpected Margin Issue

This repository demonstrates an uncommon bug encountered when using Tailwind CSS's margin utilities (`mt-*`) in conjunction with padding utilities (`p-*`).  Specifically, the `mt-4` class doesn't apply the expected margin when nested within a parent div that already has padding (`p-4`).

## Bug Description

The expected behavior is that a `mt-4` class should add a 1rem (16px by default) margin to the top of the element. However, in the scenario outlined, it fails to apply, resulting in unexpected spacing and layout issues.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the unexpected spacing in the rendered component.

## Solution

The solution involves overriding the default margin behaviour with specific class or using a different utility.

See `solution.js` for the implemented solution.