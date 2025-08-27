# Advanced Goalkeeper Analytics System

## Overview

This is a comprehensive goalkeeper analytics system that applies advanced mathematical concepts including Euclidean geometry, probability theory, and optimization algorithms to analyze and improve goalkeeper performance. The system provides real-time analysis of save probabilities, optimal positioning strategies, and performance metrics using interactive visualizations.

The application combines physics-based ball trajectory modeling with sophisticated probability calculations to simulate realistic football scenarios. It features heat map generation for coverage analysis, optimization algorithms for finding ideal goalkeeper positions, and comprehensive performance tracking capabilities.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: Streamlit-based web application for interactive data science
- **Visualization Engine**: Dual visualization system using Plotly for interactive web graphics and Matplotlib for static analysis
- **Session Management**: Streamlit session state for maintaining analysis results and scenario data across user interactions
- **Layout Design**: Wide layout with expandable sidebar for configuration controls

### Core Analytics Engine
- **Physics Engine**: Advanced trajectory modeling using projectile motion with drag, Magnus effect, and gravity calculations
- **Probability Models**: Multi-component probability system calculating save likelihood based on geometric, reaction time, positioning, and physical capability factors
- **Optimization System**: Scipy-based optimization using differential evolution and minimize algorithms for finding optimal goalkeeper positions
- **Geometry Calculator**: Euclidean geometry calculations for shot angles, coverage areas, and spatial relationships

### Data Architecture
- **Data Models**: Dataclass-based structured data representation for goal dimensions, goalkeeper profiles, and shot scenarios
- **Session State**: In-memory storage using Streamlit's session state for scenarios and analysis results
- **Configuration Management**: Real-time parameter adjustment through sidebar controls

### Mathematical Framework
- **Geometric Analysis**: Shot angle calculations using vector dot products and spatial coverage analysis
- **Probability Theory**: Weighted geometric mean combination of multiple probability components with empirical constants
- **Optimization Algorithms**: Multi-objective optimization with configurable constraints and bounds
- **Physics Simulation**: Numerical integration for trajectory calculations with realistic ball physics

### Visualization System
- **Heat Map Generation**: Interactive probability and pressure zone visualizations with customizable color scales
- **Trajectory Visualization**: 3D ball path rendering with real-time updates
- **Performance Analytics**: Statistical charts and comparative analysis displays
- **Interactive Controls**: Real-time parameter adjustment with immediate visual feedback

## External Dependencies

### Core Libraries
- **Streamlit**: Web application framework for data science applications
- **NumPy**: Numerical computing for mathematical operations and array processing
- **Pandas**: Data manipulation and analysis library
- **SciPy**: Scientific computing library for optimization, integration, and statistical functions

### Visualization Dependencies
- **Plotly**: Interactive plotting library for web-based visualizations including graph objects and express modules
- **Matplotlib**: Static plotting library for scientific visualization and analysis charts

### Mathematical and Scientific Computing
- **SciPy.optimize**: Optimization algorithms including minimize and differential_evolution
- **SciPy.spatial**: Distance calculations and spatial analysis functions
- **SciPy.integrate**: Numerical integration for physics calculations
- **SciPy.stats**: Statistical distributions and probability functions

### Data Processing
- **JSON**: Configuration and data serialization (Python standard library)
- **Math**: Mathematical functions for trigonometric and geometric calculations (Python standard library)

The system is designed as a standalone analytics application with no external database requirements, using in-memory processing for real-time analysis and visualization.
