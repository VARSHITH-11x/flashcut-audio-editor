FLASHCUT — Your Audio. Your Studio.
A free browser-based multitrack audio editor. Audio is processed locally in your browser.
Run
Open index.html in a modern browser. Microphone recording requires permission and a secure context (HTTPS or localhost).
Current features
Studio Gold theme with responsive desktop/mobile layout
Import multiple audio files as separate tracks
Playback, seek, zoom, waveform display, mute, solo and clip positioning
Drag-to-select regions with pointer/touch handling; trim, delete and split
Mix audible tracks into one new track
Join audible tracks sequentially in track-list order
Duplicate tracks and basic undo/redo for recorded editing actions
Live three-band EQ during playback
Local .flashcut project save/reopen
WAV export (built in)
MP3 export using the LAME encoder loaded on demand from jsDelivr (internet required)
FLAC, AAC/M4A and OGG export when the current browser exposes a compatible MediaRecorder encoder
Basic spectrum display and microphone recording where supported
Export compatibility notes
WAV is the dependable built-in format. MP3 encoding loads an external JavaScript encoder on demand, so an internet connection is needed for that export. FLAC, AAC/M4A and OGG are capability-dependent: browsers do not consistently provide these encoders through MediaRecorder. If the browser does not support the selected codec, FLASHCUT reports that it cannot export that format rather than creating a misleading file.
Known limitations after this upgrade
This is still a lightweight browser editor, not a full professional DAW.
Browser-native FLAC/AAC/OGG export is not guaranteed on every device/browser. A bundled multi-format encoder would be needed for consistent support across browsers.
EQ is applied to live playback; the current mix/export path does not bake the EQ filters into the rendered file.
Compressor, reverb and advanced spectral noise reduction remain unimplemented.
Clip fades and automation are not yet implemented.
Undo/redo covers the main track and destructive-edit operations, but is not a complete DAW-grade history system.
Large projects can use substantial memory because audio is held in browser memory and embedded in .flashcut project files. Keep original audio backups.
Privacy
Imported audio is processed locally; this build does not upload audio to a server. The MP3 encoder is fetched from jsDelivr only when MP3 export is selected.
