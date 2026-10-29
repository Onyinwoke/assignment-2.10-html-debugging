# Assignment 2.10 – Problem and Fix Table

| No. | Problem identified | Location in `broken.html` | Correction in `fixed.html` | Why the correction matters |
|---|---|---|---|---|
| 1 | Missing document language | Opening `<html>` tag | Added `lang="en"` | Helps browsers and assistive technologies identify the page language. |
| 2 | Missing document title | Inside the `<head>` element | Added `<title>My Learning Website</title>` | Gives the page a meaningful browser-tab title and improves accessibility. |
| 3 | Missing closing paragraph tags | Welcome and introductory paragraphs | Closed each `<p>` element properly | Ensures the browser interprets the document structure correctly. |
| 4 | Incorrect element nesting | Paragraph and `<div>` elements near the middle of the page | Corrected the nesting and closed elements in the proper order | Prevents unexpected HTML structure and rendering problems. |
| 5 | Duplicate IDs | The two headings using `id="section"` | Replaced them with unique IDs such as `about` and `projects` | IDs should be unique so links and scripts can identify the correct element. |
| 6 | Missing image alternative text | Profile image `<img>` element | Added descriptive `alt` text | Makes meaningful image content accessible to people using screen readers. |
| 7 | Broken relative links | Links to `pages/about.html` and `projects/project.html` | Changed them to valid in-page links, `#about` and `#projects` | Ensures the links point to sections that exist in the corrected document. |
| 8 | Incorrect form-label associations | Full Name and Email Address labels | Updated each label's `for` attribute to match its input's `id` | Allows assistive technologies to associate each label with the correct form control. |
| 9 | Incorrect heading hierarchy | Main heading and Background heading | Changed the main heading to `<h1>` and Background to `<h3>` under the `<h2>` section | Creates a logical heading structure for readers and assistive technologies. |

## Validation Summary

- The original `broken.html` file was inspected manually and checked using the W3C Nu HTML Checker.
- The initial validation identified HTML errors and warnings.
- The corrections were made in a separate file named `fixed.html`.
- The corrected file was validated again using the W3C Nu HTML Checker.
- The final validation reported **zero errors**.

## Evidence

- `evidence/broken-validation 1.png` – Initial validation screenshot.
- `evidence/broken-validation 2.png` – Additional initial validation screenshot.
- `evidence/fixed-validation.png` – Final successful validation screenshot.

