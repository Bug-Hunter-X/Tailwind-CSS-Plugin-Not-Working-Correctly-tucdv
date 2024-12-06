# Tailwind CSS Plugin Bug

This repository contains a bug report for a Tailwind CSS plugin that is not working correctly in some cases. The gradient is not being applied correctly, resulting in a solid color instead.

## Bug Description

The plugin is not working properly, resulting in unexpected styling. The gradient is not being applied correctly, but instead the color is applied as a solid color.

## Bug Reproduction

1. Install the plugin.
2. Add the gradient class to an element.
3. Observe that the gradient is not applied correctly.

## Solution

The solution is to add the following CSS to your project:
```css
.bg-gradient-to-r {
  background-image: linear-gradient(to right, #ff0000, #0000ff);
}
```