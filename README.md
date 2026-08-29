# Şevval Ulus Memis — Academic Website v2

This version is designed in the style of modern academic GitHub Pages used by ML/CS researchers:
compact navigation, profile-focused introduction, research bullets, education, news, publication cards,
project tags, and an academic rather than corporate visual style.

## Publish

Create a public repository named:

`sevvaluluss.github.io`

Upload:
- `index.html`
- `styles.css`
- `assets/`

Then open:

`https://sevvaluluss.github.io`

## Add your profile photo

Put your photo at:

`assets/profile.jpg`

Then replace this block in `index.html`:

```html
<div class="photo-placeholder">
  <span class="initials">SU</span>
  <span class="photo-note">Add your photo</span>
</div>
```

with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Şevval Ulus Memis">
```

and add this to `styles.css`:

```css
.profile-photo{
  width:172px;
  height:172px;
  object-fit:cover;
  border-radius:7px;
}
```

## Before final launch

Replace the placeholder Google Scholar and LinkedIn links with your real profile URLs.


## Street Photography Gallery

The website now includes a `Street Photography` section and an `Outside Research` section.

To add your own photographs:

1. Put 6–12 selected images in `assets/photography/`.
2. Recommended filenames:
   - `street-01.jpg`
   - `street-02.jpg`
   - `street-03.jpg`
3. In `index.html`, replace a placeholder like:

```html
<div class="gallery-placeholder">Photo 01</div>
```

with:

```html
<img src="assets/photography/street-01.jpg" alt="Street photograph by Şevval Ulus Memis">
```

Keep the gallery selective. Six to twelve strong images will look more professional than a very large archive.
