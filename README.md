# Missing alt attribute in img tag

This repository demonstrates a common HTML error: forgetting or leaving the `alt` attribute empty in the `<img>` tag.  The `alt` attribute is essential for accessibility and SEO.  It provides alternative text for screen readers and search engines.

The `bug.html` file shows the incorrect code. The `solution.html` file provides the corrected version.

## How to Reproduce the Bug

1. Open `bug.html` in a web browser.
2. Inspect the image with your browser's developer tools.  Note the missing `alt` attribute.
3. Use a screen reader to see how the image is described (or rather, how it's *not* described).

## Solution

The solution is to include a meaningful `alt` attribute in the `<img>` tag, describing the image concisely.  See `solution.html` for an example.