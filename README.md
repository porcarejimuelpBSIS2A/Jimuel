# GAMEVERSE — Gaming Showcase Website

**Developer:** Jimuel P. Porcare  
**Activity:** Activity 01 — ALL OR NOTHING  
**Technology:** HTML5 and CSS3 only

GAMEVERSE is an original, responsive gaming showcase website featuring a futuristic neon design. It introduces the website, shares information about its creator, and displays three fictional game concepts: Cyber Rift, Star Odyssey, and Shadow Arena.

## Project features

- Three connected pages: Home, About, and Game Gallery
- Responsive layout for desktop, tablet, and mobile
- CSS hover effects, gradients, and a subtle floating hero illustration
- Accessible navigation labels and descriptive image alternative text
- Locally stored SVG illustrations in the `images` folder
- No JavaScript, JavaScript libraries, or frameworks

## Folder structure

```text
gameverse/
├── index.html
├── about.html
├── gallery.html
├── css/
│   └── style.css
├── images/
│   ├── hero-controller.svg
│   ├── cyber-rift.svg
│   ├── star-odyssey.svg
│   └── shadow-arena.svg
└── README.md
```

## How to run locally

1. Download or clone this repository.
2. Keep the folder structure unchanged.
3. Open `index.html` in a modern web browser.
4. Use the navigation links to visit the About and Game Gallery pages.

An internet connection is needed to load the optional Google Fonts. The website layout and local SVG illustrations still work without those fonts.

## Image guidance

The `images` folder contains original SVG illustrations made for this project. They are already connected to the HTML pages, so no extra image downloads are required. If you want to replace an illustration, use your own gaming artwork and keep the same filename, or update the matching `src` path in the HTML file. Use images you created or have permission to use.

## Publish with GitHub Pages

1. Sign in to [GitHub](https://github.com/).
2. Create a new repository named `gameverse` (or another name your instructor approves).
3. Set the repository visibility to **Public**.
4. Upload the contents of this project folder. Make sure `index.html` is at the repository root, not inside another nested folder.
5. Open the repository's **Settings** tab.
6. Select **Pages** from the left sidebar.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch `main` and folder `/ (root)`, then click **Save**.
9. Wait for GitHub Pages to finish publishing. Refresh the Pages settings if the link does not appear immediately.
10. Open the published URL and test all three navigation pages and images.

Your website address will usually look like:

`https://github.com/porcarejimuelpBSIS2A/Jimuel.git`

Replace `YOUR-GITHUB-USERNAME` with your GitHub username. If you used a different repository name, replace `gameverse` with that name.

## Before submitting

- [ ] Repository is Public.
- [ ] `index.html`, `about.html`, and `gallery.html` are in the repository root.
- [ ] `css/style.css` and all four SVG files are uploaded.
- [ ] All navigation links work.
- [ ] Website displays correctly on a phone-sized screen.
- [ ] Live GitHub Pages link opens successfully.
- [ ] No JavaScript has been added.

## Academic note

This project was created for an HTML5 and CSS3 activity. All interactive navigation is implemented with regular links and CSS. No JavaScript is included.
