# LuminaStudio

Privacy-first browser video studio. Media is processed locally; files are never uploaded.

## Run
`npm install && npm run dev`

## Static build
`npm run build` creates `dist/`, ready for shared hosting `public_html`.

## Notes
Browser-native export depends on MediaRecorder support. Optional single-thread FFmpeg WebAssembly is loaded on demand for advanced conversions. Large 4K files need significant RAM. Fonts and FFmpeg runtime are fetched from CDNs; video content is not sent to them.