# City Navigation Application

## Technical Features

- **Open Street Map Integration**: Efficiently reads data from the Open Street Map database.
- **Route Calculations**: Calculates navigation routes between two points, accommodating both car-only and car-plus-walking scenarios.
- **Advanced Pathfinding**: Utilizes Dijkstra’s Algorithm enhanced with A* search optimization for the routes in the city.
  
- **Travelling Salesman Problem**: Solves complex routing problems involving multiple pickup and drop-off points with specific carrying capacities, aiming for the most efficient route.
- **Optimization Techniques**: Employs greedy algorithms, multi-start methods, and iterative improvement algorithms (e.g., 2-opt, Intersection Swap) to progressively approach optimal solutions.
- **Performance Enhancements**: Optimizes runtime through multi-threading and precomputing/caching pathfinding results.

## Visual Features

- **Points of Interest**: Displays various points of interest with custom icons.
- **Subway Stops**: Clearly marks subway stops on the map.
- **One-Way Streets**: Highlights one-way streets for better navigation.
- **Dark Mode**: Follows WCAG contrast guidelines for accessibility.
- **Dynamic Street Names**: Shows only one street name at a time, keeping it visible on the screen.
- **Zoom-Level Adjustments**: Dynamically loads visual elements based on zoom level.
- **High Detail Mode**: Smooths out jagged road edges for a cleaner look.
- **Geographic Features**: Differentiates between main roads, non-main roads, and geographic features like water, parks, and beaches.

## User Interface and Interaction Features

- **Intuitive Map Selection**: Easy map selection with a user-friendly interface.
- **Search Suggestions**: Drop-down menu for search suggestions and autocomplete functionality.
- **Splash Screen**: Engaging loading screen.
- **Toggle Information**: Options to toggle dark mode, one-way streets, subway stops, and points of interest.
- **Categorized Points of Interest**: Custom icons for different categories of points of interest.
- **Map Navigation**: Zoom in/out, pan around, and search for points of interest or street intersections.
- **Interactive Elements**: Click to get details about specific intersections.
- **Help Menu**: Provides help text and error dialog popups.
- **Status Bar**: Displays information and usage instructions.
- **Navigation Routes**: Start/end navigation routes at searched intersections or points of interest.
- **Adjustable Parameters**: Change navigation parameters like turning penalty, walking speed, and walking limit.
- **Route Highlighting**: Highlights routes as you pan through them and displays information in the status bar.
- **Clear Instructions**: Provides easy-to-understand navigation instructions for both car and walk/car transportation.

## Algorithms

- **City as a Graph**: Models the city map as a directed, weighted graph with intersections as nodes and streets as edges. Weights are based on actual street data like length and speed limits.
- **Optimized Pathfinding**: Uses Dijkstra’s Algorithm with A* search optimization to find the shortest path by prioritizing the most promising routes.
- **Walking + Driving**: Implements Multi-Source Dijkstra’s Algorithm to find the best start point for walking and then driving to the destination.
- **Travelling Salesman Solutions**: Generates initial solutions using greedy algorithms and multi-start methods, then improves them with iterative algorithms like 2-opt and intersection swap.

## Libraries Used

This application is designed to run on Linux (tested on Debian and Ubuntu) and utilizes several libraries to achieve its functionality.


