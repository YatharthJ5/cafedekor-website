# CafeDekor website concept
Static site, no build step or dependencies. Run: `python3 -m http.server 8000` then open http://localhost:8000
(Videos need a server; opening index.html by double-click may block them.)
## Configure
- `index.html` > `FORM_ENDPOINT`: set a Formspree (or similar) URL. Until set, the form shows an honest "not connected" message.
- Footer: add verified email/phone links (see CONFIG comment). Add `sitemap.xml` with the live domain.
## Assets
`assets/`: hero.mp4 (compressed hero), film1/2.mp4 (project films), p1-p4.jpg (supplied photos, top watermark cropped), bean.png (logo mark extracted from supplied logo).
Copy: services are proposed categories; project titles are neutral labels. Replace when real details are supplied.
Routes are hash-based (#/projects, #/project/1, ...). Unknown routes show the 404 view.
