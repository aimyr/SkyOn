# SkyOn — drone-assisted agricultural GIS

SkyOn is a project concept and early prototype exploring how drones, sensors, and understandable data summaries could make agricultural GIS workflows more accessible in Kazakhstan.

The proposed system combines aerial surveying, a ground station, sensor measurements, and software that presents maps and explanations to users. This repository documents the idea and preserves small automation examples; it is not a complete deployed GIS platform.

## Repository contents

| File | Purpose |
| --- | --- |
| [PROJECT SKYON, ENG.pdf](PROJECT%20SKYON%2C%20ENG.pdf) | Project presentation |
| [ChatGPT_API_Integration_for_Analysis](ChatGPT_API_Integration_for_Analysis) | Example prompt-based analysis of terrain and video-summary inputs |
| `script_automates_flight_and_triggers_video_recording.\\` | DroneKit/Pixhawk mission example with survey waypoints and a camera command |
| `SkyOn_ a system designed for the agricultural industry to make GIS research more accessible.mp4` | Project demonstration file |

## Technical direction

- Pixhawk / ArduPilot for drone control and survey missions.
- DroneKit and MAVLink for mission automation.
- Geospatial and sensor data as inputs to an analysis interface.
- AI-generated explanations to help non-specialists interpret outputs.

The examples contain placeholder coordinates, device paths, and an API-key placeholder. The flight example needs its MAVLink import and a verified hardware configuration; the AI example uses an older OpenAI SDK interface. They are preserved as prototype examples, rather than documented as ready-to-run production components.

## Status

The project presentation includes proposed hardware, business assumptions, and development plans. Those proposals should be read separately from the limited implementation published here. This repository does not establish operational survey accuracy, autonomous deployment, or validated AI recommendations.

[Project demo](https://youtu.be/chiZU74GAgI) · [Aimer's current project overview](https://github.com/aimyr)
