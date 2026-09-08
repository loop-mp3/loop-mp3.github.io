# Ambient music

Add audio files here using this naming format:

```text
artist_trackname.wav
```

Supported extensions include `.aac`, `.flac`, `.m4a`, `.mp3`, `.mp4`, `.oga`, `.ogg`, `.wav`, and `.webm`.

The landing page discovers files from the `/music/` directory listing. If your host does not expose directory listings, add a `manifest.json` file containing either an array of filenames or an object with a `files` array.
