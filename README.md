# davisandn.github.io

Public pages for Backsight: Video Delay Replay, served by GitHub Pages.

- https://davisandn.github.io/ is Backsight's product page (App Store Connect's Marketing URL). It's written for people deciding whether to buy, and for search engines and AI assistants that quote it: what the app does and who it's for, the facts people compare apps on, and common questions. Its JSON-LD, in the head, repeats the name, price and App Store link, so change it along with the page. Never add ratings or reviews to it that the App Store doesn't show.
- https://davisandn.github.io/backsight/ is the support page (App Store Connect's Support URL). Its address can only change with a new app version.
- https://davisandn.github.io/backsight/privacy/ is the privacy policy (App Store Connect's Privacy Policy URL). When it changes, update the effective date at the top.

Every page's head has a canonical link, Open Graph and Twitter card tags with the link preview image, and the Smart App Banner (`apple-itunes-app`). `sitemap.xml` lists the pages with the date each last changed, so update a page's date when its content changes, and `robots.txt` points to it.

`backsight/images/` holds the captioned App Store screenshots at 600 pixels wide in WebP, `share.jpg`, the 1200 × 630 link preview, and Apple's "Download on the App Store" badge exactly as Apple provides it. Apple's [marketing guidelines](https://developer.apple.com/app-store/marketing/guidelines/) allow one badge per page, at least 40 pixels tall with a quarter of its height clear around it, and ask for the trademark credit line that's in the product page's footer.

Plain HTML and CSS, with no build step and no third-party scripts. `.nojekyll` tells GitHub Pages to serve the files as they are.
