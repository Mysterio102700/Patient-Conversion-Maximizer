# Patient Conversion Maximizer Demo - Implementation Guide

This guide provides instructions for embedding the Patient Conversion Maximizer interactive demo on your Webflow or WordPress website.

## Overview

The Patient Conversion Maximizer demo is a lightweight, interactive widget that allows prospects to experience your AI phone, SMS, and chat automations firsthand. The demo is designed to be:

- Lightweight (< 100KB total)
- Fast-loading (LCP < 2.5s)
- WCAG AA accessible
- Compatible with all modern browsers
- Mobile-responsive
- Easy to implement

## Quick Start

1. Upload the `pcm-widget.min.js` file to your website
2. Add the following code snippet to your page, just before the closing `</body>` tag:

```html
<script src="path/to/pcm-widget.min.js"></script>
```

That's it! The demo widget will appear as a floating button in the bottom-right corner of your page.

## Detailed Implementation Instructions

### For Webflow

1. **Upload the JavaScript file:**
   - Go to your Webflow project dashboard
   - Navigate to "Assets" in the left sidebar
   - Click "Upload" and select the `pcm-widget.min.js` file
   - Copy the generated URL for the uploaded file

2. **Add the script to your site:**
   - In your Webflow project, go to "Pages" in the left sidebar
   - Select the page where you want to add the demo
   - Click on the settings icon (gear) in the top-right corner
   - Select "Custom Code" tab
   - In the "Footer Code" section, add:
   ```html
   <script src="YOUR_UPLOADED_FILE_URL"></script>
   ```
   - Replace `YOUR_UPLOADED_FILE_URL` with the URL copied in step 1
   - Click "Save" and publish your site

3. **Optional: Trigger the demo programmatically:**
   - To open the demo when a specific button is clicked, add this code to your button:
   ```html
   <script>
     document.getElementById('your-button-id').addEventListener('click', function() {
       window.PatientConversionDemo.open();
     });
   </script>
   ```

### For WordPress

1. **Upload the JavaScript file:**
   - Log in to your WordPress admin dashboard
   - Go to "Media" > "Add New"
   - Upload the `pcm-widget.min.js` file
   - Copy the file URL from the attachment details

2. **Add the script to your site:**
   - Option A: Using a plugin
     - Install and activate the "Header and Footer Scripts" plugin
     - Go to "Settings" > "Header and Footer Scripts"
     - Add the following code to the "Scripts in Footer" section:
     ```html
     <script src="YOUR_UPLOADED_FILE_URL"></script>
     ```
     - Replace `YOUR_UPLOADED_FILE_URL` with the URL copied in step 1
     - Click "Save"

   - Option B: Editing your theme
     - Go to "Appearance" > "Theme Editor"
     - Select your theme's "footer.php" file
     - Add the following code just before the closing `</body>` tag:
     ```html
     <script src="YOUR_UPLOADED_FILE_URL"></script>
     ```
     - Replace `YOUR_UPLOADED_FILE_URL` with the URL copied in step 1
     - Click "Update File"

3. **Optional: Trigger the demo programmatically:**
   - To open the demo when a specific button is clicked, add this code to your page using a Custom HTML block:
   ```html
   <script>
     document.getElementById('your-button-id').addEventListener('click', function() {
       window.PatientConversionDemo.open();
     });
   </script>
   ```

## Customization Options

### Changing the Calendly Link

By default, the "Book a Call" button opens a placeholder Calendly link. To use your actual Calendly link:

1. Open the `pcm-widget.min.js` file in a text editor
2. Find all instances of `https://calendly.com/orangecarrot`
3. Replace them with your actual Calendly URL
4. Save the file and re-upload it to your site

### Changing Colors and Styling

The demo uses CSS variables for consistent styling. To match your brand colors:

1. Add the following CSS to your website's custom CSS:

```css
:root {
  --primary: #YOUR_BRAND_COLOR; /* Replace with your primary color */
  --primary-dark: #YOUR_DARKER_SHADE; /* Replace with a darker shade of your primary color */
  --primary-light: #YOUR_LIGHTER_SHADE; /* Replace with a lighter shade of your primary color */
}
```

## Troubleshooting

### The widget doesn't appear

- Verify that the script is properly loaded by checking your browser's developer console
- Ensure there are no JavaScript errors on your page
- Check if another plugin or script is conflicting with the demo

### The demo looks different on mobile

- The demo is designed to be responsive and will adapt to different screen sizes
- On very small screens, it will switch to a simplified layout
- Ensure your website's viewport meta tag is properly set:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Performance issues

- If the demo affects your page performance, ensure it's loaded after your page content
- Consider loading the script with the `defer` attribute:
```html
<script src="path/to/pcm-widget.min.js" defer></script>
```

## Technical Support

For technical assistance with implementing the Patient Conversion Maximizer demo, please contact our support team at support@orangecarrotmedia.com.
