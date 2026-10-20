# The Kitchen Buddy

A personal recipe website for finding something to cook. Type in the ingredients you already have and the site shows the recipes you can make, or browse by meal: breakfast, lunch, dinner, dessert and juicing. Each recipe opens in a card with its ingredients, steps, cooking time and nutrition, and you can print it or save it to your favorites.

**Visit the site:** https://www.thekitchenbuddy.com/

The site is plain HTML, CSS and JavaScript with no build step, so it runs on GitHub Pages or any static host.

## Using the site

| Feature | What it does |
| --- | --- |
| **Find by Ingredients** | Enter what's in your kitchen and see the recipes that use it |
| **Browse by Meal** | Tabs for All recipes, Breakfast, Lunch, Dinner, Dessert and Juicing |
| **Search** | The search bar next to the meal tabs finds recipes by name, description or tag as you type |
| **Recipe card** | Ingredients, steps, time and nutrition per serving. Pick how many servings you're making and the ingredient amounts adjust to match. |
| **🖨️ Print** | Prints a clean copy of the recipe without the rest of the page |
| **🤍 Favorites** | Tap the heart on a recipe to save it, then press **Favorites** to see your saved recipes |
| **A A A** | Sets the text size: normal, larger or largest |

Your favorites and text size are saved in your browser, on that device only. A small counter in the corner shows how many times the site has been visited.

## Adding a recipe

All recipes live in `js/recipes.js`. To add one, copy an existing recipe, give it a new unique `id`, and add it to the list. Keep ingredient names lowercase and consistent (for example, always `garlic`, never `Garlic`) so **Find by Ingredients** can match them.

## Files

| File | What it holds |
| --- | --- |
| `index.html` | The page itself |
| `css/styles.css` | Colors, fonts and layout |
| `js/app.js` | Search, meal tabs, favorites, printing and text size |
| `js/recipes.js` | Every recipe on the site |
| `images/` | Recipe photos |
| `CNAME`, `robots.txt`, `sitemap.xml` | The web address and search-engine setup |
| `recipe-docs/` | Original copies of recipes that were added to the site (Word and Outlook files) |

## Hosting

The site is hosted on GitHub Pages at the custom web address in `CNAME` (www.thekitchenbuddy.com). In the repository, Settings → Pages is set to deploy from the `master` branch.

## Roadmap

### Completed

| Step | Task | Status |
| --- | --- | --- |
| 1 | Define scope | ✅ Done |
| 2 | Set up repo structure | ✅ Done |
| 3 | Connect domain + hosting + SSL | ✅ Done |
| 4 | Design main page | ✅ Done |
| 5 | Build main page | ✅ Done |
| 6 | Create recipe data model | ✅ Done |
| 7 | Build search by ingredients | ✅ Done |
| 8 | Build filter by meal type + combined search | ✅ Done |
| 9 | Make it searchable (SEO + site searchability) | ✅ Done |

### Phase two

| Step | Task | Status |
| --- | --- | --- |
| 1 | Build add recipe | ⬜ To do |
| 2 | Test everything | ⬜ To do |
| 3 | Launch + maintain | ⬜ To do |

**Goal:** https://www.thekitchenbuddy.com/
