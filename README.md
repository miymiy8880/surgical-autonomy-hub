# VISCERAL VISION v2.0: Real-Time Autonomous Surgical Field Assistant

Visceral Vision v2.0 upgrades the core simulation matrix into a polished, high-fidelity Surgical HUD (Heads-Up Display). Optimized for deployment on cloud hosting platforms like GitHub Pages, v2.0 integrates modern utility-first styling with dynamic repository asset resolving to create an immersive, responsive frontend template ready for medical AI integration.

Live Demo: https://miymiy8880.github.io/surgical-autonomy-hub/

## New Features in v2.0
- Medical Software Aesthetic: Redesigned from the ground up using Tailwind CSS to mirror the high-contrast, dark-mode styling of modern endoscopy camera towers and robotic surgical consoles.
- Robotic CV Pipeline Diagnostics: Added a live mock HUD metrics panel tracking parameters like Segmentation Accuracy (97.8%), Depth Prediction Loss (0.009), and Tool Vector Latency (1ms).
- Dynamic Path Resolver: Upgraded the image engine with an automated repository subpath directory locator. This fixes case-sensitive asset broken links natively when running on live cloud servers.
- Native Repository Samples: One-click sample loaders mapped to verified repository assets (170207-16-1024x741.jpg and lap_frame1.jpg.jfif) for immediate out-of-the-box evaluation.

## HUD Canvas Breakdown
- Panel 1: Raw Field Input. Displays the baseline endoscopy camera stream feed.
- Panel 2: Task 1 Tissue Segmentation. Organ class parsing dividing the field into Target Zones and Margins.
- Panel 3: Task 2 Vessel Depth Criticality Map. High-risk zone heat-mapping showing Do-Not-Cut Zones.
- Panel 4: Task 3 Optimal Incision Plane. AI-predicted linear vector trajectory overlay.

## Technology Stack
- Frontend UI: Tailwind CSS via CDN runtime engine
- Graphics Pipeline: HTML5 Canvas API and 2D Context Manipulation
- Environment Handling: Location-aware JavaScript URL absolute resolver

## Future Roadmap and Contribution Ideas
This repository is designed to be an easily forkable, lightweight scaffolding for medical imaging researchers. If you want to contribute or build on top of this foundation, consider these tracks:

1. ONNX Runtime Web Integration: Swapping the simulated canvas filters for actual browser-side deep learning inference using quantized model files.
2. Dynamic Video Stream Feed: Binding the input loader to a live video element or web-camera stream instead of static images.
3. Custom Color Lookup Tables: Expanding the segmentation function to support distinct colors for a broader variety of surgical tools and organ tissues.

## Contributing
Forks, pull requests, and repository stars are highly welcome. If you use this interface as a frontend dashboard template for your own surgical AI research datasets, please feel free to open an issue or share your project link.
