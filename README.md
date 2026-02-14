# MMFM-BIOMED Website

Static website for the **MMFM-BIOMED @ CVPR 2025** workshop.

## Files

- `index.html` - page content and layout
- `styles.css` - visual design and responsive styling

## Deploy to GitHub Pages

1. Create a new GitHub repository named `<username>.github.io` (or use any repository and deploy from branch/folder settings).
2. Upload these files to the repository root.
3. In GitHub, open **Settings -> Pages**.
4. Under **Build and deployment**, choose:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `master`), folder `/ (root)`
5. Save and wait 1-2 minutes.
6. Open the URL shown in GitHub Pages settings.

## Quick Customization

- Replace speaker/organizer avatars with photos by swapping each initials `div.avatar` in `index.html`.
- Add links (OpenReview, registration, schedule PDF) by editing the call-to-action buttons and section content.
- Update colors in `styles.css` under `:root` variables.
