🇩🇪 [Deutsche Version](README.de.md)

# Age Group Calculator for Running (DLV Rules)

A simple age group calculator for running events based on the rules of the German Athletics Association (DLV). It is a single HTML file and can be embedded in WordPress.

## Features

- Calculates the age group from competition year, gender and date of birth
- Covers children, youth, juniors, U23, senior athletes and Masters (M/W30 and up, in 5-year steps)
- No dependencies, no external libraries
- Responsive layout
- Interface language: German

## How it works

According to the DLV competition rules, the age reached in the competition year is decisive:

```
Age = competition year − year of birth
```

The exact birthday does not matter.

## Usage

### Embed in WordPress

1. Open the page or post where the calculator should appear.
2. Add a **Custom HTML** block.
3. Copy the full content of `age-group-calculator.html` into the block.
4. Save or publish the page.

### Use standalone

Download `age-group-calculator.html` and open it in any modern browser.

## Customization

- **Colors and layout:** Edit the CSS in the `<style>` section (classes start with `akr-`).
- **Age groups:** Adjust the function `ermittleAltersklasse` in the `<script>` section.

## Disclaimer

This tool is provided without warranty. For binding registrations, always refer to the current event announcement and the official DLV competition rules.

## License

Released under the [MIT License](LICENSE).
