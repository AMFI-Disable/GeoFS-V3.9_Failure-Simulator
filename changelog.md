# Changelog

All notable changes, emergency simulation mechanics, and version releases for GeoFS-V3.9 Failure Simulator are documented in this file.

---

## [2.0.2] - Multi-Bogie Indexing And Slider Safety

### Added
- **Multi-Bogie Gear Detection**: Intelligent keyword mapping for complex multi-wheel assemblies on airliners (A380, B747).
- **Draggable Control Launcher**: Draggable button interface with screen boundary detection and `localStorage` position persistence.

### Fixed
- **In-Flight Slider Lock**: Automatically disables probability adjustments while emergency simulations are actively running.
- **Hydraulic Leak Depletion Curve**: Calibrated hydraulic pressure loss rates across primary flight controls.

---

## [2.0.0] - Probabilistic Multi-System Architecture

### Added
- **Multi-System Failure Engine**: Simulates independent or cascaded failures across Engines, Fuel Tanks, Hydraulics, Flight Controls, Electrical Bus, and Trim/MCAS.
- **Customizable Probability Sliders**: Configurable failure thresholds ranging from 0.1% to 100%.

---

## [1.0.0] - Initial Production Release

Initial standalone release of the system failure simulation framework for GeoFS.
