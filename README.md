# Relatos Unidos
An interactive transmedia project exploring the gentrification and memory of the El Rosario neighborhood in Bogotá.

## Description

"Relatos Unidos" is a transmedia installation that contrasts the "statistical/virtual" projections of urban developers with the lived experiences of current residents. By merging physical scale models with digital archives, interactive web interfaces, and IoT-driven light installations, the project seeks to document the threat of displacement and create a space for community memory.

This project bridges the gap between artistic performance, documentary theater, and urban activism, designed specifically for circulation in public schools and community spaces in Bogotá.

## Technical Architecture

This project integrates physical and digital layers through a robust technological stack:
- Frontend (Interactive): Unity WebGL interface for visualization and real-time interaction, allowing visitors to explore the neighborhood and submit testimonies.
- Backend: Node.js (Express) server hosted on Hostinger, handling API requests and synchronizing data across the installation.
- Database: MongoDB for storing user-generated testimonies, community narratives, and urban data.
- IoT & Hardware: A Raspberry Pi/ESP32 network connected via MQTT to trigger localized LED lighting on the physical scale model, synchronizing digital input with physical architectural responses.

## Key Components
- Physical Scale Model: A tangible representation of the neighborhood that acts as the centerpiece for the interactive experience.
- Digital Archive: A web platform (relatosunidos.com) that collects collective memories and future visions of the territory.
- Documentary Theater: A performance piece where the scale model serves as a "living" scenographic element.
- Photographic Gallery: A photographic series by Santiago Merchán exploring the interiors of homes in the El Rosario neighborhood.
- Circulation Kit: Modular installation designed for public venues, focusing on pedagogical engagement regarding urban development.

## Documentation Structure
- /3D_Assets: Blender source files and low-poly architectural models.
- /UnityProject: Unity WebGL build and interactivity scripts.
- /Backend: Node.js server and API documentation.
- /Hardware: IoT logic and Python scripts for Raspberry Pi/LED control.
- /Docs: Project notes, pedagogical resources, and research on gentrification.
