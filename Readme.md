# Professional Debugging Prompt — KAKA Store Dashboard

Act as a senior frontend developer and debugging expert specializing in HTML5, CSS3, JavaScript, and Visual Studio Code.

I am developing a motorcycle shop management system called **KAKA Store** using HTML, CSS, and JavaScript.

## Project Files

My project contains three files in the same folder:

- `index.html` — website structure
- `style.css` — dashboard styling
- `script.js` — interactive functionality

## Current Problem

My dashboard opens in the browser, but the CSS styling does not appear correctly.

I performed a test by temporarily replacing the contents of `style.css` with:

```css
body {
    background-color:656D3F;
}

h1 {
    color: 492828;
    font-size: 40px;
}
```

The test worked, and the browser displayed the light-blue background. Therefore, the HTML file can successfully load the CSS file.

The problem may be related to the original CSS code, missing or mismatched HTML class names, incomplete code, CSS syntax errors, or incorrect file contents.

## Your Tasks

1. Help me identify the actual cause of the dashboard styling problem.
2. Do not assume the cause without examining the relevant code.
3. Ask me to provide my current `index.html`, `style.css`, and `script.js` files if necessary.
4. Check the HTML structure, stylesheet link, CSS selectors, class names, braces, media queries, and JavaScript errors.
5. Identify any errors and explain why they prevent the dashboard from working correctly.
6. Provide corrected, complete code for each affected file.
7. Ensure all three files work together without requiring unnecessary external libraries.
8. Make the dashboard responsive on desktop, tablet, and mobile screens.
9. Preserve the KAKA Store branding and professional motorcycle shop management design.
10. Ensure the sidebar, summary cards, recent sales table, low-stock alerts, and navigation display correctly.
11. Ensure the JavaScript functionality works without console errors.
12. Give me step-by-step instructions for applying the fixes in Visual Studio Code.

## Design Requirements

Use a professional navy-blue and white color scheme, clean typography, consistent spacing, attractive dashboard cards, readable tables, and responsive layouts.

The dashboard should be suitable for a real motorcycle spare parts business in Uganda, with prices displayed in Ugandan Shillings (UGX).

## Important Instructions

I have some knowledge of HTML and CSS, so explain technical concepts clearly without overwhelming me.

Do not rebuild the entire project unnecessarily. First diagnose the existing problem, then fix it.

Do not give me incomplete code or vague instructions. Tell me exactly which file to open, what code to replace, where to paste the corrected code, and how to test the result.

Once the dashboard works correctly, help me continue development step by step, starting with inventory management, product registration, stock quantities, selling prices, search, and browser-based data storage.

**Begin by asking me to share the current code or upload the three project files so you can inspect them and identify the real problem.**
