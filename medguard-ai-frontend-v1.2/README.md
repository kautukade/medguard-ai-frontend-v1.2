# ITCYBER MedGuard AI — Frontend Prototype v1.2

Frontend-only prototype for an AI-assisted medical shop / pharmacy loss-prevention and operations supervisor.

## Run

Open `login.html` directly, or run a local web server from this folder:

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080/`.

## v1.2 additions

- Full Transaction Investigation screen with simulated CCTV evidence, transaction correlation and explainable risk score.
- Evidence timeline that aligns camera, billing, payments and inventory activity.
- Camera AI Zone Editor UI for cash counter, high-value medicine, entrance, storage and custom zones.
- Detailed connector wizard patterns for network, device and business-software integrations.
- Medical shop connector catalog: Marg ERP Pharmacy, C-Square EcoGreen Express, GOFRUGAL Pharmacy, RedBook, SWILERP / RetailGraph, MEDEIL Pharmacy POS and TallyPrime.
- Medical agency / distributor connector catalog: Marg ERP Pharma Distribution, C-Square PharmAssist, SWILERP Distribution, MEDEIL / AllotMED, TallyPrime and a custom ERP connector.
- Advanced Owner Away control center with selectable monitoring and alert priorities.
- Opening Assistant and Daily Closing Assistant.
- System Health failure-state UI and diagnostics simulation.

## Important

This is still a frontend prototype. The software cards are connector **configuration templates**, not implemented vendor integrations. Real integration will require the supported API, read-only database/ODBC access, scheduled export or a local bridge available for the exact product/version installed at the client site.


## v1.2 AI Zone upgrades

- Owner-drawn free-form polygon zones
- Rectangle zones and entry/exit direction lines
- Ignore zones, zone presets, sensitivity, schedules and trigger delays
- Zone-specific recording options
- Inventory shelf/rack, POS counter and cash-drawer linking
- Perspective calibration and Test Zone UI
- Human-review feedback: Normal / Investigate / False Alert
- Incident case creation
- Shift cash reconciliation
- Rule cooldown, confidence threshold and 7-day simulation
- Camera-to-business context via shift/POS assignment

This remains a frontend prototype: camera inference, POS/payment APIs and real inventory sync are not connected yet.
