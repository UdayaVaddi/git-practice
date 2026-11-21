# UDAYA SRI SATYA SAI VADDI — Portfolio

A responsive portfolio for a Machine Learning Engineer focused on Applied AI, predictive systems, MLOps, and business-driven solutions. Built with plain HTML, CSS, and JavaScript; no build step or dependencies are required.

## Preview locally

From this folder, start a local web server:

```sh
python3 -m http.server 8000
```

Open <http://127.0.0.1:8000/> in a browser. Stop the server with **Control+C** in its terminal.

## Site sections

- Full-name introduction centered on transferable machine-learning and business problem-solving capabilities.
- Technical expertise across model development, deep learning, MLOps, data engineering, cloud, and analytics.
- Filterable projects, anonymized project-based delivery approach, and external company projects.
- Research papers and conference presentations, patent/design work, a copyright project, and book authorship.
- Education, certifications, GitHub, LinkedIn, and Medium.

The site does not include a résumé download or employer-branded professional-history section. Professional work is represented by project descriptions. The separate external-project section remains labeled by organization.

## Review before publishing

- The UK IP document confirms Registered Design No. 6552358, registered 10 September 2026; it protects the device's appearance and is described as a design, not a patent.
- The U.S. non-provisional specification supplied here has no public application number or grant record in the document. The site describes the specification without calling it a granted patent.
- No Canadian copyright registration details, IEEE DOI/proceedings links, or conference URLs were included in the supplied materials. Add public identifiers when available.
- Patent, research, and book source documents are not bundled as public downloads. Their project descriptions are on the site.
- The Brain Stroke report remains outside this repository because it contains another person's local Windows account name.
- The AWS certification is listed using the name supplied by Udaya.

The separate working file `portfolio-source-notes.md` is in the parent Documents folder, outside this repository. Do not copy it into the public repository.

## Publish with GitHub Pages

This repository is connected to `https://github.com/UdayaVaddi/git-practice.git`.

1. Review the portfolio in a browser and check all titles, status labels, contact details, and profile links.
2. Commit the site and its assets to `main`:

   ```sh
   git add index.html README.md assets
   git commit -m "Remove résumé file and anonymize professional work"
   git push origin main
   ```

3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then click **Save**.
5. After deployment, GitHub shows the site URL in **Settings → Pages**. For this repository it will usually be <https://udayavaddi.github.io/git-practice/>.
