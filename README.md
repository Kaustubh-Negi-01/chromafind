# ChromaFind

ChromaFind is a modern image-search application designed to let users explore the world in vibrant color. In its final form, it will fetch and display images in a responsive grid based on user search queries, leveraging an external API.

## Project Scope
This project is being built over multiple parts. Part 1 focuses entirely on the UI scaffold, establishing the structural HTML, semantic tags, accessible forms, and the core responsive CSS Grid layout that will hold our images.

## Design Decisions

1. **Teal & Slate Color Palette:** 
   I chose a teal (`#0d9488`) primary color combined with a slate grey text scheme (`#0f172a` and `#64748b`) and a clean off-white background (`#f8fafc`). This decision was made to give the app a fresh, modern, and trustworthy aesthetic that feels reminiscent of high-end photography portfolios. It differs distinctly from the reference's purple theme, ensuring the app has its own unique brand identity.

2. **Category Chips (Quick Picks):** 
   I included a quick-pick category row just below the search bar (featuring tags like Nature, Abstract, Architecture, and Minimal). This decision improves user experience (UX) by allowing users to execute common searches with a single click, immediately showcasing the app's capabilities without requiring them to type out a query.

3. **Visual Empty State:** 
   I implemented a dedicated visual empty state ("Search to see results") with an accompanying minimalist SVG magnifying glass icon. Rather than presenting users with a confusing blank page when they first land on the app or clear their search, this design decision naturally guides the user's attention back to the search bar and sets clear expectations about how to interact with the interface.

4. **Responsive CSS Grid Layout:** 
   The results container utilizes CSS Grid with `repeat(auto-fill, minmax(280px, 1fr))`. I chose a `280px` minimum card width because it allows for comfortable, large image viewing on desktop screens while gracefully reflowing to a single column on most mobile devices, ensuring a seamless experience across all viewport sizes.
