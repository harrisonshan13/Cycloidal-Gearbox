# Cycloidal Gearbox

Custom **15:1 3D-printed cycloidal drive** designed from parametric first principles. Originally developed as a rotating base actuator for a personal project, now being repurposed as the joint actuator for [ALFRED](https://github.com/harrisonshan13/6DOF), a 6DOF robotic arm.

---

## 📄 Full design log

The complete development log — iterations, DFM findings, prototype photos, test videos, and V2 direction — lives in the deck below. **The `.pptx` is the source of truth (embedded videos play in PowerPoint).** The PDF is a static export for quick in-browser viewing.

- **[cycloidal-gearbox-design-log.pptx](docs/cycloidal-gearbox-design-log.pptx)** — download to view with videos
- **[cycloidal-gearbox-design-log.pdf](docs/cycloidal-gearbox-design-log.pdf)** — static preview (no videos)

---

## Assembly overview
![Exploded view](docs/images/gearbox-exploded.png)

## Design targets
- **15:1 reduction ratio** (single-stage cycloidal)
- **FDM-printable** with only standard off-the-shelf hardware (bearings, dowel pins, thrust bearing)
- Sub-1° angular accuracy at output
- Compact envelope suitable for robotic joints

## Development

Iterated through **4 hardware prototypes** to characterize FDM manufacturing tolerances (±0.2 mm on lobe diameter), sliding vs. rolling friction at output pins, and stepper misstep behavior under load. Introduced **needle bearings on the output pins** to convert sliding to rolling contact.

## Current work

Redesigning from scratch to a **44 mm OD** package — roughly **60% smaller** than the first version — to fit inside the ALFRED joint housings.

## Contact

Harrison Lanfrank — harrisonshan13@gmail.com
