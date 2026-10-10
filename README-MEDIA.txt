# Retro Birthday Website — media asset guide

## Where to put files

Keep the folder structure exactly like this:

```text
retro-birthday-site/
├── index.html
└── assets/
    ├── photos/
    │   ├── photo-01.jpg
    │   ├── photo-02.jpg
    │   ├── photo-03.jpg
    │   └── photo-04.jpg
    ├── videos/
    │   ├── video-01.mp4
    │   └── video-02.mp4
    └── audio/
        └── birthday-song.mp3
```

## Required filenames

### Photos
- `assets/photos/photo-01.jpg`
- `assets/photos/photo-02.jpg`
- `assets/photos/photo-03.jpg`
- `assets/photos/photo-04.jpg`

### Videos
- `assets/videos/video-01.mp4`
- `assets/videos/video-02.mp4`

### Optional birthday song
- `assets/audio/birthday-song.mp3`

The filenames and capitalization must match exactly. If your photo is PNG or WEBP, convert it to JPG or change the matching path in `index.html`. For videos, MP4 (H.264/AAC) is the safest browser-compatible choice.

## Add the files
1. Extract this ZIP.
2. Copy your photos/videos into the matching folders.
3. Rename them to the filenames above.
4. Upload the whole folder contents to your GitHub repository, keeping `index.html` at the repository root.
5. Enable GitHub Pages in the repository settings.

## Supabase reminder
The guestbook still needs your Supabase project URL and anon/publishable key configured in `index.html`. Never put a `service_role` or secret key in a public website.

## Important
The ZIP includes the website and folder structure, but not your personal photos, videos, or song yet. Add your own media files before publishing so the file paths resolve correctly.
