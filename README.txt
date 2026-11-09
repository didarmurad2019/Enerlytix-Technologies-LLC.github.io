Enerlytix By-Laws Portal — deployment notes

Files:
- bylaws-portal.html: standalone portal page intended for the website root.
- assets/data/bylaws-users.json: requested separate JSON account list.
- homepage-navigation-snippet.html: optional link to add to the existing site's navigation.

Important security note:
This is a static HTML/JavaScript demonstration. The JSON file is publicly downloadable from GitHub Pages, and passwords in it can be inspected. The login gate only controls the page's presentation; it does NOT securely protect the By-Laws page or its URL. Do not use real credentials or treat this as access control. For real restriction, use a server-side authentication service and protect the document itself.

Replace the placeholder account fields in assets/data/bylaws-users.json. Test via the published site (or a local web server); opening the HTML directly with file:// may prevent fetch from loading the JSON.
