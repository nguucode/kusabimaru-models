# 3D model credits

All models are licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/).
Modified by Kusabimaru (scripts/prepare-models.mjs in the plugin repo): logos, ground planes and accessories removed,
screen textures replaced with a blank display, some materials recolored, re-oriented, rescaled to real-world size,
re-centered, meshes simplified and compressed (EXT_meshopt_compression), textures resized to WebP.

| File | Original | Author | Source |
|---|---|---|---|
| iphone-17-pro.glb | "iPhone 17 Pro" | Ranguel | https://sketchfab.com/3d-models/iphone-17-pro-4541aa8a28324b33a2baaf81d263aaec |
| galaxy-s21-ultra.glb | "Samsung Galaxy S21 Ultra" | DatSketch | https://sketchfab.com/3d-models/samsung-galaxy-s21-ultra-cd962832be7744efb6b37fe0ee2027e7 |
| ipad-air-11.glb | "Ipad Air 5 (FREE)" | Artbor | https://sketchfab.com/3d-models/628ab0359d774af480be8eda9de70272 |
| surface-pro.glb | "Microsoft Surface Pro 3 + Touch Cover" | MD.Jobair Hossain | https://sketchfab.com/3d-models/microsoft-surface-pro-3-touch-cover-24052379ad2a4a57bd313aef83305dcf |
| macbook-air-13.glb | "MacBook Air M2" | rtql8d | https://sketchfab.com/3d-models/786fa23d402a4f90ae36c4168997f9cc |
| macbook-pro-16.glb | "macbook pro M3 16 inch 2024" | jackbaeten | https://sketchfab.com/3d-models/macbook-pro-m3-16-inch-2024-8e34fc2b303144f78490007d91ff57c4 |
| imac-24.glb | "iMac 2021" | DatSketch | https://sketchfab.com/3d-models/imac-2021-304cb06ffb554883a7a642b2b56754c1 |

Files are meshopt-compressed: load with a GLTF loader that has a meshopt decoder (three.js: `GLTFLoader.setMeshoptDecoder`).
