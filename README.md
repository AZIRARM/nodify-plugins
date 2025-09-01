# Nodify Headless CMS - Plugins Overview

This document presents an overview of the available plugins for **Nodify Headless CMS** and guidance on how to create and develop your own plugins.

---

## Available Plugins

- **jquery3.7.1**  
  Plugin integrating **jQuery 3.7.1** for enhanced DOM manipulation and event handling.  
  [Doc](jquery/README.md)

- **feedbacks**  
  Nodify plugin designed to manage user **feedbacks**, handling only HTML/JS content.  
  [Doc](feedbacks/README.md)

- **bootstrap5.0.2**  
  Plugin providing **Bootstrap 5.0.2** framework integration for responsive UI components and styling.  
  [Doc](bootstrap/README.md)

- **comments**  
  Nodify plugin to enable **content comments**, supporting only HTML/JS content.  
  [Doc](comments/README.md)

- **clicks**  
  Plugin that tracks **content clicks** within Nodify, handling only HTML/JS content.  
  [Doc](clicks/README.md)

- **epubjs**  
  Plugin integrating **epub.js** to enable rendering and navigation of **EPUB ebooks** directly within Nodify.  
  [Doc](epubjs/README.md)

---

## Creating Plugins in Nodify Studio

Plugins are created within the **Nodify Studio** under the **Plugins** menu. By default, Nodify generates a simple base code for each new plugin which you will need to modify according to your requirements.

### Key points for plugin creation:
- You can add **assets** such as images, scripts, stylesheets, or other resource files required by your plugin.
- It is **highly recommended** to include a **README file** inside the assets folder of your plugin to explain how to use and configure it.
- Information about each available plugin can be found in its respective plugin folder inside the Nodify project directory.

---

## How to Develop a Plugin

1. **Start in Nodify Studio:**  
   Use the built-in plugin creation wizard from the Plugins menu to generate the plugin skeleton.

2. **Modify the base code:**  
   The generated code is a minimal working example. Customize it by adding your logic, UI elements, and interactions.

3. **Add assets:**  
   Include any necessary files like CSS, JS, images inside the `assets` folder of your plugin directory.

4. **Document your plugin:**  
   Write clear instructions, usage examples, and configuration options in a README file inside the assets folder. This helps users understand and properly use your plugin.

5. **Test your plugin:**  
   Ensure your plugin works correctly within the Nodify environment and does not conflict with other plugins.

---

For any questions or contributions, please refer to the plugin folders or contact the Nodify development team.

---
