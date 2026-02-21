# tb_vehicle_driftmode

Vehicle Drift Mode for FiveM

## Features
- Toggle drift mode on/off for vehicles you drive (by pressing the Shift key)
- Restrict drift mode to specific vehicles using config.lua, or allow all vehicles
- Simple notification system for mode status

## Installation
1. Place `tb_vehicle_driftmode.lua`, `config.lua`, and `fxmanifest.lua` in a folder inside your FiveM resources directory (e.g., `resources/[local]/tb_vehicle_driftmode`).
2. Add `start tb_vehicle_driftmode` to your `server.cfg`.
3. Restart your server or use `refresh` and `start tb_vehicle_driftmode` in the server console.

## Usage
- Get in a vehicle and press the **Shift** key to toggle drift mode.
- You will see a notification indicating if drift mode is enabled or disabled.
- Drift mode changes vehicle handling for easier drifting.

### Configuration
- Open `config.lua` to set vehicle restrictions:
	- Set `RESTRICT_TO_LISTED_VEHICLES = true` to allow only vehicles listed in `ALLOWED_DRIFT_VEHICLES` to use drift mode (by spawn code).
	- Set `RESTRICT_TO_LISTED_VEHICLES = false` to allow all vehicles to use drift mode.
	- Edit the `ALLOWED_DRIFT_VEHICLES` table to add or remove allowed vehicle spawn codes.
