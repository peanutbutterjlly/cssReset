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

Here are some system font stack pairings from [Modern Font Stacks](https://modernfontstacks.com/). These use system fonts only - no downloads or external links required.

I currently have Rounded Sans as heading text, and System UI for body text, but feel free to change them! 

To update fonts in your CSS, set:

```css
--heading-font-family: ...;
--font-family: ...;
```

### 1. Both Sans-Serif (Different Fonts)

#### A. Inter (body) + Tahoma (headings)

```css
--font-family: "Inter", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
--heading-font-family: Tahoma, Verdana, Segoe, sans-serif;
```

Crisp UI text paired with tight, readable headers.


#### B. Verdana (body) + Trebuchet MS (headings)

```css
--font-family: Verdana, Geneva, sans-serif;
--heading-font-family: "Trebuchet MS", "Lucida Grande", "Segoe UI", sans-serif;
```

A classic sans body with modern, compact headings.


#### C. Geometric Humanist (headings) + Humanist (body)

```css
--heading-font-family: "Avenir", "Avenir Next", "Segoe UI", "Roboto", "Helvetica", sans-serif;
--font-family: "Gill Sans", "Gill Sans MT", "Calibri", "Trebuchet MS", sans-serif;
```

Geometric headings with warm, readable body fonts for contemporary interfaces.


### 2. Same Font for Both (Sans-Serif with Weight/Size Contrast)

#### A. Arial

```css
--font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
--heading-font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
```

Versatile and available nearly everywhere.


#### B. System UI Stack

```css
--font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
--heading-font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
```

Great for matching native OS styles.


#### C. Neo-Grotesque

```css
--font-family: "Inter", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
--heading-font-family: "Inter", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
```

Clean, neutral, and versatile. Perfect for startups, apps, and professional UIs.


### 3. Serif Headings + Sans-Serif Body

#### A. Georgia (headings) + Inter (body)

```css
--heading-font-family: Georgia, "Times New Roman", Times, serif;
--font-family: "Inter", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
```

Sharp, traditional headings over clean UI body.


#### B. Bookman (headings) + Verdana (body)

```css
--heading-font-family: "Bookman", "URW Bookman", "Georgia", serif;
--font-family: Verdana, Geneva, sans-serif;
```

Vintage serif with highly readable sans.


### 4. Display or Editorial Contrast

#### A. Didot (headings) + Rockwell (body)

```css
--heading-font-family: "Didot", "Bodoni MT", "Didoni", "Modern No. 20", serif;
--font-family: "Rockwell", "Rockwell Nova", "Roboto Slab", "DejaVu Serif", serif;
```

Eye-catching serif headlines with slab serif body for balance.


#### B. Palatino (headings) + Gill Sans (body)

```css
--heading-font-family: "Palatino Linotype", Palatino, serif;
--font-family: "Gill Sans", "Gill Sans MT", Calibri, sans-serif;
```

Elegant and traditional headlines with open, soft sans-serif body.


### 5. Monospace Combinations (Technical)

#### A. Courier New (headings) + Consolas (body)

```css
--heading-font-family: "Courier New", Courier, "Nimbus Mono L", monospace;
--font-family: Consolas, "Lucida Console", Monaco, monospace;
```

Classic mono headers with clear developer-friendly body font.


#### B. JetBrains Mono (headings) + Andale Mono (body)

```css
--heading-font-family: "JetBrains Mono", "Courier New", monospace;
--font-family: "Andale Mono", "Lucida Console", Monaco, monospace;
```

More modern mono headers with familiar, legible mono for content.


### 6. Youthful and Friendly

#### A. Rounded Sans (headings) + Neo-Grotesque (body)

```css
--heading-font-family: "Comfortaa", "Arial Rounded MT Bold", "Quicksand", "Verdana", sans-serif;
--font-family: "Inter", "Helvetica Neue", "Helvetica", "Arial", sans-serif;
```

Rounded headings add a playful, inviting tone — grounded by clean, familiar sans-serif text.


## Acknowledgements

This CSS base/reset file was initially inspired by ideas from Josh W. Comeau's custom CSS reset; I've obviously added a lot more! For more details on his approach, visit [Josh's CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/). I also threw in some of Swyx's [100 Bytes of CSS to look great everywhere](https://www.swyx.io/css-100-bytes) in the html/body tag section (commented out).

## License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for more details.
