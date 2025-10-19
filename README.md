## Overview

A ready-to-go solution for integrating **Bambu Lab** printers with **[Spoolman](https://github.com/Donkie/Spoolman)** and **Postgres** using **Docker**.

This setup also uses the **[Bambu AMS Spoolman Filament Status connector](https://github.com/Rdiger-36/bambulab-ams-spoolman-filamentstatus)** to monitor filament usage and **AMS** events.

## Setup

- Create a `.env` file based on `.env.example` and fill in the required credentials
- Edit the `printers.json` file in `spoolman-bambu/config/printers/` and fill in the required printer details
- Run the configuration using `docker compose up -d`

## Access

- **Spoolman UI**: [http://localhost:8000](http://localhost:8000)
- **Bambu AMS connector**: [http://localhost:4000](http://localhost:4000)
