# Fixing 404 Not found Docsify on GitHub Pages

If you're using Docsify to host your static website on GitHub Pages, you might have encountered a frustrating issue: navigating directly to a specific page results in a "404 Page Not Found" error. This is because Docsify relies on the HTML5 History API for routing, which Github Pages doesn't handle by default without additional configuration.

## Problem

When you visit your site at `phuongvo9.github.io`, everything works fine. However, if you try to go directly to a subpage like `phuongvo9.github.io/guide`, you get a 404 error. This is because GitHub Pages doesn't know how to handle the SPA routing and looks for a physical file at that path, which doesn't exist.

### The Solution

To fix this, we need to create a custom `404.html` page that redirects all requests back to `index.html`, allowing Docsify to handle the routing. Here's how you can do it:

1. **Create a `404.html` file** in the root of your repository with the following content:

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Page Not Found</title>
  <meta http-equiv="refresh" content="0; URL=./index.html">
  <script type="text/javascript">
    // Redirect to the index.html with the correct path
    var path = window.location.pathname;
    window.location.replace('/index.html?' + path);
  </script>
</head>
<body>
  <p>Page not found. Redirecting...</p>
</body>
</html>
```

2. **Commit and push the `404.html` file** to your GitHub repository.

3. Make sure your relativePath configuration in `window.$docsify` is set to `true`.
Refer to the official Docsify documentation for more details: https://github.com/docsifyjs/docsify/blob/develop/docs/configuration.md

### How It Works

- The `404.html` file catches all 404 errors.
- It then redirects the user to `index.html`, appending the original path as a query parameter.
- Docsify reads this parameter and navigates to the correct page.

### Let me know

By adding this `404.html` file, you ensure that all routes are correctly handled by Docsify, even when users navigate directly to a subpage
Please create a Pull request and let me know if this can not solve the issue you had or you find another solution 

---
