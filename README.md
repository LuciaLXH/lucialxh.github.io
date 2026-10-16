# Lucia (Xiaohan) Liu — Portfolio

Personal portfolio: **https://lucialxh.github.io/**

Selected projects:
- [NZ Water × Population](https://lucialxh.github.io/nz-data-dashboard/): Python, DuckDB SQL, ECharts and Leaflet.
- [Union Bakery Payroll](https://union-bakery-payroll-portfolio.onrender.com): Python and Streamlit public demo with fictional session data. The separate owner-testing application uses PostgreSQL.

## Edit and publish

This repository is the primary source for the GitHub Pages homepage. Edit `index.html`, `styles.css` and `assets/`, then push to `main`. GitHub Pages publishes from the repository root, with `.nojekyll` disabling Jekyll. No build or database is required.

Preview locally:

```sh
python3 -m http.server 18503 --bind 127.0.0.1
```

This basic server is suitable for layout previews but does not support HTTP byte ranges. Use a range-capable static server when testing video seeking, and verify `206 Partial Content` responses on the deployed video.

The prior Sites deployment remains a separate snapshot; future homepage edits should be made here.

## Personal media

The owner-selected warm editorial design uses upright serif headings, a warm paper background, plum text and iris-purple links and fine rules. The `.hero-media` section uses the owner's selected riverside photograph, resized for the web with EXIF/XMP/IPTC metadata removed. A near-square 371:347 frame crops the sides to match the owner's reference, with a maximum size of approximately 426 × 398 CSS pixels, 12 px corners, a fine iris border and a subtle shadow. The frame scales down on smaller screens; the original photograph is unchanged.

The merged About section includes a short biography and the owner's complete personal introduction video (approximately 3 min 24 sec). `assets/lucia-introduction.mp4` is a 1280 × 720 H.264/AAC web copy (approximately 60 MB) with the metadata at the start for network playback. The original MOV is unchanged. The video retains its embedded subtitles and closing LinkedIn QR code; its opening title card supplies the initial image without a separate poster. Native controls provide click-to-play, volume, seeking and fullscreen, with muted initial playback, inline playback and no autoplay. The expandable transcript preserves the owner's supplied narration, grouped into four titled sections.

## Asset attribution

Water preview: public NZ Water × Population dashboard, captured 12 October 2026. Data: Stats NZ (CC BY 4.0), Taumata Arowai NEPR (CC BY 3.0 NZ); see the linked repository for full methods and attribution. Payroll preview: the project's public English demo, fictional data only. Fonts: Lora and Manrope via Google Fonts, with system fallbacks.

The site has no database connection, analytics, contact form or private payroll data.

Homepage photograph: IMG_E2826.jpg, supplied and selected by the portfolio owner. The earlier graduation photo is no longer used on the homepage.

Introduction video: Lucia.MOV, supplied and approved for publication by the portfolio owner.
