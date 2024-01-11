# EINSat

# Exoplanet Characterization CubeSat Imaging System

## Introduction

This repository contains information and resources related to the imaging system for CubeSats designed to characterize exoplanets using the transit method of photometry. The system utilizes various image sensors, including CCD and CMOS sensors, as well as hyperspectral imaging sensors. The goal is to provide a comprehensive overview of the technology and its applications in space exploration.

## Image Sensors

### 1. Image Sensors Overview

Image sensors play a crucial role in the optical payload of CubeSats, enabling the capture of data during exoplanet transits. This section provides an overview of the following image sensors:

- **Charge-Coupled Devices (CCD) Sensors:**
  - Linear sensors with precise photon-to-charge conversion.
  - Conducts longer integrations for photometry function.
  
- **Complementary Metal–Oxide–Semiconductor (CMOS) Imaging Sensors:**
  - Integrates amplification directly in the pixel.
  - Faster readouts, used for star tracking and attitude determination.

- **Hyperspectral Imaging Sensors:**
  - Collects and processes information across the electromagnetic spectrum.
  - Used for advanced technology development and hyperspectral sensing.

### 2. Advantages and Disadvantages of CCD and CMOS Sensors

Explore the pros and cons of CCD and CMOS sensors in various astronomical settings, including read-out noise, quantum efficiency, and cost considerations.

### 3. Terms Related to Image Sensors

- **Dark Current:** Spurious electron generation in CMOS sensors in the absence of light.
- **Jitter Noise:** Signal corruption due to pixel response non-uniformity and spacecraft pointing error.
- **Read Noise:** Fluctuation in load resistance during electron counting.
- **Quantum Efficiency:** Probability of generating a photoelectron from an incident photon.
- **Piezo Stage:** Mechanical device for precise motion control, reducing spacecraft jitter.

## Image Sensor Models

### 1. Cypress HAS2 Detector

- Member of the STAR family of radiation-tolerant CMOS sensors.
- Array of 1024 x 1024 active pixels, supporting on-chip Non-Destructive Readout.
- Ideal for radiation environments where traditional sensors cannot survive.

### 2. CIS2521F

- Ultra-low-noise CMOS sensor by Fairchild Imaging.
- Low-light sensitivity, QE above 52%, and very low dark current.
- Used in Andor Neo camera.

### 3. GSense400BSI

- Scientific CMOS sensor with larger well depth and back-illuminated options.
- High dynamic range, low noise, and peak QE of 95%.
- Used in Andor Marana camera.

## Optical Payload and Imagers

### 1. iSIM-90 VNIR SWIR

- Lightweight optical payload for CubeSats, designed for high performance in a compact form.
- Covers VNIR spectral range, achieving ground resolution down to 1.65m from an altitude of 500km.

### 2. HyperScape100

- Hyperspectral push-broom imager for Earth Observation in CubeSats.
- Utilizes a CMOS image sensor and custom optical filter in the VNIR spectral range.

### 3. Caiman Imager

- High-resolution, multispectral camera optimized for integration with 6U or larger CubeSat frames.
- Offers imaging across 7 multispectral bands.

### 4. Chameleon Imager

- Multispectral or hyperspectral camera suitable for 3U or larger CubeSats.
- Integrates high-performance optics and space-qualified control electronics.

## Acknowledgments

[If there are any acknowledgments or references, mention them here.]

