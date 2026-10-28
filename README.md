# Healthy Homes Navigator

A responsive research prototype for New Zealand tenants to explore housing concerns, organise fictional evidence, prepare an editable maintenance request, find support and make a personal action plan.

## Included

- Visual concern selector with clearly labelled AI-generated sample pictures.
- Browser-only photo preview and guided questions. **No automatic AI image analysis.**
- Simplified personal observation checklist, notes, custom items and text download, with a link to the official Tenancy Services checklist.
- Fictional evidence workspace, maintenance-request draft, sharing preview, action plan and simulated progress tracker.
- Links to official information, advocacy and practical Healthy Homes support.

Use fictional information during testing. This tool does not determine legal compliance, send requests, provide secure evidence storage or schedule notifications. Photos are held in page memory only. Demo text and checklist answers use session storage in the current browser tab. Downloads and copied text remain where the user saves them.

## Publish through GitHub (no coding required)

1. Extract the ZIP on your computer.
2. Sign in at https://github.com and create a repository named `healthy-homes-navigator`. Choose Public if using GitHub Free and wanting GitHub Pages. A public repository makes its code and included files visible to everyone.
3. Open the repository, choose **Add file > Upload files** (or the upload link on a new repository).
4. Upload the extracted contents: `index.html`, `style.css`, `app.js`, `assets/`, this README, and `.nojekyll` if visible. Upload the contents, not the ZIP or the outer containing folder. Keep `assets/housing-examples.png` inside `assets/`.
5. Commit the uploaded files to `main`. If GitHub instead opens a pull request, merge it into `main`.
6. Go to **Settings > Pages**. Set Source to **Deploy from a branch**, Branch to **main**, and Folder to **/(root)**. Save.
7. When publishing finishes, open the website address GitHub displays on the Pages settings screen.

GitHub Pages hosts this static prototype. The current site hosted through ChatGPT remains a separate copy; updates to one do not automatically update the other.

## Work with Dylan

Share the repository link for code review. Repository Settings provides collaborator access if you decide to invite him. A repository link shows the files; the Pages link opens the working website. No invitation has been sent with this package.

## Edit and preview

`index.html` contains the page shell, `style.css` contains styling, and `app.js` contains the prototype content and browser interactions. `assets/housing-examples.png` is an AI-generated photographic contact sheet displayed as cropped tiles with CSS.

No dependencies or build step are required. With Python installed, run `python -m http.server 8000` in this directory and open http://localhost:8000. Stop with Ctrl+C.

Future AI analysis requires a secure backend and separately configured API access. Never put an API key in browser JavaScript or a public repository.

## References

- Create a Pages site: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- Upload files: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
- Configure Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Prepared 28 October 2026 from the current working prototype. No account credentials, hosting identifiers, research participant data or demo session data are included.
