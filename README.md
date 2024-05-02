# Applying a Theme in Salesforce FormAssembly

## Overview
Themes in Salesforce FormAssembly allow you to customize the appearance of your forms. You can define colors, fonts, and other visual elements to match your brand or design preferences. Let's walk through the steps to apply a theme.

## Prerequisites
Before you begin, make sure you have:
- A FormAssembly account
- Access to the Form Builder

## Steps

1. **Log in to FormAssembly:**
   First, log in to your FormAssembly account.

2. **Navigate to the Form Builder:**
   Once logged in, go to the Form Builder section.

3. **Access the Theme Editor:**
   - Click the "Themes" button from the top Form Builder menu.
   - In the Themes menu, you'll find private and public themes, as well as existing themes available for customization.

4. **Sourcewell Base Theme:**
   - Browse through the available themes.
   - Expand the "Private Themes" section.
   - Find the "Sourcewell (Light)" theme.
   - You can apply an existing theme directly to your form or customize it further.

5. **Applying an Existing Theme:**
   - If you want to use an existing theme as-is, simply click the theme you like.
   - The theme will be immediately applied in the form builder.

6. **Customizing a Theme:**
   - To customize an existing theme:
     - Click the theme you want to modify.
     - Edit options such as background color, primary color, font size, etc.
     - Save the theme by clicking the "Save" button at the top-right corner of the theme menu.
     - Optionally, rename the theme by clicking the pencil icon next to the theme name.

7. **Creating Your Own Theme (Admins Only):**
   - Steps listed below.

8. **Review and Test:**
   - After applying or customizing a theme, review your form to ensure it aligns with your desired look and feel.
   - Test the form to verify that the theme works as expected.

# Creating a Theme in Salesforce FormAssembly

## Steps

1. **Log in to FormAssembly:**
   First, log in to your FormAssembly account.

2. **Navigate to the Form Builder:**
   Once logged in, go to the Form Builder section.

3. **Click on the "Theme" Option:**
   In the Form Builder menu, click on the "Theme" option. This will take you to the theme editor.

4. **Create a New Theme:**
   Click the "Create New Theme" button. Give your theme a name (e.g., "Custom Theme").

5. **Customize Your Theme:**
   - **SCSS Variables:** In the theme editor, you'll find a section called "Custom CSS." Here, you can add SCSS (Sass) variables to define various style elements.
   - **Exposed Variables:** Decide which SCSS variables you want to expose to users who will customize the theme. These variables will be available for customization.
   - **Valid SCSS Variable Syntax:**
     - Start with a "$" followed by a valid CSS identifier.
     - Include a valid "type" prefix (e.g., $text-abcdef for a text variable).
     - Define a label (e.g., $text-input-font for the input font).

6. **Types of SCSS Variables:**
   You can use different types of SCSS variables:
   - **text**: For text-related styles.
   - **length**: Numeric values with size units (e.g., "px," "em").
   - **color**: 6-digit hex format for colors.
   - **number**: Plain numeric values.
   - **range**: Numeric values between 0 and 1 (used for sliders).
   - **image**: Background images.
   - **font**: Google Font names.

7. **Save Your Theme:**
   Once you've defined your SCSS variables, save your theme. Valid definitions will immediately appear as theme options.

8. **Additional Notes:**
   - Use valid CSS code augmented with SCSS variable syntax.
   - Syntax errors will prevent the theme from being saved.


8. **Review and Test:**
   - After applying or customizing a theme, review your form to ensure it aligns with your desired look and feel.
   - Test the form to verify that the theme works as expected.
