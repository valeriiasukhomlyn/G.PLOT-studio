G.PLOT Studio (Android & Web)

G.PLOT Studio is a standalone, offline-first CAM & CNC control suite for 2D pen plotters, diode laser engravers, and desktop CNC routers — available as a native Android app (Kotlin / Jetpack Compose) and a Web app (HTML5 / Web Serial API).

🌐 Live Web Version: https://gplot-studio.netlify.app/

Key Features
Image, Vector & PDF to G-Code: Convert PNG, JPG, SVG, DXF, and PDF files locally on-device with zero server uploads.
6 Vectorization Modes: Marching Squares Contours (+ RDP & Chaikin smoothing), Contours + Hatch Fill (1-to-1 pocket islands), Boustrophedon Scanline, 3-Layer Halftone, Centerline (Zhang-Suen Skeleton), and Canny Edges, plus 2-Opt route optimization and Kåsa G2/G3 arc fitting.
CAD Primitives & Vector Text: Built-in parametric shapes and custom text-to-G-Code generator.
Interactive 2D Canvas & Simulator: Cursor/pinch zoom, node editor, corner rounding, freehand draw/erase, background underlay, and step-by-step toolpath simulation.
Universal CNC Controller Support (8 Presets):
Arduino Uno R3 + CNC Shield V3 (ATmega328P, Optiboot 1.6s wait)
ESP32 32-bit (FluidNC, MKS DLC32, Grbl_ESP32)
STM32 / RP2040 / Teensy (grblHAL)
CNC 3018 Pro (Z-axis), Arduino Nano V4, Diode Lasers (M4), Marlin 2.x (M280 P0), and CoreXY / iDraw plotters.
Direct Hardware Connectivity: USB OTG (13+ USB-UART/CDC chips) on Android, Web Serial API on desktop Chrome/Edge, plus Bluetooth SPP and Wi-Fi TCP.
7 Languages: English, Ukrainian, Russian, German, French, Arabic (RTL), and Chinese.
Built-in Calibration & Beginner Guide: 2-step $100/$101 steps/mm calibration wizard and interactive 4-step Quick Start guide.
Tech Stack
Android: Kotlin, Jetpack Compose, Android USB Host API, Bluetooth SPP, TCP Sockets.
Web: Vanilla HTML5 / CSS3 / JavaScript Canvas 2D, Web Serial API (hosted on Netlify).
License

All rights reserved © 2026 G.PLOT Studio.
