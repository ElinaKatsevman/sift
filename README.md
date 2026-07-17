# Sift

Sift is a client-side web application designed to rescue home cooks and bakers from the clutter of modern recipe websites by extracting clean ingredients and step-by-step instructions.

### What it does

* **Recipe Extraction:** Instantly pulls structured recipe data from URLs or raw HTML/text.
* **Interactive Recipe Card:** Features a clean layout with an ingredients checklist and highlightable instructions.
* **Dynamic Scaling \& Conversion:** Easily scale serving sizes and convert between metric and imperial units.
* **My Cookbook:** Saves your extracted recipes locally in your browser for easy access.
* **Customization \& Export:** Allows you to edit recipes, add personal notes, and export them as formatted Markdown files.

### Live link

https://elinakatsevman.github.io/sift/

### How to use it

1. Open the live link and paste a recipe URL (or raw webpage HTML/ raw website schema) into the extraction bar.
2. Click "Sift" to extract the recipe to view the clean, ad-free ingredients and instructions.
3. Cook from the interactive interface, adjust servings, write notes or save the recipe to your personal digital cookbook!

### Known limitations

Only works for modern recipe blogs that use standard schema metadata (JSON-LD/Microdata). Occasional extraction failures may occur if a website heavily blocks CORS proxies, in which case you must manually paste the raw HTML to extract the recipe. Doesn't work for every website, therefore you can paste HTML/ raw website schema. Sometimes makes mistakes, therefore you can edit each text box!

