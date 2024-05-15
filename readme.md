# Base/Reset CSS

This repository contains a base/reset CSS file that establishes a consistent baseline for styling across browsers. It sets up a clean slate with sensible defaults, optimized for performance and accessibility.

## Features

- **Modern Typography**: Uses system and optimized fonts for headings and body to enhance readability.
- **Responsive Fonts**: Font sizes adjust to screen sizes using `clamp`.
- **Consistent Box Sizing**: Applies `box-sizing: border-box` to all elements for consistent sizing.
- **Smooth Scrolling**: Enables smooth scrolling behavior within the webpages.
- **Accessibility Ready**: Provides styles to support screen readers and reduce motion for users who prefer it.

## Usage

To integrate this CSS into your project, link it in your HTML:

```html
<link rel="stylesheet" href="path/to/base.css" />
```

## Customization

Customize the CSS by overriding the predefined variables in your own stylesheets or modifying them directly in the base/reset file.

## Font Pairings

Here are some system font stack pairings from [Modern Font Stacks](https://modernfontstacks.com/). I currently have Rounded Sans as heading text, and System UI for body text, but feel free to change them! The CSS variables to change for fonts are --font-family and --heading-font-family, respectively.

### Professional and Clean

- **Headings:** Neo-Grotesque
- **Body Text:** Neo-Grotesque
- This pairing uses clean, geometric forms that are modern and straightforward, ideal for corporate or business-oriented designs.

### Modern and Elegant

- **Headings:** Didone
- **Body Text:** Slab Serif
- Featuring high contrast in the headings with the thick and thin strokes of Didone, and balanced with the sturdy serifs of Slab Serif, this pairing suits luxury brands and elegant publications.

### Classic and Readable

- **Headings:** Old Style
- **Body Text:** Old Style
- Both fonts are highly readable with a classic touch, making them perfect for traditional or academic documents where readability is paramount.

### Contemporary and Dynamic

- **Headings:** Geometric Humanist
- **Body Text:** Humanist
- Geometric Humanist offers a clean and modern geometric appearance for headings, while Humanist keeps the body text approachable and clear.

### Technical and Informative

- **Headings:** Monospace Slab Serif
- **Body Text:** Monospace Code
- This pairing is great for technical documents, coding environments, or any setting where a monospaced font enhances the data's structure and readability.

### Youthful and Friendly

- **Headings:** Rounded Sans
- **Body Text:** Neo-Grotesque
- Rounded Sans’s rounded edges make headings feel more approachable, complemented by the familiar simplicity of Neo-Grotesque for body text, suitable for informal or youth-oriented designs.

### Sophisticated and Editorial

- **Headings:** Didone
- **Body Text:** Antique
- Didone provides a stylish and high-impact look for headings, while Antique offers excellent readability and a slightly historic vibe for longer reads.

## Acknowledgements

This CSS base/reset file was initially inspired by ideas from Josh W. Comeau's custom CSS reset; I've obviously added a lot more! For more details on his approach, visit [Josh's CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/). I also threw in some of Swyx's [100 Bytes of CSS to look great everywhere](https://www.swyx.io/css-100-bytes) in the html/body tag section (commented out).

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for more details.
