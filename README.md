[README.md](https://github.com/user-attachments/files/30171651/README.md)
# AGORA — Interface Concept

A static, single-page mockup of the AGORA news app interface: a personalized
mobile feed and a web story-detail view with a branching narrative timeline.
Built for investor presentation purposes. No build step, no dependencies
beyond Google Fonts — it's a single `index.html` file.

## Publish this with GitHub Pages

1. Create a new repository on GitHub (or use an existing one).
2. Upload `index.html` to the root of the repository (drag-and-drop on the
   GitHub web UI works fine, or `git add` / `git commit` / `git push`).
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` (or `master`) and folder `/ (root)`, then
   **Save**.
6. Wait a minute or two, then refresh that Pages settings screen — GitHub
   will show your live URL, typically:

   ```
   https://<your-username>.github.io/<repository-name>/
   ```

That's it — no other configuration is needed since the page is a single
self-contained HTML file.

## Notes

- All story content shown is hypothetical, for demonstration purposes only.
- Fonts (Fraunces, Inter, IBM Plex Mono) load from Google Fonts via CDN, so
  the page needs an internet connection to render with the intended
  typography.
