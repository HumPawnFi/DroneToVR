# DroneToVR
Turn any 4K drone photo/video into a VR-ready 3D construction site model in &lt; 10 minutes — offline on a single desktop
# DroneToVR — Offline 4K Drone → VR Construction Site Models

Turn any drone photo or video into a measurable 3D site model — **100 % offline**, zero cloud, zero monthly fees.

https://github.com/user/DronesToVR/assets/123456789/demo.mp4

### What it does
1. Drag a 4K drone photo/video
2. Click one button
3. Get in < 10 minutes:
   - NDJSON (depth, materials, geometry)
   - USD file (Omniverse-ready)
   - GLB file (open in Meta Quest)
   - PDF summary report

Runs on a single NVIDIA DGX Spark Desktop (Blackwell).

### Why this matters for construction
- No data ever leaves your office
- No $5k+/month cloud bills
- Daily as-builts, quantity takeoffs, safety heatmaps
- Win bids with VR walkthroughs owners can actually use

### Tech Stack
- Ollama + LLaVA-34B (vision)
- Open WebUI (localhost:3000)
- Omniverse Kit SDK (USD export)
- Simple double-click start script

### How to run (for anyone with a DGX Spark)
```bash
./start.sh   # One click. That’s it.
