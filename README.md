# VidyuthVaani MVP

VidyuthVaani is a bilingual citizen electricity assistance prototype based on the project presentation. The first MVP includes the citizen experience and a lightweight DISCOM operator workspace.

## Run locally

The app has no package dependencies. Start a local server from this folder.

```powershell
python -m http.server 5173
```

Then open `http://localhost:5173`.

## Included flows

- VoltAlert fault reports with category, location, phone, description and photo selection
- Local complaint reference IDs and status tracking
- PowerPulse community outage and restoration reporting
- Rule-based outage confidence updates
- Bill entry, slab-distance guidance and estimated appliance breakdown
- Subsidy matching for domestic, BPL and agricultural users
- English and Telugu citizen interface
- Citizen and DISCOM operator role switching
- Local browser persistence through `localStorage`

## Current scope

This is a frontend MVP. It uses local browser data so the complete experience is testable before the Flask API, authentication, database, OCR and map integrations are connected.
