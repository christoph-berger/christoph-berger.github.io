# Upload to GitHub Pages

Target repository: `christoph-berger/christoph-berger.github.io`

Permanent public URL: `https://christoph-berger.github.io/microstates/`

## Recommended: GitHub Desktop

1. Clone `christoph-berger/christoph-berger.github.io`.
2. Copy the complete `microstates` folder from this bundle into the root of the cloned repository.
3. Add your conference poster as `microstates/poster.pdf`.
4. Commit the changes, for example with the message `Add microstates poster companion site`.
5. Push to `main`.
6. On github.com open **Settings > Pages**. Under **Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
7. After deployment, open `https://christoph-berger.github.io/microstates/`.

The QR code already points to this permanent landing page. It does not need to be regenerated when individual files are updated later.

## Command-line alternative

```bash
git clone https://github.com/christoph-berger/christoph-berger.github.io.git
cd christoph-berger.github.io
# Copy the supplied microstates folder here
git add microstates
git commit -m "Add microstates poster companion site"
git push origin main
```
