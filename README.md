# Waypoint

A self-hosted navigation and routing application that combines GraphHopper routing engine with a modern React web interface. Waypoint provides offline-capable routing with turn-by-turn navigation, multiple transport profiles, and an intuitive map interface.

## Overview

Waypoint is a complete navigation solution that runs entirely on your own infrastructure. It consists of:

- **Backend**: Self-hosted GraphHopper routing engine with TileServer GL for map tiles
- **Frontend**: React web application with MapLibre GL for interactive maps
- **Features**: Multi-point routing, turn-by-turn instructions, address geocoding, and more

## Key Features

### ✅ Implemented Features

- **Self-hosted routing**: Complete offline navigation using GraphHopper
- **Multiple transport profiles**: Car and foot routing with optimized paths
- **Interactive markers**: Add, edit, and manage waypoints on the map
- **Multi-point routing**: Route between multiple markers with turn-by-turn instructions
- **Address geocoding**: Set start and end points using addresses
- **Route visualization**: Clear route lines with distance and ETA calculations
- **Collapsible sidebar**: Organized interface with route instructions and controls
- **Map controls**: Manual rotation, scale display, and interactive navigation
- **Route optimization**: Automatic route calculation and optimization
- **Distance calculations**: Both routing distance and "as the crow flies" measurements
- **Responsive design**: Works on desktop and mobile devices

### 🔄 Planned Features

- **GPS tracking**: Real-time location tracking and off-route detection
- **Voice guidance**: Audio turn-by-turn instructions
- **Speed alerts**: Speed-based notifications using map data
- **Elevation profiles**: Road altitude visualization
- **Layer management**: Multiple map layers and overlays
- **Real-time speed**: Current and maximum speed display
- **Automatic rerouting**: Dynamic route recalculation when off-route

## Architecture

### Backend Components
- **GraphHopper**: High-performance routing engine for processing OSM data
- **TileServer GL**: Serves vector and raster map tiles
- **Docker containers**: Isolated, scalable deployment

### Frontend Components
- **React 19**: Modern React with hooks and functional components
- **MapLibre GL**: Open-source mapping library (Mapbox GL alternative)
- **Vite**: Fast development and build tooling
- **Custom hooks**: Reusable logic for markers, routes, and map interactions

## Technology Stack

### Backend
- GraphHopper (Java-based routing engine)
- TileServer GL (Node.js map tile server)
- Docker & Docker Compose
- OpenStreetMap data processing

### Frontend
- React 19 with modern hooks
- MapLibre GL for interactive maps
- Vite for build tooling
- CSS modules for styling

## Data Sources

- **Routing data**: OpenStreetMap (.osm.pbf files)
- **Map tiles**: Self-hosted TileServer GL with OSM data
- **Geocoding**: GraphHopper's built-in geocoding capabilities

## Use Cases

- **Offline navigation**: Complete routing without internet dependency
- **Custom routing**: Multi-point routes with custom waypoints
- **Transport planning**: Optimized routes for cars and pedestrians
- **Map exploration**: Interactive maps with custom markers
- **Address-based routing**: Start and end point selection via addresses

## Privacy & Control

Waypoint is designed for privacy-conscious users who want:
- **Complete data control**: All data stays on your infrastructure
- **No tracking**: No external services or analytics
- **Offline capability**: Full functionality without internet connection
- **Custom data**: Use your own OpenStreetMap extracts

## Performance

The system is optimized for high-performance routing with:
- **Parallel processing**: Multi-threaded OSM data processing
- **Memory optimization**: Efficient caching and memory management
- **Scalable architecture**: Docker-based deployment for easy scaling
- **Custom profiles**: Optimized routing for different transport modes

---

*Waypoint provides a complete, self-hosted navigation solution that puts you in control of your routing data and privacy.* 
