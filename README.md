# Mermaid Monument at Plac Górnośląski (CesiumJS Visualization)

A technical project featuring a 3D visualization of the Mermaid monument located at Plac Górnośląski in Gdynia (Orłowo), Poland. Built with **CesiumJS**, this application integrates photorealistic **Google 3D Tiles** city data with a custom 3D model.

## Features

* **Google 3D Tiles Integration:** Loads real-world urban surroundings using Cesium Ion assets (Asset ID: `2275207`).
* **Dynamic Shadows:** Full shadow mapping enabled for both objects and terrain (`Cesium.ShadowMode.ENABLED`).
* **Time Control:** The scene's timeline is hardcoded to **May 24, 2026, at 14:00 UTC** to ensure consistent, realistic lighting and shadow angles across the plaza.
* **Precise Camera Framing:** The initial view is optimized for a cinematic angle that highlights the monument within the context of the surrounding urban space.

---

## Geographic & Technical Data

The application anchors the object in global space using the following parameters:

### Monument Location
| Parameter | Value | Description |
| :--- | :--- | :--- |
| **Longitude** | `18.538774` | X Coordinate (Plac Górnośląski) |
| **Latitude** | `54.483220` | Y Coordinate (Plac Górnośląski) |
| **Height** | `60.7` m a.s.l. | Ground-level alignment adjustment |
| **Scale** | `2.2` | Scaling factor for the `pomnik.glb` model |
| **Heading** | `-90°` | Model rotation facing the plaza |

### Camera Settings (Starting Viewport)
* **Position:** `18.538560° E`, `54.483350° N`, Height: `66.5` m
* **Orientation Kinds:** Heading: `148°`, Pitch: `-22°` (looking slightly downward), Roll: `0.0°`

