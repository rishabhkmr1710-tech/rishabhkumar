# Rishabh Pandey — Portfolio

A 7-page static site (no build step, no frameworks) covering:
`Home · Resume · Projects · Internship · Certifications · Case Competitions · Insights`

## File map
```
index.html              Home
resume.html
projects.html
internship.html
certifications.html
case-competitions.html
insights.html
css/style.css           all styling
js/script.js            mobile nav toggle
assets/                 put your resume PDF, report PDF, etc. here
```

## 1. Put it on GitHub (free hosting)
1. Create a new repository on GitHub named exactly `<your-username>.github.io`
   (e.g. `devivishwakumar.github.io` — or any name if you're okay with a
   `/reponame/` in the URL).
2. Upload all the files in this folder to that repository (drag-and-drop
   on github.com works fine, or use `git push` if you're comfortable with it).
3. Go to the repo's **Settings → Pages**, set the source branch to `main`
   and folder to `/root`, then save.
4. Your site goes live at `https://<your-username>.github.io` within a
   couple of minutes.

## 2. Edit content
Every page has one or more boxes marked:
```
[EDIT ME] ...
```
Open the `.html` file in any text editor (or directly on GitHub using the
pencil icon), replace the bracketed placeholder text with your real content,
and save — GitHub Pages redeploys automatically.

To add your resume PDF: drop the file into `assets/`, then update the link
in `resume.html` (search for `Rishabh_Pandey_Resume.pdf`) to match your
actual filename.

## 3. Connect a custom domain (optional, Step 2 from the slide)
1. Buy a domain (Google Domains successor / Namecheap / GoDaddy).
2. In the repo, add a file named `CNAME` containing just your domain, e.g.:
   ```
   yourname.com
   ```
3. At your domain registrar, add a CNAME record pointing to
   `<your-username>.github.io`.
4. In **Settings → Pages**, enter the custom domain and enable HTTPS once
   it's verified.

## Design notes
The visual language borrows from an equity-research report — navy masthead,
paper background, a green "up" accent, and a sparkline motif — since that's
the field you're aiming for. Feel free to swap the palette in
`css/style.css` (the `:root` block at the top) if you want a different look.
