# Kaslin Govender

Original source export of saved Site version 1.

## Source provenance

Commit: eb4b5e1b692dbb6d8b9a49017faefb945d5771b6

The two original tracked files are preserved byte for byte:
- dist/index.html
- .openai/hosting.json

This is a self-contained static website. HTML, CSS, JavaScript and the SVG favicon are inline in dist/index.html. There are no external asset dependencies, package manifests, npm dependencies, build steps, environment variables or runtime secrets required by this version. The external venture links and mailto links remain unchanged.

## Run locally

Open dist/index.html in a browser, or run:

    python3 -m http.server 8000 --directory dist

Then visit http://localhost:8000.

## GitHub migration and deployment

Extract this folder, create a repository and upload its contents. Preserve the .openai folder if you want to retain the original configuration for reference. Its project_id identifies the existing Site. Independent static hosting does not use this file.

For a static hosting provider, leave the build command empty and set the publish directory to dist. For GitHub Pages, publish the contents of dist through a Pages deployment workflow, or copy dist/index.html to the repository root and choose that root as the Pages source.

README.md and export-manifest.json are export documentation added separately from the original source. Git history, credentials, and local tooling state are excluded. No original source file was changed and the existing Site was not modified or redeployed.
