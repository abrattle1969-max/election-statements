# Two candidate statement websites

Each site displays the statement pages unchanged in order and offers the byte-for-byte original PDF. Page images use lossless WebP; visitors can open the PDF for full-resolution viewing. No analytics, accounts or cookies are added. Search indexing is discouraged, but the sites are public, not access-controlled.

## Deploy on Render

1. Upload the contents of this directory to the root of a GitHub repository. Preserve both candidate folders. A private repository can keep the source private; deployed sites remain public.
2. Sign in to https://dashboard.render.com and select New > Blueprint.
3. Connect that repository and use render.yaml. Review the two static sites and deploy.
4. Render assigns a separate HTTPS onrender.com address to each site. Copy the actual URLs from the dashboard; names in this file are requested service names, not reserved URLs.
5. Check every page and both PDF links on each live site, including on a phone.

Alternatively create two Static Sites from the same repository. Build command: echo "Static files ready". Publish directory: rhys-harmer for one; glen-hart for the other. Leave root directory unset.

## End of the hosting period

No shutdown date has been set. These sites stay online until removed in Render. At the agreed end date, remove both static-site services through the Render dashboard. Merely removing them from render.yaml does not necessarily delete existing services. Removing a page in browser JavaScript would not prevent direct access to its PDF.

## Original document verification

checksums.json records SHA-256 hashes of the original PDFs. Both copies have been checked byte-for-byte against the supplied files. Rhys: 4 pages. Glen: 2 pages.

## Accessibility

Images preserve the original design but do not provide a full text alternative. PDF links are available, but accessibility depends on the supplied PDFs; Glen's original is not tagged. A fully accessible HTML transcription would be an additional deliverable.

Documentation: https://render.com/docs/static-sites and https://render.com/docs/blueprint-spec
