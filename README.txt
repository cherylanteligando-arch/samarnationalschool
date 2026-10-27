SAMARIÑAN WEBSITE DEMO

Open index.html in a modern browser. Internet is needed to load the Poppins font; the site otherwise uses local HTML/CSS/JavaScript and supplied image assets.

Features:
- Responsive Home, Feature Stories, Editorial Cartooning, and About pages
- Article detail dialog with author, date, story, and caption
- Demo admin CMS to add, edit, and delete features and cartoons
- Data persists in localStorage in the current browser
- PWA manifest included

Important limitations:
- This is a front-end demo. The admin CMS is not protected by login and localStorage is not shared between devices or users.
- Do not put confidential information in it or use it as a production CMS without adding secure authentication, server-side storage, backups, and editorial permissions.
- Replace placeholder articles and image references with verified content and approved photos before publishing.

To use the demo: unzip the folder and open index.html. For PWA/service-worker installation or production hosting, serve the folder over HTTPS and add a service worker plus a secure backend/CMS.
