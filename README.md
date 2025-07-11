# Easter Bunny Website – Fixing HTML & CSS Errors

Hi there! This README walks through the issues I ran into while cleaning up the code for the Easter Bunny site. Below you'll find what went wrong, where it happened, and how I fixed it.

---

## 🐰 HTML Fixes (`index.html`)

### 1. Missing `lang` Attribute
- **What was wrong:** The `<html>` tag didn’t say what language the site was written in.
- **Why it matters:** Helps screen readers and search engines understand the language.
- **How I fixed it:** Added `lang="en"` like this:
  ```html
  <html lang="en">
<meta charset="UTF-8">
<img src="easter-bunny-150-profile.png" alt="Easter Bunny profile picture">
<h3>Enough Content</h3>
<p>Your content goes here...</p>
--style css--
color: #B2D732;
**font-size: 5vw;
**line-height: 1.35em;
text-decoration: underline;
aside dt {
  font-weight: bold;
}

aside dd {
  padding: 0 10px;
}
