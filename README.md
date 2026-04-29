PNG to ICO Converter
A pure frontend tool that converts PNG images to ICO icon format directly in your browser. No server upload required — all processing happens locally.

Features
Drag & Drop — Drop a PNG image or click to select
Multiple Sizes — Choose from 16×16, 32×32, 48×48, 64×64, 128×128, 256×256
Multi-size Packing — Select multiple sizes and pack them into a single .ico file
BMP DIB Format — Generates standard ICO files with BMP DIB image data for maximum compatibility across all platforms
Transparency Support — Preserves alpha channel via 32-bit BGRA pixels and AND mask
Bilingual UI — English / 中文, with preference saved to localStorage
Zero Dependencies — Single HTML file, no backend, no libraries
How to Use
Open png-to-ico.html in any modern browser
Upload a PNG image (drag & drop or click)
Select desired output sizes
Click Convert & Download ICO
The .ico file will be downloaded automatically
Technical Details
ICO Format: Standard ICO container with BMP DIB (BITMAPINFOHEADER) entries
Color Depth: 32-bit BGRA with alpha channel
AND Mask: 1-bit/pixel transparency mask for legacy system compatibility
Byte Order: Little-endian, per ICO specification
Image Scaling: Canvas API with high-quality smoothing (Lanczos-equivalent)
Browser Support
Works in all modern browsers: Chrome, Firefox, Safari, Edge.
