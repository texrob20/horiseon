# Code Refactor Horiseon Webpage
Changes to index.html on 10/28:
- Added appropriate title "Horiseon Social Solution Services"
- Replaced <div> with <header> element for header
- Replaced <div> with <nav> element for header list
- Added alt text for "Content" section pictures
- Replaced <div> with <footer> element for footer

Changes to style.css on 10/28:
- Header class removed and replaced with <header> element styling
- Updated header <div> to <nav> to support changes to index file
- Footer class removed and replaced with <footer> element styling

Hero and Content Styling
- Updated top-level from <div> to <section> to improve logical structure
- Consolidated base styling, img, h2 into content class
- Added "content-block" class to consolidate search-engine-optimization, online-reputation-management, and social-medial-marketing class styling
- Romoved search-engine-optimization, online-reputation-management, and social-medial-marketing class styling


Benefits Styling
- Updated top-level from <div> to <section> to improve logical structure
- Consolidated all styling for benefits class into a single class reducing redundant styling
- Removed benefits-lead, benefits-brand, and benefits-cost classes
- Added styling for "p" to benefits class
