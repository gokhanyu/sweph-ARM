# 🌍 Swiss Ephemeris DLL for Windows 11 ARM64

This project builds the **Swiss Ephemeris** astronomical computation library (by [Astrodienst](https://www.astro.com/swisseph/)) as a **DLL (Dynamic Link Library)** on **Windows 11 ARM64**.

## 🚀 Features

- ✅ Native ARM64 compilation
- ✅ Output: `swedll64-ARM.dll`
- ✅ Compatible with C, C++, C#, Python (via ctypes), and more
- ✅ High-precision calculations: planetary positions, lunar phases, houses, eclipses
- ✅ Optional support for JPL DE4xx ephemeris files
- ✅ Cross-platform compatible core (cleaned from the test code)

## 📦 Source Files Included

The following core Swiss Ephemeris `.c` files are compiled into the DLL:

swedate.c - Date/time conversions
swehouse.c - Astrological house calculations
swejpl.c - JPL ephemeris interface
swemmoon.c - Lunar position
swemplan.c - Planetary positions
sweph.c - Main ephemeris engine
swephlib.c - Utility functions
swecl.c - Solar eclipse calculations
swehel.c - Heliocentric computations
sweephe4.c - JPL DE4xx ephemeris reader (optional)
sweclips.c - Eclipse prediction functions (optional)

## 📦 Swiss Ephemeris Official Github Repository
The official Swiss Ephemeris source code can be found at: https://github.com/aloistr/swisseph

📚 License
Swiss Ephemeris is open-source under the GNU Lesser General Public License (LGPL).
See: https://www.astro.com/swisseph/swisseph.htm
