# `EckiTruckr` Source Package

This directory contains all the primary source code and application logic for EckiTruckr.

## Key File Structure

* `__init__.py`: It signals to Python that this directory should be treated as a **package**. This allows us to use structured imports (e.g., `from EckiTruckr.utils import ...`).

* `main.py`: This file serves as the main **entry point** for the application.
    * When the application is run, the execution logic begins here.
    * As the project grows, `main.py` will primarily be responsible for organizing and invoking the main logic, which will be defined in other modules (`.py` files) within this same directory.
